# Measures of Central Tendency
For summarizing and understanding data.
## Mean
The mean is the average of all the data points.
![image](https://github.com/user-attachments/assets/e6d4f0ec-ff8a-4d23-a48f-92abe07c6287)

## Median
The median is the middle value in an ordered data set.
1. Arrange the data in ascending or descending order.
2. If the number of data points is odd, the median is the middle value.
3. If the number of data points is even, the median is the average of the two middle values.
   ![image](https://github.com/user-attachments/assets/068f2a64-4332-417a-a661-1f6fee2334b7)

## Mode
The mode is the value that appears most frequently in a data set. The mode is higher bar in bar chart.
eg:
[5, 23, 6, 9, 5, 4, 9, 5]
mode = 5

## Percentile
A percentile indicates the value below which a given percentage of data falls.
For example, the 25th percentile (also called the first quartile, Q1) is the value below which 25% of the data lies.
[1,2,3,4,5,6,7,8,9,10] the 25th percentile is 3.

## Quartiles(Q1, Q2, Q3)
Quartiles divide the data into four equal parts:
1. Q1 (First Quartile): The median of the lower half of the data (25th percentile).
2. Q2 (Second Quartile): The median of the entire data set (50th percentile).
3. Q3 (Third Quartile): The median of the upper half of the data (75th percentile).

![image](https://github.com/user-attachments/assets/81d016d4-6f22-40e6-9bbf-83c7bda860e5)

1,2,3,4,5,6,7,8,9,10

Q1 = 3 
Q2 = 5.5
Q3 = 8

## Interquartile range
The IQR measures the spread of the middle 50% of the data.
Calculation: IQR = Q3 - Q1
Eg: 
For the data set above, IQR = 8 - 3 = 5.

## Min
The minimum (min) is the smallest value in a data set.
Eg:
2,4,6,8, the min is 2.
## Max
The maximum (max) is the largest value in a data set.
eg:
2,4,6,8, the max is 8.

# Finding Outliers using Quartiles
- Quartiles(Q1, Q2, Q3)
- Interquartile range
- Lower Fence: Q1 - (1.5 × IQR)
- Upper Fence: Q3 + (1.5 × IQR)

# Measures of Dispersion
## Range
The range is the difference between the maximum and minimum values in a data set.
Formula:
Range=Max−Min

Example: For the data set 
2,4,6,8, the range is 
8−2=6.

## Variance
Variance measures the average squared deviation of each data point from the mean.
![image](https://github.com/user-attachments/assets/01ced9e1-d301-4e42-ac99-34c7e6b21bc2)
eg:
![image](https://github.com/user-attachments/assets/0a6aa1ae-bfc6-4561-8549-06122ef46bef)

## Standard Deviation
The standard deviation is the square root of the variance. It measures the average distance of data points from the mean.
![image](https://github.com/user-attachments/assets/bd84d9f8-76f8-4ee2-a87d-bf68652e32b8)
eg:
![image](https://github.com/user-attachments/assets/b511c623-7b23-463a-a978-a2effb4a14a0)

## Z-score (used for standardization)
It is used to standardize data, making it easier to compare values from different data sets or distributions.
1. It indicates the relative position of a data point within a data set.
2. A positive z-score means the data point is above the mean.
3. A negative z-score means the data point is below the mean.
4. A z-score of 0 means the data point is equal to the mean.

![image](https://github.com/user-attachments/assets/f3455adc-2141-4e25-8a8f-86f6c8308324)

## Confidence Interval (CI)


### Qs:
![image](https://github.com/user-attachments/assets/0b672535-6533-4cca-b79a-28b06c1607b8)

# Correlation coefficient (-1 to 1)
The correlation coefficient (often denoted as r) is a statistical measure that describes the strength and direction of the linear relationship between two variables. It ranges from -1 to 1, where:

r=1: Perfect positive linear relationship.

r=−1: Perfect negative linear relationship.

r=0: No linear relationship.
![image](https://github.com/user-attachments/assets/222051f6-7328-451f-8f82-88cffc7b4323)
![image](https://github.com/user-attachments/assets/81261208-95c5-4655-b7cc-c0e7434022d6)


## pearson correlation coefficient
Measures the strength and direction of the linear relationship between two continuous variables.
![image](https://github.com/user-attachments/assets/8b2344bc-21a2-46d2-9090-6a1d1366119e)

## sphearman's rank correlation
Measures the strength and direction of the monotonic relationship (whether linear or not) between two variables. It is based on the ranks of the data rather than the raw data.
![image](https://github.com/user-attachments/assets/87b55e33-8e9b-4bf3-9fdf-6931b72c5123)

![image](https://github.com/user-attachments/assets/65bcc2c0-a00c-4b4c-a1b7-0c9ef270b0ec)

# Scatter plot (Bivariate analysis)
A scatter plot is a graphical representation of the relationship between two variables in bivariate analysis. It is one of the most effective tools for visualizing the correlation, trends, and patterns between two continuous variables. Each point on the scatter plot represents an observation with coordinates (x,y), where x is the value of the first variable, and y is the value of the second variable.

![image](https://github.com/user-attachments/assets/2ca4631a-84a0-46cd-890a-555952b0917d)

![image](https://github.com/user-attachments/assets/b6c90ecb-9623-45c3-97d3-e08ec258e73d)

# Histograms
A histogram is a graphical representation of the distribution of a dataset. It is a type of bar chart that groups data into bins (intervals) and shows the frequency (or count) of data points within each bin. Histograms are commonly used in statistics to visualize the shape, spread, and central tendency of continuous data.

![image](https://github.com/user-attachments/assets/e772eb96-4437-4caf-82cb-44b94e3ef7fb)

# Probability density function and cumulative density function
1. PDF gives the probability of a specific value occurring (in terms of an infinitesimally small range around that value).
2. CDF gives the probability that the random variable is less than or equal to a certain value.
3. PDF is used to describe the relative likelihood of different outcomes.
4. CDF is used to describe the cumulative probability up to a certain point.
   
# Box plot
A box plot (also known as a box-and-whisker plot) is a graphical representation of the distribution of a dataset. It shows the median, quartiles, and outliers, giving a good summary of the data spread.
![image](https://github.com/user-attachments/assets/11fe1c5e-fe39-4927-aac4-285ce8460b5c)

  
