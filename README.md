# Ex02-OUTLIER

You are given bhp.csv which contains property prices in the city of banglore, India. You need to examine price_per_sqft column and do following,

(1) Remove outliers using IQR 

(2) After removing outliers in step 1, you get a new dataframe.

(3) use zscore of 3 to remove outliers. This is quite similar to IQR and you will get exact same result

(4) for the data set height_weight.csv find the following

    (i) Using IQR detect weight outliers and print them

    (ii) Using IQR, detect height outliers and print them

# EXPLANATION
              An Outlier is an observation in a given dataset that lies far from the rest of the observations. That means an outlier is vastly larger or smaller than the remaining values in the set. An outlier is an observation of a data point that lies an abnormal distance from other values in a given population. (odd man out).Outliers badly affect mean and standard deviation of the dataset. These may statistically give erroneous results.Most machine learning algorithms do not work well in the presence of outlier. So it is desirable to detect and remove outliers.Outliers are highly useful in anomaly detection like fraud detection where the fraud transactions are very different from normal transactions.

# ALGORITHM
STEP 1: Read the given Data.

STEP 2: Get the information about the data.

STEP 3: Detect the Outliers using IQR method and Z score.

STEP 4: Remove the outliers.

STEP 5: Plot the datas using Box Plot.

# CODE
# (1) & (2) Examine price_per_sqft column and use IQR to remove outliers and create new dataframe.

![](/Outlier%201.png)

![](/Outlier%202.png)

# (3) Examine price_per_sqft column and use zscore of 3 to remove outliers.

![](/Outlier%203.png)

# (4)(i) For the data set height_weight.csv detect weight outliers using IQR method.

![](/Outlier%204.png)

![](/Outlier%205.png)

# (4)(ii) For the data set height_weight.csv detect height outliers using IQR method.

![](/Outlier%206.png)

# OUTPUT
# (1)(2) Examine price_per_sqft column and use IQR to remove outliers and create new dataframe.

Dataset.

![](/out%201.png)

Dataset Head.

![](/out%202.png)

Dataset Info.

![](/out%203.png)

Dataset Describe.

![](/out%204.png)

Null Values.

![](/out%205.png)

Dataset Shape.

![](/out%206.png)

Box plot of price_per_sqft column with outliers.

![](/out%207.png)

price_per_sqft - Dataset after removing outliers.

![](/out%208.png)

price_per_sqft - Shape of Dataset after removing outliers.

![](/out%209.png)

Box Plot of price_per_sqft column without outliers.

![](/out%2010.png)

# (3) Examine price_per_sqft column and use zscore of 3 to remove outliers.

Dataset after removal of outlier using z score.

![](/out%2011.png)

Dataset after removal of outlier using z score.

![](/out%2012.png)

price_per_sqft column after removing outliers.

![](/out%2013.png)

# (4) For the data set height_weight.csv detect weight and height outliers using IQR method.

Dataset.

![](/out%2014.png)

Dataset Head.

![](/out%2015.png)

Dataset Info.

![](/out%2016.png)

Dataset Describe.

![](/out%2017.png)

Null Values.

![](/out%2018.png)

Dataset Shape.

![](/out%2019.png)

Weight - With outliers.

![](/out%2020.png)

Weight - Dataset after removing Outliers using IQR method.

![](/out%2021.png)

Weight - Shape of Dataset after removing Outliers using IQR method.

![](/out%2022.png)

Weight - Without Outliers using IQR method.

![](/out%2023.png)

Height - With outliers.

![](/out%2024.png)

Height - Dataset after removing Outliers using IQR method.

![](/out%2025.png)

Height - Shape of Dataset after removing Outliers using IQR method.

![](/out%2026.png)

Height - Without Outliers using IQR method.

![](/out%2027.png)


# RESULT

The given datasets are read and outliers are detected and are removed using IQR and z-score methods.







