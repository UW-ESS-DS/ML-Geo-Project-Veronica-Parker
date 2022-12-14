# ML-Geo-Project-Veronica-Parker
Veronica and Parker's repository for the MLGeo class project

Parker's final project employs a PCA for distributed acoustic sensing (DAS) data dimensionality reduction and compression. The PCA is accomplished with a singular value decomposition (SVD) of the covariance matrix for the original data file. An earthquake was recorded by the Whidbey Island DAS array deployed by UW researchers (Brad Lipovsky et al) on September 8, 2022 near Lofall, WA. The PCA reduces the dimensionality of the DAS data file from (6000,1721) to (6000,117). The data compression ratio is 6:1 (i.e. file size reduced from ~41Mb to 6.7Mb) and achieves a spacing saving metric of ~83%. 

The code that generates the figures "Whidbey_pca.png" and "explainedVar.png" is posted here as "mlGeo_pca.ipynb" in a jupyter notebook. 
