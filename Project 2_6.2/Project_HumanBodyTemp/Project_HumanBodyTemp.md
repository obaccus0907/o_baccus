Question1: 

It's clear to see from the graphical display that the human body temperature data closely follows a normal distribution.
Using scipy to test for normality, we see a fairly large p-value of 0.3 and are therefore more likely to fail to reject the null hypothesis that the distribution follows a normal distribution. 

Question2: 

There are 129 observations in the data, sample size is not very large. 
Using graphical analysis, the scatter plot shows there is little to no correlation between temperature and heart rate. 
The swarm plot shows that males are more likely to have lower heart rates (70-75 bbm) compared to females. Moreover, the data also shows that women are more likely to have higher body temperatures compared to men. 

Question3:

To conduct this analysis we sampled 50 people from the population. After trying bootstrap hypothesis testing, we see a low p value and can therefore reject the null hypothesis that the sampled mean is less than or equal to the observed mean temperature. 
We use a one sample test here because we are comparing one sample mean to a null hypothesis value. 
Using FST, we observe an extremely small p-value and can therefore reject the null hypothesis that the expected value of a sample of independent observations is equal to the given population mean. 
In order to be able to use the z score statistics, we would need to know the values of the mean as well as the standard deviation of the population. A z statistic is more commonly used in samples with many observations, so in this case, given we calculate the standard deviation, we should use the z statistic. 
Using the z statistic, I want to calculate whether the sample mean and observed mean temperatures (98.6) are equal. After calculating the z statistic, we can see that the z score is -4.05 and the corresponding p-value is almost 0.7 and we are more likely to  fail to reject the null hypothesis that the sample mean and observed mean are equal. 

Question4: 

After drawing a sample size of 10 from the data I notice that the p value is higher in the t statistic case, which means we are less lilely to reject the null hypothesis that the expected value of a sample of independent observations is equal to the given population mean. The z score associated p value was lower than when we used a sample of 50, and therefore we are more likely to reject the null hypothesis that the sample mean and observed mean are equal. It would seem that the smaller the sample, the more appropriate it is to use a t statistic. The z statistic gave us the same conclusion with a sample of 50, and 10, which is concerning for our analysis. 

Question5:

Based on the confidence interval (95%) and margin of error of the BS replicates, we see that a temperature below 118 and higher than 172 is considered abnormal, outside 95% of data, note that this is a translated mean, whereas using the t-test, we see that temperatures below 96.8 and higher than 99.6 are considered abnormal.

Question6:

In order to compare whether there was a significant difference between the female and male temperatures, I performed a t-test of 2 sample means with the null hypothesis that the sample means of both polulations are equal. The p value produced as a result of this analysis is 0.05 which is fairly small, and we are therefore more likely to reject the null hypothesis that the sample means of both populations are equal. 


