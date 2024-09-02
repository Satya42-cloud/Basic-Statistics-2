# Basic-Statistics-2

## Confidence Interval Estimation for Print-Head Durability
### Background
In quality control, particularly for high-value components, destructive testing methods are employed to ensure adherence to quality standards. Due to the inherent costliness of these tests, only a small sample can be evaluated. This project focuses on estimating the mean durability of print-heads—measured in millions of characters printed before failure—by constructing confidence intervals based on a limited dataset.

### Scenario
A manufacturer of print-heads for personal computers has conducted a study to estimate the mean durability of their products. Due to the destructive nature of the testing process, a sample of 15 print-heads was tested, and their durability was recorded as follows (in millions of characters): 1.13, 1.55, 1.43, 0.92, 1.25, 1.36, 1.32, 0.85, 1.07, 1.48, 1.20, 1.33, 1.18, 1.22, 1.29.

### a. Construction of 99% Confidence Interval Using Sample Standard Deviation
#### Objective: To construct a 99% confidence interval for the mean durability based on the sample standard deviation.
#### Methodology:
1. Compute Sample Statistics: Calculate the sample mean and sample standard deviation from the dataset.
2. Select the t-Distribution: Given the small sample size (n = 15) and the unknown population standard deviation, the t-distribution is used for a more accurate estimation 
   of the confidence interval.
3. Interval Calculation: Utilize the t-distribution to compute the confidence interval, incorporating the sample standard deviation and the t-value for a 99% confidence 
   level.
4. Justification: The t-distribution is appropriate due to the small sample size and the necessity of estimating the population standard deviation from the sample.
### b. Construction of 99% Confidence Interval Using Known Population Standard Deviation
#### Objective: To construct a 99% confidence interval for the mean durability assuming a known population standard deviation.
#### Methodology:
1. Compute Sample Mean: Derive the sample mean from the recorded data.
2.Apply Population Standard Deviation: Use the known population standard deviation of 0.2 million characters in the interval calculation.
3. Use the z-Distribution: Since the population standard deviation is known and the sample size is considered sufficiently large for this context, the z-distribution is 
   employed for constructing the confidence interval.
### Conclusion
This analysis provides robust estimates of the mean print-head durability through the construction of 99% confidence intervals. By comparing intervals derived from sample-based and population-based approaches, the analysis underscores the importance of choosing the appropriate statistical method based on available data and known parameters.
