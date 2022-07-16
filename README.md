# Autism Spectrum Disorder Prediction for Toddlers using Machine Learning Algorithms in Saudi Arabia Regions

I developed this project as part of my graduation project. This project is in machine learning. We collected autism screening data for toddlers in Saudi Arabia and built machine learning models to predict autism in Saudi toddlers.

## Dataset Visualization


### Region
![download](https://user-images.githubusercontent.com/51442732/178659315-60e54458-fafe-4555-b012-99320e2548f9.png)

### Gender

![download (1)](https://user-images.githubusercontent.com/51442732/178659444-7a9f351f-2144-4fc0-9a1c-95668399b012.png)

### Number of males and females for each region
![download (2)](https://user-images.githubusercontent.com/51442732/178659497-26f77193-f5ca-4b7e-a79a-7b54722dc3c5.png)

### Family member with ASD history

![download (3)](https://user-images.githubusercontent.com/51442732/178659560-1a891aba-0514-4aec-b086-1a9728b5f60e.png)

### Age

![download (4)](https://user-images.githubusercontent.com/51442732/178659614-87d8a048-238c-4ca0-b9d6-f5e9d6022699.png)

## Dataset Preprocessing

### Numeric transformation

![Picture1](https://user-images.githubusercontent.com/51442732/178660786-35945901-cda3-4301-b434-a20e51eaeef9.png)

### Reducing the less essential features 

![sd](https://user-images.githubusercontent.com/51442732/178660924-221cbab0-5d78-41fc-ae4d-49c89d8f5698.png)

### Models Implementation

#### Machine learning algorithms
1- Support Vector Machine 
2- Naive Bayes
3- Logistic Regression 
4- K- Nearest Neighbour 

### Training and Testing   
The dataset has been split into train, validation, and test sets. Because the dataset
is imbalanced, we used stratified proportional allocation and random shuffling to
split the data. Figure 10 shows that 80% of the data is allocated to the train set
and the remaining 20% to the test Set. We used stratified CV to select a validation
set arbitrarily during the construction of the classifier.

### Features Selection 

#### Features selection methods
 Chi-squared  and  Mutual Information 
 
 #### Seleced Features
 A9,A8,A6,A4,A3,A2
 
 ### Hyperparameter Optimization
we use grid-search tuning technique 

 ### Results
 #### Performance of the four classifiers before feature selection
and hyperparameter optimization
<img width="1359" alt="Picture3" src="https://user-images.githubusercontent.com/51442732/178662767-d0e9351b-aa4d-4bf2-92f1-7fd80f390446.png">

#### 
Performance of the four classifiers after feature selection
and hyperparameter optimization

<img width="1324" alt="Picture4" src="https://user-images.githubusercontent.com/51442732/178662893-e610ca44-9582-4638-9a0e-ad224766c9e7.png">
 
 ### Learning Curves 
 

![download (8)](https://user-images.githubusercontent.com/51442732/178663134-7b1f5526-91e4-4451-8429-9582bfc623ab.png)
![download (5)](https://user-images.githubusercontent.com/51442732/178663141-c74c78c1-5033-4776-9684-dfb39a2fbe87.png)
![download (6)](https://user-images.githubusercontent.com/51442732/178663143-75042fed-b5ea-4870-aca6-4e193bf14a2c.png)
![download (7)](https://user-images.githubusercontent.com/51442732/178663144-16b4aaa7-f7cb-4a82-a521-a332606b52e4.png)

