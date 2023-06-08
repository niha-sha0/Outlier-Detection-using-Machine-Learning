##### In this project we have used different techniques to detect and remove outlier from the data and compare the techniques to detect outlier which is better among all the techniques. 
##### It is observered that IQR and DBSCAN techniques are fast to detect and remove outliers.

### OUTLIER DETECTION USING MACHINE LEARNING
##### Outlier is an observation (data point) that behave differently from all other observations.
##### In other words, an outlier is an observation that lies an abnormal distance from other values in a random sample from a population.
##### For example, to predict the weight of a person from the height. In general, one with more height will also have more weight (linear positive trend), but what if rarely we have 3 - 4 people who have much less weight, but comparatively more height than the data will be treated as bad data or the outliers.

#### How to treat Outlier?
+ ###### Trimming
- ###### Capping
* ###### Missing Value (Less Used)    
+ ###### Discretization (Less Used)

#### How to detect Outlier?
+ ###### Normal Distribution
- ###### Skewed Distribution
* ###### Percentile Distribution

#### TECHNIQUES FOR OUTLIER DETECTION AND REMOVAL
+ ##### Z-score Method
- ##### IQR based Filtering
* ##### Percentile Method

### Z-SCORE METHOD
##### Z-Score is a highly efficient way of detecting and removing outliers, we cannot use it with every datatype. Which means that it can only work with the data which is completely or close to normally distributed.
##### This method is used for normally distributed data.
![image](https://github.com/niha-sha0/Outlier-Detection-using-Machine-Learning/assets/87136913/a315453d-6ec6-4a22-a240-ebe9d7643da4)

##### To find outlier - 
###### Upper Limit - µ + 3 * Standard Deviation
###### Lower Limit - µ - 3 * Standard Deviation

### IQR BASED FILTERING
##### This method is used when the distribution of data is skewed.
![image](https://github.com/niha-sha0/Outlier-Detection-using-Machine-Learning/assets/87136913/8b04dda3-2c68-4d42-86db-5bab17e7c5c5)
##### As we know that Z-Score is only used for columns that are normally distributed, but we have to find out the way where we can remove the bad data from left and right skewed distribution for that statistics introduced IQR. IQR will work with Skewed Data.

