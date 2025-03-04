# Inferential Statistics
Inferential statistics is a branch of statistics that involves using data from a sample to make inferences or draw conclusions about a larger population. Unlike descriptive statistics, which summarize and describe the features of a dataset, inferential statistics aim to make predictions or generalizations beyond the immediate data.
## Why do we need Inferential Statistics?
Correlation Vs. Causation
Controlled Experiment
Examples
A/B Testing
Medical Trials
## Population
The entire set of individuals or items of interest.
## Sample
A subset of the population that is used to represent the entire population.
## Why do we need sampling ?
### Sampling bias
Sampling bias occurs when some members of a population are systematically more likely to be selected in a sample than others, leading to a sample that is not representative of the entire population. This can distort the results of a study and lead to incorrect conclusions because the sample does not accurately reflect the population it is intended to represent.
### Types of sampling
1. Selection Bias:
Occurs when the sampling method systematically excludes or underrepresents certain groups.
Example: Conducting a survey on internet usage by only sampling people who have internet access, which excludes those without access.
2. Voluntary Response Bias:
Occurs when individuals self-select to participate in a study, often leading to overrepresentation of individuals with strong opinions.
Example: Online polls where only people with strong feelings about the topic choose to respond.
3. Non-Response Bias:
Occurs when individuals who do not respond to a survey or study differ significantly from those who do.
Example: A survey on job satisfaction where unhappy employees are less likely to respond, skewing the results.
4. Convenience Sampling Bias:
Occurs when samples are taken from a group that is conveniently accessible, rather than being randomly selected.
Example: Surveying only students in a university campus to understand the opinions of the general population.
5. Time Interval Bias:
Occurs when the time period during which the sample is collected influences the results.
Example: Conducting a survey on consumer spending habits immediately after a holiday season, which may not reflect typical spending patterns.
6. Survivorship Bias:
Occurs when only the "survivors" or existing members of a population are considered, ignoring those that have dropped out or failed.
Example: Analyzing the success of companies without considering those that have gone bankrupt.

### Sampling Distribution
1. Probability distribution
2. Area under the curve
3. Gaussian distribution and Normal distribution
4. Sampling Distribution of the Mean
5. Central Limit Theorem (CLT)
Online stats visualization
If you take many samples from a population and calculate their averages, those averages will form a bell-shaped curve (normal distribution), even if the original data isn’t bell-shaped. This is useful because it lets us make predictions about the population.
## Hypothesis Testing
### Null Hypothesis
A statement that there is no effect or no difference, and it is the hypothesis that is tested.
### Alternate Hypothesis
A statement that there is an effect or a difference.
### Significance Level (α)
Typically used values are 0.05 (e.g. e-commerce ) and 0.01 (e.g in fileds like medicine)
### P-value
The probability of obtaining the observed results, or more extreme results, if the null hypothesis is true. A low p-value (typically < 0.05) indicates that the null hypothesis can be rejected.

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
![image](https://github.com/user-attachments/assets/8ed50ae9-92fc-45d9-a8e4-73a86529b510)

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

![image](https://github.com/user-attachments/assets/b5fe4e14-ad74-4a14-a0c6-0420eaac13fe)

### Sample Data

1. Brand A: 49.5, 50.1, 49.8,50.3, 50
2. Brand B: 50.4, 49.9, 50.6, 50.2, 50.1

![image](https://github.com/user-attachments/assets/0a33e37c-7824-458b-8d52-f3c97d48c6f4)

Paired Sample T-test
. Compares means from the same group at different times (before/after)

### F-Distribution
The F-Distribution is a probability distribution used primarily in variance analysis and 
comparing multiple group means.
Key Concepts
• Definition:
– The ratio of two independent chi-squared variables divided by their degrees 
of freedom.
– Formula:
![image](https://github.com/user-attachments/assets/5082bec1-77ee-4153-b812-fd9b7d1b0f18)
Where:
![image](https://github.com/user-attachments/assets/001383fe-8837-4e2e-b574-645cf10a9b14)

• Properties:
– Non-negative values (F≥ 0).
– Skewed distribution, becoming less skewed as sample size increases.
