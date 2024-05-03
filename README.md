# Automated Detection and Classification of Oral Lesions Using Deep Learning for Early Detection of Oral Cancer
### in this notebook we implemented 2 models:

## 1- Random Forest classifier
Feture Extraction:  to extract features to be used in random forest from images
-  HOG features shape from an image
-   LBP features texture from an image
-   color histogram features from an image
  
Hyperparameters: 
- n_estimators=100
- max_depth=40

  
![image](https://github.com/zainbmaged/Project/assets/101899558/7acaf67b-5ea1-46fc-81b5-63b59b43edd3)


## 2-  ResNet-101 which is a Convolutional Neural which is proposed in the disscussed paper some of the hyperparameters where reduced to save RAM
Hyperparameters: 
- learning rate =0.001
- momentum=0.9
- weight_decay=0.005
- num_epochs = 3 instead of 100 
- batch_size=64 instead of 128


![image](https://github.com/zainbmaged/Project/assets/101899558/b410fc4d-f1ef-4e3c-81b4-92941babd877)

### the dataset used is smaller than the one used in paper due to the available computational power
