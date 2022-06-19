# Treating photos in the cloud

## Summary
Objective: Recognizing automatically fruits from images with the help of VGG16 and PCA . 

Description: 
I developed in a Big Data environment a first data processing chain of images of fruits which includes preprocessing and a dimension reduction with VGG16 and PCA. The purpose is to recognize different fruits automatically from images. I started by creating an Amazon account and a bucket where the photos can be uploaded. I also created an EC2 server which could be used to pre-process photos. After that, I created a Databricks account. The company provides a free account for two-weeks; where it is possible to configure the account with the AWS bucket and create a cluster to preprocess the images. Databricks also provides a notebook environment to facilitate data downloading and processing. I then did the preprocessing and reduction of dimension on Databricks with pyspark. I saved the parquet creation file to the docs on github.

<img width="697" alt="Capture d’écran 2022-06-19 à 21 37 01" src="https://user-images.githubusercontent.com/101344485/174497621-71ae8b74-a46f-4bdb-a838-b5d832b7c73a.png">

<img width="359" alt="Capture d’écran 2022-06-19 à 21 40 38" src="https://user-images.githubusercontent.com/101344485/174497697-c0cec484-635f-4c5b-afab-c4162ddb7b31.png">

<img width="362" alt="Capture d’écran 2022-06-19 à 21 40 45" src="https://user-images.githubusercontent.com/101344485/174497701-79ccf601-c065-4f04-b33f-f4fcaf7eb97c.png">

<img width="595" alt="Capture d’écran 2022-06-19 à 21 37 55" src="https://user-images.githubusercontent.com/101344485/174497637-cbdd7f2c-c2c6-4cb3-8391-1bf936599f33.png">
