# Inferential Statistics
## Why do we need Inferential Statistics?
Correlation Vs. Causation
Controlled Experiment
Examples
A/B Testing
Medical Trials
## Population
## Sample
## Why do we need sampling ?
### Sampling bias
### Types of sampling
### Sampling Distribution
Probability distribution
Area under the curve
Gaussian distribution and Normal distribution
Sampling Distribution of the Mean
Central Limit Theorem (CLT)
Online stats visualization
If you take many samples from a population and calculate their averages, those averages will form a bell-shaped curve (normal distribution), even if the original data isn’t bell-shaped. This is useful because it lets us make predictions about the population.
## Hypothesis Testing
### Null Hypothesis
### Alternate Hypothesis
### Significance Level (α)
Typically used values are 0.05 (e.g. e-commerce ) and 0.01 (e.g in fileds like medicine)
P-value
# Major Statistical Tests
## Z-test
A Z-test is used to compare means when the sample size is large n>30 and the population variance is known. It follows the standard normal distribution (Z-distribution). The steps to do this as follows

1. State the Null Hypothesis
2. State the Alternate Hypothesis
3. Choose Your Significance level (α)
4. Calculate Your Z-test Statistic
![image](https://github.com/user-attachments/assets/7ed76a3b-40e3-4266-afa3-b20728f26905)

x¯= sample mean
μ = population mean
σ= population standard deviation
n= sample size

5. Find p-value using Z-Table and Z-test statistic computed
6. if p-value < α, then we fail to reject null Hypothesis
7. There are one-tailed and two-tailed tests
## Z-test Practice Problem
A particular companies chocolate bars are supposed to have an average weight of 50 grams according to the maufacturer. We want to test if a sample of chocolate bars deviates significantly from this weight. Data: 50.8, 49.5, 50.2, 51, 49.7, 50.3, 49.8, 50.5, 49.6, 50.1 Population standard deviation: 1.5 grams (assumed based on production tolerance)

## T-test
We need T-test because population standard deviation σ is not always available
Here we will be computing T-test statistic (based on the problem statement and type of t-test)
Type of T-test	Null Hypothesis	Alternate Hypothesis	Degrees of Freedom
One Sample t-test	The sample mean is equal to the reference value	The sample mean is not equal to the reference value	
![image](https://github.com/user-attachments/assets/9acf8c18-5ce2-4cf9-aee5-b1ed9b1b17af)

## One Sample T-test
Compares the sample mean to a known population mean
The steps are as follows

1. State the Null Hypothesis
2. State the Alternate Hypothesis
3. Choose Your Significance level (α)
4. Calculate Your T-test Statistic
![image](https://github.com/user-attachments/assets/9c04f13c-b749-49ba-b240-3c83d868ec5b)


x¯= sample mean
μ= population mean
s= sample standard deviation

![image](https://github.com/user-attachments/assets/38896400-f71b-441a-869c-6284bb46801c)



n= sample size
5. Find the critical t-value from T-Table using significance (α) level
6. if t-statistic < critical t-value, we fail to reject Null Hypothesis

## Independent Sample T-test
Compares means of two independent groups
The steps are as follows
1. State the Null Hypothesis
2. State the Alternate Hypothesis
3. Choose Your Significance level (α)
4. Calculate Your T-test Statistic

![image](https://github.com/user-attachments/assets/01e0eaa9-9365-4235-8475-ed487f6268d9)

![image](https://github.com/user-attachments/assets/3641f086-29ee-410f-85d8-eef123fef045)


5. Find the critical t-value from T-Table using significance (α) level
6. if t-statistic < critical t-value, we fail to reject Null Hypothesis

### Sample Data

Brand A: 49.5, 50.1, 49.8,50.3, 50
Brand B: 50.4, 49.9, 50.6, 50.2, 50.1
Paired Sample T-test
Compares means from the same group at different times (before/after)
F-Distribution
