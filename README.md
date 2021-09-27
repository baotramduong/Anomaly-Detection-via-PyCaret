# Anomaly Detect Via PyCaret

## Blog

[Medium Blog](https://baotramduong.medium.com/anomaly-detection-via-pycaret-53648caa099c)

## Introduction

Anomaly detection, or outlier analysis, is a step in the Data Science workflow to identify data point that deviates from what is standard, normal
or expected.

Anomaly or uncertainty is introduced into data because the process of collecting and processing data in the real world is imprecise and incomplete. When uncertainty is not handled properly, it will negatively affect data analysis by causing noise and distorting the overall quality of the analysis. On the other hand, when uncertainty is handled properly, it can be interpreted as unique information that gives decision boundaries and additional insights for the problem at hand.

Anomaly detection has been successfully implemented in various industries: email phishing, identity theft, document forgery, fraud detection, fault detection, intrusion detection, monitoring sensor readings in an aircraft, spotting potential risk or medical problems in health data, quality control and predictive maintenance etc. The anomaly detection market is expected to reach $4.45 Billion by 2022, at a Compound Annual Growth Rate (CAGR) of 16.4% (Market Research Firm, n.d.).

This project is for beginners like me, who are working and learning about data science and machine learning yet have little or no background in coding. It can be argued that Data scientists or analysts should spend more time experimenting rather than coding. PyCaret allows us to go from 0 to 100 in preparing our data to deploying our model in just a few lines of code.

## Data Source

PyCaret hosts the repository of open source datasets. We will be using one of these datasets, specifically the "anomaly" dataset, for our purpose of anomaly detection of this project.

## Exploratory Data Analysis

<img src = '../main/Data & Images/swarmplot.png'>

<img src = '../main/Data & Images/boxplot.png'>

<img src = '../main/Data & Images/pairplot.png'>

## Result

### Isolation Forest

<img src = '../main/Data & Images/iforest.png'>

### Local Outlier Factor

<img src = '../main/Data & Images/lof.png'>

### K-nearest Neighbors Detector

<img src = '../main/Data & Images/knn.png'>

### All Features Pairplot

<img src = '../main/Data & Images/knn_results.png'>

## Reference

Anomaly detection market. Market Research Firm. (n.d.). Retrieved September 27, 2021, from https://www.marketsandmarkets.com/Market-Reports/anomaly-detection-market-138133262.html.

Hawkins, D.M.: Identification of outliers, vol. 11. Springer, Berlin (1980).

Uddin, M. S. (n.d.). Machine learning — Anomaly detection via PyCaret [MOOC]. Coursera. https://www.coursera.org/projects/anomaly-detection
