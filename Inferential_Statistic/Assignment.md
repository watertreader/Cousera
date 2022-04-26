TO: Head Trainer, U.S. bicycle team

FROM: Wong Chee Howe, Data Analyst

DATE: Apr 14, 2022

SUBJECT: Study and Analysis on Chocolate Consumption Effect on Cyclist Performance


## Introduction
  The study about the chocolate consumption effects (dark chocolate "Dove" and white chocolate "MilkyBar") on cyclists during cycling. The particular parameter we are interested in is the cyclist all-out sprint performance. From 9 male cyclists, study was conducted in 2 parts
  * Part 1 Dark chocolate consumption for a week
  * Part 2 While chocolate consumption for subsequent week

The result is being collected and share as below, "Test Observation"

As the test is similar to a before-after test on same group of people, it can be taken that we have a population paired data and is done in cross over design test.
  
 #### Benefits of CrossOver Design
   The benfits of crossover design test is that one need lesser study participants, especially in special categories. For this study, it is quite difficult to find that many professional cyclist to particpate (would at least require twice the participants number for normal test). Study participants server as their own control as the intervention is measured on the same group of people
   

## Defining Hypothesis
There is two hypothesis being tested out here and of interest to people
  1. Whether there is any benefits from consuming chocolates (both black and white) in cycling
  2. Whether there is a difference between choosing white chocolates over black chocolates and vice versa

We will formulate their formal definition below in Hypothesis 1 & 2

#### Hypothesis 1
First we will set it for baseline versus any form of chocolate. 

      Null Hypothesis: The consumption of chocolate have no effect on the cyclists and they travel equal distances.
                => H0: dark chocolate - white chocolate = 0

     Alternate Hypothesis: There is significant difference between the consumption of chocolates to sprint distance, 
                => H1: dark chocolate - white chocolate != 0

#### Hypothesis 2
The next set of hypothesis will be set for comparison between dark and white chocolates. Let the mean of dark chocolate be mu1 and white chocolate be mu2
     
      Null Hypothesis: There is no significant difference between consuming dark and white chocolates. 
              =>H0: mu1 - mu2 = 0 
      Alternate Hypothesis: There is significant difference between consuming dark and white chocolates.
              =>H1: mu1 - mu2 != 0 These are both 2 sided hypotheses.

## Assumptions
With hypothesis being set, we will check out the assumption for this study.
  * One assumption is to assume the data is normally distributed. Even though the sample size is rather small, we are to consider them normal
  * Another assumption is that there is no residual effect from chocolate consumption ie effect of consumption would not linger/spill over for any period after the test. Or simply the assumption are that the observations are independent from previous test. 
  * Last assumption we are to assume that the observations are random. There is no given instructions to cyclist on which order (white or dark chocloate), they should consume first

## Test Observation
 | #1 | #2 | #3 | #4 | #5 | #6 | #7 | #8 | #9 | #10 | #11
--- | --- | --- | --- |--- |--- |--- |--- |--- |--- |--- |---
Mean (m) | #1 | #2 | #3 | #4 | #5 | #6 | #7 | #8 | #9 | #10 | #11
--- | --- | --- | --- |--- |--- |--- |--- |--- |--- |--- |---
Std dev (m) | 301 | 283 | 290 | 286 | 289 | 285 | 287 | 287 | 272 | 276 | 269
--- | --- | --- | --- |--- |--- |--- |--- |--- |--- |--- |---
p-value (compared to baseline) | 301 | 283 | 290 | 286 | 289 | 285 | 287 | 287 | 272 | 276 | 269

## Analysis of results
We already have the results of the distance covered without having chocolates, after having white chocolates for a week and after consuming dark chocolate for a week. We have the mean, and standard deviation for all the three along with the corresponding p-value of white and dark chocolate compared with the baseline.
From the data, we get the following results:

mu1 - mu_baseline = 1606 - 1367 = 239 meters
95% confidence interval of dark chocolate: (165 m, 314 m)
p-value for the above = 0.001
m2 - mu_baseline = 1419 - 1367 = 52 meters The difference in mean (mu1 - mu2) = 1606 - 1419 = 187 meters
95% confidence interval for dark chocolate vs white chocolate: (82 m, 292 m)
p-value for the above = 0.003
where mu1 = mean distance dark chocolate, mu2 = mean distance white chocolate, mu_baseline = baseline mean distance.
We will consider our significance level to be 0.05.

## Making a Decision
We see, from our analysis of the results that dark chocolate almost always performs better than white chocolate and the baseline results. This might be only for our sample and so, we will check our hypothesis and the confidence interval to see if our result is useful or not.

We will check for the first set of hypotheses, to see the difference in performance of cyclists before and after having chocolates, i.e. H0_1 and Ha_1.

From our sample we see that the difference between having either chocolate and the baseline performance is positive, implying that for this sample people performed better after having chocolates.

We will first do the confidence interval check to see if our sample result is reasonable or not. At the 95% confidence interval, we get a range of reasonable values to be between 165 meters and 314 meters. Our value happens to be 239 meters which is inside the confidence interval. So, it is not a surprising value.
For the hypothesis test, we see that we get a p-value of 0.001 which implies that if we consider our Null hypothesis to be true, the values we got is 0.1% possible. That means we have sufficient proof to reject our Null hypothesis which states that there is no significant difference between the performance of participants before and after taking any form of chocolate. This implies that there is a significant difference between consuming and not consuming chocolates when it comes to cycling. Since the difference is positive, we can say that having chocolates has a positive effect on performance.
We will now check for the second set of Hypotheses, to see the effect of each type of chocolate on the performance of the cyclists, i.e. H0_2, Ha_2.

We see that the difference between consuming dark chocolate and white chocolate on the distance cycled is over 187 meters in favor of dark chocolate. So, from our sample we see that dark chocolate makes the cyclists perform better.

To confirm this, we will check the confidence interval and see if the value we got was reasonable or not. We see that the confidence interval is (82 meters, 292 meters). 187 meters lies inside the confidence interval and so our result is reasonable. In addition, since both values in the confidence interval is positive, we can also conclude with 95% confidence that dark chocolate makes cyclists perform better than those who take white chocolate.
For our Hypothesis test, we see that the p-value we get is 0.003 which is less than 0.05, our significance level. So, from this, we see that if our Null hypothesis was true, we would get the value of 187 meters only 0.003% of the time. This makes our null hypothesis look ridiculous. And since the value is way less than 0.05, we will reject the null hypothesis and conclude that there is significant difference between the effect of dark chocolate versus white chocolate on cyclists. In addition, we can say that dark chocolate performs much better than white chocolate.

## Conclusion
From this, we can conclude the following:
  * There is significant difference between the performance of cyclists when they took chocolates versus their performance when they did not take chocolates. Chocolates seem to have a positive effect on their performance.
  *  In addition, consuming dark chocolate gives a greater performance boost than consuming white chocolates.

## Reference
  * R. K.; Brouner, J.; Spendiff, O. Journal of the International Society of Sports Nutrition. 2015 12:47
  * https://s4be.cochrane.org/blog/2020/09/07/crossover-trials-what-are-they-and-what-are-their-advantages-and-limitations/
