# MED263-Tutorial

## Google Colab
### Please ensure that you can use Google Colab. If there are issues opening the notebook on your UCSD account, please try using your personal gmail account. The python script can be accessed using the following link: https://colab.research.google.com/drive/1TjY3m1oxA3KqIoFQn0ArR5alS79DXgAQ?usp=sharing.

## Data 
### The data can be downloaded through the following link: https://www.10xgenomics.com/datasets/human-breast-cancer-ductal-carcinoma-in-situ-invasive-carcinoma-ffpe-1-standard-1-3-0. Note that you will have to make a 10x Genomics account. 
The following files need to be downloaded from the link: 
1. Feature / barcode matrix HDF5 (filtered)
2. Spatial Imaging Data

### Steps to organize data for spatial analysis:
1. Unzip the spatial imaging data, and create a folder in the Google Drive titled "Dataset"
2. Paste the two files we downloaded in "Dataset". 
3. Rename the spatial imaging data folder to "spatial".
4. Rename the h5 matrix file to "filtered_feature_bc_matrix.h5".

![alt text](https://i.ibb.co/KLbV3r8/fold.png)

## Software/Libraries 
### The following libraries need to be installed using the following commands on the Python Notebook:
1. ScanPy: !pip install scanpy==1.9.3
2. Leiden: !pip install leidenalg
3. Decoupler: !pip install decoupler
4. Omnipath: !pip install omnipath
