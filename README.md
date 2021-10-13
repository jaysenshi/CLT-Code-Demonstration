# The Central Limit Theorem
## Introduction
The central limit theorem is one of the most essential and powerful theorems in statistics, serving as the basis for all statistical inference. Approximations of the central limit are fundamental for most elementary statistical study including confidence intervals, regression, and logistical analysis, and hypothesis testing. These techniques have been applied over the years in business applications and empirical studies.

## Conditions
For the central limit theorem to hold, we must be evaluating the mean or the sum of a random sample that is substantially large. A random sample has two conditions.

&nbsp;&nbsp;&nbsp;&nbsp; 1. All variables in the sample must be independent of one another.      
&nbsp;&nbsp;&nbsp;&nbsp; 2. All variables in the sample must be identically distributed.        

## Results
![image](https://user-images.githubusercontent.com/63396651/137059587-cda3074c-e3fd-487f-aa28-ada426c68315.png)

The central limit theorem states that as the size of our random sample increases, the following properties will take hold:

### 1. 

&nbsp;&nbsp;&nbsp;&nbsp;-The expected value of the mean will approach the true population mean.  

&nbsp;&nbsp;&nbsp;&nbsp;-The expected value of the sum will approach the true population total.

### 2.

&nbsp;&nbsp;&nbsp;&nbsp;-The variance of the mean will approach the true population variance divided by the sample size.

&nbsp;&nbsp;&nbsp;&nbsp;*Thus the variance of the mean will decrease with increased sample size.*

&nbsp;&nbsp;&nbsp;&nbsp;-The variance of the sum will approach the product of the true population variance and its sample size.

&nbsp;&nbsp;&nbsp;&nbsp;*Thus the variance of the sum will increase with increased sample size.*

### 3. 

&nbsp;&nbsp;&nbsp;&nbsp;The distribution of the mean and the sum will approach being normal. (having a bell curve shape)

![image](https://user-images.githubusercontent.com/63396651/137059672-56001c2a-f847-4b63-9b35-2312683339b6.png)

*One interesting quality about the central limit theorem is how the distribution of the mean and sum of a random sample will be normal regardless of how far away the distributions of the random variables in the random sample were from being normal.* 

## Demonstration

In our coding demonstration, we will show how these three properties hold even when our random sample consists of random variables generated from distributions very different in nature from the normal distribution. These distributions include the Poisson, gamma, and exponential distribution. For each distribution, we will create a population, and generate random samples from that population. We will then create a sample of means from these samples. From there, we get the sample mean, sample variance, and distribution of the "sample of means".  We will then compare these results to the original population mean, variance, and distribution.
