# Face-Classification

Face Classification and Verification with image features. 

The classification is done based on the following features:
- Eigen Faces / PCA 
- Kernel PCA
- Fisher Face / LDA
- Kernel Fisher Face
- VGG Features 
- Resnet Features

The classifier is tested using three face datasets
- Yale Face Dataset
- IMFDB
- IIIT-CFW

## Face Recognition
**Database** : IMFDB </br> 
**Classification** : Classifies images based on face recognition

`imfdb_dict = {`<br>
    `'MadhuriDixit': 0,`</br>
    `'Kajol': 1,` </br>
    `'SharukhKhan': 2,` </br>
    `'ShilpaShetty': 3,` </br>
    `'AmitabhBachan': 4,` </br>
    `'KatrinaKaif': 5,` </br>
    `'AkshayKumar': 6,` </br>
    `'Amir': 7}` </br>

The following are few results of face recognition

![Screenshot](1.png)

## Gender Prediction
**Database** : IIIT-CFW </br>
**Classification** : Male/Female 

`Classify = {` </br>
    `Female = 1` </br>
    `Male = 0}`

The following are few results of gender classification 

![Screenshot](2.png)

Find the code and the output at [Jupyter Notebook](../master/Face_Classifier.ipynb) and a detailed report at [Report.pdf](../master/Report.pdf)

This is done as part of the Statistical Methods of AI course at IIIT-Hyderabad.