# Customer Segmentation
<p style="color:red;">I am red</p>
## Table Of Contents
- Abstract
- Introduction
- Existing Model
- Proposed Method
- System Architecture
- Methodology
- Implementation
- Conclusion

## Abstract
Effective decisions are mandatory for any company to generate good
revenue In these days competition is huge and all companies are moving
forward with their own different strategies We should use data and take a
proper decision Every person is different from one another and we don’t know
what he/she buys or what their likes are But with the help of machine learning
technique one can sort out the data and can find the target group by
applying several algorithms to the dataset Without this, It will be very difficult
and no better techniques are available to find the group of people with similar
character and interests in a large dataset Here, The customer segmentation
using K Means clustering helps to group the data with same attributes which
exactly helps to business the best We are going to use elbow method to find
the number of clusters and at last we visualize the data


## Introduction
- Nowadays the competition is vast and lot of technologies came into
  account for effective growth and revenue generation For every business the
  most important component is data With the help of grouped or ungrouped
  data, we can perform some operations to find customer interests

- Customer Segmentation is useful to divide the large data from dataset into
  several groups based on their Gender, Age, Annual Income and Spending
  Score These groups are also known as clusters By this, we can get to know
  that which age group are purchasing more their gender type, their income
  and their spending scores And we can target that age group people the
  most
- Initially we are going to work upon the mall customer dataset Apply the K
  means clustering algorithm on the given dataset to us and we have to find
  the number of clusters first So, at lastly, we have to visualize the data One
  can easily find the potential group of data while observing that visualization
- The goal is to identify customer segments using the K Means Clustering The
  elbow method determines the optimal clusters
  
## Existing Model
The existing method is storing customer data through paperwork and
computer software (digital data) is increasing day by day At end of the day
they will analyze their data as how many things are sold or actual customer
count etc By analyzing the collected data they got to know who is beneficial
to their business and increase their sales It requires more time and more
paperwork Also it is not much effective solution to find the desired customers
data

## Proposed Model
To overcome the traditional method i e paper work and computerized digital
data this new method will play vital role As we collect a vast data day by day
which requires more paperwork and time to do As new technologies were
emerging in today’s world Machine Learning which is powerful innovation
which is used to predict the final outcome which has many algorithms So for
our problem statement we will use K Means Clustering which groups the data
into different clusters based on their similar characteristics And then we will
visualize the data

## System Architecture
- Initially we will see the dataset and then we will perform exploratory data
  analysis which deals with the missing data, duplicates values and null values
  And then we will deploy our algorithm k means clustering which is
  unsupervised learning in machine learning

  ![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)
  
- As in order to find the no of clusters we use elbow method where distance
  will be calculate through randomly chosen centres and repeat it until there is
  no change in cluster centres Thereafter we will analyse the data through
  data visualization Finally we will get the outcome.

## Methodology
- First of all we will import all the necessary libraries ( NumPy, Seaborn,
  Mathplotlib, Warnings).
- Then we will read dataset and analyze whether it contains any null values,
  missing values and duplicate values So we will fix them by dropping or fixing
  the value with their means, medians etc which is technically named as Data
  Preprocessing.
- We will deploy our model algorithm K Means Clustering, which divides the
  data into group of clusters based on similar characteristics To find number of
  clusters we will use elbow method.
- Finally, we will visualize our data using M atplot, which concludes the
  customers divided into groups who are similar to each other on their group.

## Implementation
- Importing Libraries

  ![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

- Overview Of Dataset. This Mall_Customer dataset contains 200 ro ws and 5 columns 
- 
