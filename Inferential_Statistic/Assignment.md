TO: Head Trainer, U.S. bicycle team

FROM:  Data Analyst

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

We will formulate their formal definition below in Hypothesis 1 & 2. Let the mean of dark chocolate be mu2 and white chocolate be mu1 while mu0 be without chocolate

#### Hypothesis 1
First we will set it for baseline versus any form of chocolate. For simplicity sake, we will make two comparison, first the white, then the black 

      Null Hypothesis: The consumption of chocolate have no effect on the cyclists and they travel equal distances.
                => H0:  mu0 - mu1/2 = 0

     Alternate Hypothesis: There is significant difference between the consumption of chocolates to sprint distance, 
                => H1:  mu0 - mu1/2 != 0 These are both 2 sided hypotheses

#### Hypothesis 2
The next set of hypothesis will be set for comparison between dark and white chocolates. 
     
      Null Hypothesis: There is no significant difference between consuming dark and white chocolates. 
              =>H0: mu2 - mu1 = 0 
      Alternate Hypothesis: There is significant difference between consuming dark and white chocolates.
              =>H1: mu2 - mu1 != 0 These are both 2 sided hypotheses.

## Assumptions
With hypothesis being set, we will check out the assumption for this study.
  * One assumption is to assume the data is normally distributed. Even though the sample size is rather small, we are to consider them normal
  * Another assumption is that there is no residual effect from chocolate consumption ie effect of consumption would not linger/spill over for any period after the test. Or simply the assumption are that the observations are not affected by previous test. 
  * Last assumption we are to assume that the observations are random. There is no given instructions to cyclist on which order (white or dark chocloate) should consume first.

## Test Observation
We have the results of the sprint distance (mean, standard deviation  and the corresponding p-value respectively) covered without having chocolates, after having white chocolates for a week and after consuming dark chocolate for a week and tabulated below

|    | Baseline | White Chocolate (WC) | Dark Chocolate (DC) | 
--- | --- | --- | --- |
Mean (m) | 1367 | 1419 | 1606 | 
Std dev (m) | 171 | 248 | 158 | 
p-value (compared to baseline) | --- | 0.319 | 0.001 | 

## Analysis of results
Information is given from the description.

For the 1st hypothesis we get the following results:
        
       mu2 - mu0 = 1606 - 1367 = 239 meters
       95% confidence interval: (165 m, 314 m)
       p-value for the above = 0.001

       m1 - mu0 = 1419 - 1367 = 52 meters 
       95% confidence interval: Not given
       p-value for the above = 0.319      

For the 2nd hypothesis, we get the following result,

        mu2 - mu1 = 1606 - 1419 = 187 meters
        95% confidence interval for dark chocolate vs white chocolate: (82 m, 292 m)
        p-value for the above = 0.003


## Making a Decision

### First Hypothesis
At the first glance, just by comparing the mean difference, we see that the results show that the cyclist consuming chocolate will almost always result in better performance than the baseline. This might be true for our sample and we will check our hypothesis and the confidence interval to see if results stand.

However, checking the confidence interval check, to see if our sample result is reasonable or not. At the 95% confidence interval, we get a range of reasonable values to be between 165 meters and 314 meters for dark and baseline. The difference between dark and baseline happens to be 239 meters which is within the confidence interval. The CI happens to be greater than zero even in the lower tail. There is no doubt that dark chocolate would enhance performance of athlete. At the same time, looking at hypothesis test, a p-value of 0.001 is obtained which implies that if we consider our Null hypothesis to be true, the values we got is 0.1% possible. That means we have sufficient proof to reject our Null hypothesis. 

While for the white, we could not really say for sure as the hypothesis test p-value is 0.319, meaning that there is 31.9% chance of the result occuring under the null hypothesis (ie there is no difference) which is more than the 5% limit that we have set for ourself. Moreover looking at the white chocolate result, the standard deviation is much larger compared to baseline standard deviation. The boost might be evidence in some athlete but could not be found in others, and might lead to decrease in performance. Hence we could not say with confidence that there is performance increase in consuming white chocolate.

### Second Hypothesis
We will now check for the second set of Hypotheses, to see the effect of each type of chocolate on the performance of the cyclists.

For our 2nd Hypothesis test, we see that the mean difference is 187m in favour of black chocolate. The p-value we get is 0.003 which is less than 0.05, our significance level.  This meant the experimental results is unlikely to be achieved under the null hypothesis. And since the value is way less than 0.05, we will reject the null hypothesis and conclude that there is significant difference between the dark chocolate versus white chocolate on cyclists. In addition, we can say that dark chocolate performs much better than white chocolate.

## Conclusion
From this, we can conclude the following:
  * There is significant difference between the performance of cyclists when they took dark chocolates versus baseline performance when they did not take chocolates. Dark chocolate gives better performance.
  * We are unable to say that white chocolates give better performance over baseline. The results were insufficient to tell us that we should believe in the alternative
  * In addition, consuming dark chocolate gives a greater performance boost than consuming white chocolates.

## Reference
  * R. K.; Brouner, J.; Spendiff, O. Journal of the International Society of Sports Nutrition. 2015 12:47
  * https://s4be.cochrane.org/blog/2020/09/07/crossover-trials-what-are-they-and-what-are-their-advantages-and-limitations/
