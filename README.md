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
