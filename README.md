# Treating photos in the cloud

## Summary
Objective: Recognizing automatically fruits from images with the help of VGG16 and PCA . 

Description: 
I developed in a Big Data environment a first data processing chain of images of fruits which includes preprocessing and a dimension reduction with VGG16 and PCA. The purpose is to recognize different fruits automatically from images. I started by creating an Amazon account and a bucket where the photos can be uploaded. I also created an EC2 server which could be used to pre-process photos. After that, I created a Databricks account. The company provides a free account for two-weeks; where it is possible to configure the account with the AWS bucket and create a cluster to preprocess the images. Databricks also provides a notebook environment to facilitate data downloading and processing. I then did the preprocessing and reduction of dimension on Databricks with pyspark. I saved the parquet creation file to the docs on github.
