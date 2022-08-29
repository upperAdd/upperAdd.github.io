#  Portfolio

### A sample of my personal and work projects.

### Time Series Analysis  -  Electricity Wholesale prediction price
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/upperAdd/final-project)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
<p align="justify">A Time Series Analysis is used to predict the average energy bill for Winter 2022/2023. For this project, I used a Nordpool wholesale electricity price dataset from 2018 until the 6th of august 2022. According to Ofgem, wholesale prices are 40% of our energy bill. I split the dataset into 80/20 train and test data and used time series cross-validation for this project as we can’t use the grid search cross-validation. The reason for choosing this type is because time series data characteristic by the dependence of data observation are close in time. Using the standard K-fold cross-validation method would lead to an unreasonable correlation between training and testing instances, leading to poor estimation of generalising error. The other engineering features I used are lag features, and I chose 3 times the fold due to the amount of train data used.</p>
<img src="images/EC/outputpredictionXGB.png?raw=true"/> <img src="images/EC/code.png?raw=true"/><br>
<img src="images/EC/time series split.png?raw=true"/> <img src="images/EC/split train and test.png?raw=true"/>

---

### Machine Learning Supervised  -  Fake News
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/upperAdd/Fake-News-)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
<p align="justify">The spread of misinformation & hoax on social media platforms is a large problem. Authentication of the news posted online is subject to bias and excessive time-consuming. Machine learning solves this problem. I have used supervised random forest regression and AdaBoost classifier to detect which one is a hoax.</p>
<img src="images/FN/trustworthy.png?raw=true"/><br>
<img src="images/FN/bigrams.png?raw=true"/> <img src="images/FN/type.png?raw=true"/>

---
  
## Neural Networks  -  Churn Prediction
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/upperAdd/Fake-News-)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
<p align="justify"> This project aims to predict the percentage of customer churn in the bank. Churn is a terminology that is commonly used in business companies. Churn rate is the rate at which customers stop doing business with a company over a given period of time. It can also describe customers stopping or cancelling subscriptions. And the result of this is money loss for the company. I decided to use machine learning ANN (Artificial Neural Network) to predict this behaviour, so the company can create a strategy to minimise churn.</p>
<img src="images/CP/ANN.png?raw=true"/> <img src="images/CP/confusion matrix.png?raw=true"/><br>
<img src="images/CP/card.png?raw=true"/> <img src="images/CP/product.png?raw=true"/>

---


### Logistic Regression -  Titanic
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/upperAdd/Logistic-Regression-Assignment)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
<p align="justify">Titanic are the most popular case to study logistic regression. Likewise, the dataset for titanic we get from Kaggle. The aim of this assignment is to predict the survivor when it happens. For this logistic regression for feature engineering, we need to do cross-validation using GridSearchCV, and then after that, we split our data set by 70/30 train and test data. We also need to check the accuracy of our score. Besides logistic regression, we also use naïve Bayes to compare the value.</p>
<img src="images/LR/Lr.png?raw=true"/> <img src="images/LR/heatmap.png?raw=true"/><br>
<img src="images/LR/sex.png?raw=true"/> <img src="images/LR/embark.png?raw=true"/>



---

### Linear Regression -  JFK Flight Delay 
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/upperAdd/Linear-Regression-Assignment)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
<p align="justify">This project also used a dataset from Kaggle and the dataset from JFK Airport between Nov 2019 – Dec 2020. The aim of this assignment is to check what potential direct impact the cost of the flight. As we know, the taxiing process in airlines consumes 5-10% of total fuel consumption, and Total Fuel Consumption takes 30% of the Total Operation Cost of each aircraft. Therefore, we can conclude that efficiently taxiing can reduce the TOC. In this project, I am trying to see which airlines often delay departure from their scheduled departures and try to predict the delay coefficient from their actual departures by using Linear Regression.</p>
<img src="images/linear/graph.png?raw=true"/> <img src="images/linear/equation.png?raw=true"/><br>
<img src="images/linear/actual.png?raw=true"/> <img src="images/linear/dep.png?raw=true"/>

---

### Data Visualisation -  Earthquake
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/upperAdd/DV_assigment)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
<p align="justify">This project is my first assignment doing data preprocessing and data visualisation. We use the Earthquake dataset from Kaggle. The aim is to determine which location has the biggest magnitude and often occurs by doing exploratory data analysis after cleaning the dataset. We know which locations were under the “Ring of Fire” or just in the most seismic region from the EDA result.</p>
<img src="images/EQ/3 location.png?raw=true"/> <img src="images/EQ/scatterplot.png?raw=true"/><br>



---

### Python Game - Adventure Game
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/upperAdd/Adventure-Game-DA_week-2)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
<p align="justify">This project is my favourite assignment to learn python as a programming language. We need to create adventure games that make the reader try to go into several rooms and have some blockage on the way out. I created this game inspired by Alice in Wonderland, but the situation I changed into vacation into a tropical island where readers need to have a diving license or advanced swimming skills to enjoy the vacation.</p>
<center><video src="images/AD game/AD.mp4" width= 600px height=600px autoplay controls></video></center>

---

### Machine Learning Unsupervised  -  Clustering Countries
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/upperAdd/Machine-Learning-Unsupervised)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
<p align="justify">
  
</p>
<center><img src="images/png?raw=true"/></center>


---
<left> © 2022 Titi P.</left>
