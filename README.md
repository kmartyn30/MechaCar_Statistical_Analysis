# MechaCar_Statistical_Analysis (R language ggplot and statistics)

**Deliverable 1:**

## Linear regression to Predict MPG
    The linear regression model is on a dataset containing 50 mpg test results for fifty MechaCars. The MechaCar prototypes were based on the idea 
    performance of each vehicle. As you can see the dataset first was set to pass the first six variables in the dataset.
  
    Linear regression predict MPG                                 
   ![image](https://user-images.githubusercontent.com/107796290/200182337-524dc0d1-bf82-4bb9-83e5-620c13e943d4.png)
   
  
  
  
  In this analysis I implemented the function of lm() to create the data frame. This then implicated the variables and correlation to the coefficients 
  with r-values as multiple R-squared" 0.7085 which is utilized as a powereful tool to determine the quantified relations between the variables and 
  predicatively can be utilized as a influencial decision making within the process based on the meanfulness to the model.
  The R-squared is 0.7085 which is 71% approzimately of the variables of the dependent variables which is moderate strength correlation. The p-value of  
  the linear regression model is 2.767e-06, (2.76 x 10 to the 6th power) which is least than the assused 0.05%. Therefore it results a slope of the linear 
   model not being zero, in turn it is suffiencent to reject the null hypythosis. The adjusted R-squared as 0.6524 which means there is a likelihood that 
   the probablity that the date points will fit the linear model. 
   
   As you can see in the data for the multiple linear regression model for predictive modeling tool to measure p-value as 2.767e-06 so that this will be a 
  fail to reject the null hypothesis which quantifies suffiencent level to reject the null hypothesis of the paired t-test. This implicates there is 
  limited to no distribution difference across the mpg dataset. A well designed linear regression model should approximate the two data points with a  
  strong interrelationship within the two or more data variables points. 
  
  The Slope of the linear model as you can see is not considered to be 0 due to interrelated performance. 
   
  In the linear model,  Pr(>|t|) value that each coefficent contribution to a random amount of variance to the model. The mpg Pr(>|t|) implicates that the 
  model is based on a random amounts within the dataset. 
   
                                                 
                                                 *********************************

 ##Deliverable 2:

 Summary Statistics on Suspension Coils:
 
 Total summary of suspension coils calcluating the mean, mode, variance and standard deviation. The total summary data for suspension PSI mean was 1,498.78. the median was 1500, the varience was 62.29356 and the standard deviation was 7.892627. Now lets compare to the three manufacturing lots.
 

Summary 
![image](https://user-images.githubusercontent.com/107796290/200188693-061ce89d-146e-4944-8604-759b101eb1b1.png)

  As you can see within the total summary the 1 manufacturing lot mean was 1500 and meadian was the same 1500. In this situation the mean and median are 
Lot SUMMARY   
![image](https://user-images.githubusercontent.com/107796290/200187982-2b70c671-1bc2-4b16-812f-a8273c0841fe.png)
                                            
 The MechaCar suspension coils imposed that the varience must not out perform the 100 pounds per square inch for the suspension coils. The prevailing 
manufacturing data suggests that this designs specification based on the three manufacturing lots. This was determined by the data in the set in the table. 
 The same value, so there is minimal impact to downstream analysis reflecting no skew. The summary mean was in a close range. while the median was exactly 
 
 
 on target. The variance for lot 1 was 0.9795918 which was dynamically in a different level from the summary. The standard deviation was 0.9897433 again 
 lowed than the trending summary. Manufacturing lot 2 mean consisted of 1,500.20 similarly to the summary and lot 1. Lot 2 mean was exactly the same as
lot 1 1,500.0 however the varience was 7.4693878 slightly highter than manufacture lot 1 and low than the summary.  The standard deviation was 2.7330181 
which reflected highter level than lot 1 however lower than the summary. 
  
 Lastly. Manufacturing lot 3 mean was 1,496.14 close to that of the summary and lot 1 and 2. The median was 1,498.50 similarly the same of 1500.0 however                                                                                                       
  this may implicate skewed data distribution. The varience was 170.2861224which was very high comparable to the two manufacturing datasets and the summary. 
                                                   
                                                      
                                              **********************************



##Deliverable 3
##T-Tests on Suspension Coils

Manufacturing Lot 1:
![image](https://user-images.githubusercontent.com/107796290/200192977-88b823a9-a34c-460c-8455-aea2e88e3a6f.png)
  Secondly, identfy and assess the truth of the null hypostesis as a statistical analysis. 3. Compute the p-value or probability value. 4. Compare the significant level and the p-value. 5. Determine the null hypothesis and generate a conclusiont of reject or fail to reject. 

  The overall interpertation of the t-test result findings were for the first lot data: suspension data, Manufacturing Lot 1 
= 0, df = 49, p-value = 1 
alternative hypothesis: true mean is not equal to 1500 meaning the observations and measurements used in our statistical test should have been attributed .  
to random chance, but we attributed them to something else. A 95 percent confidence interval: 1499.719 1500.281 is shown. The sample estimates: mean of 
1500

![2022-11-06 15 32 26](https://user-images.githubusercontent.com/107796290/200193665-c42682ca-1c53-421b-9507-98f377f6b805.png)

The Second overall interperation of the t-test results were data for suspension data,for Manufacturing Lot 2
t = 0.51745, df = 49, probabilty value = 0.6072 alternative hypothesis: true mean is not equal to 1500
95 percent confidence interval:1499.423 to 1500.977 this shows that there is a slight left skewness or negative skewed within the dataset so that it implicated there are negative numbers in the dataset. Sample estimates: mean of x 1500.2.  

![image](https://user-images.githubusercontent.com/107796290/200194858-bfb0d56b-9af2-42f3-8d1d-fd19a5c40416.png)

The third t-test results for data suspension data for Manufacturing Lot 3 t = -2.0916, df = 49, probability value is 0.04168 which is less than 0.05 as per 
per Shapiro-Wilk test for p-value.  The t-test results were alternative hypothesis, stated true mean is not equal to 1500. This mean that if the dataset 
 smaller or the skewness is overall fewer than the distribution more action is needed. As a result, 95 percent confidence interval:1492.431 1499.849. The 
 sample estimates is the mean of 1496.14.                                   
 
                                            *********************************************
**
## Deliverable 4
## Study Designs: MechaCar vs Competition
The purpose of the statistical analysis was designed to study comparing MechaCar to the Competition. In this study were to use metric(s) tests; the null 
hypothiss or alternative hypothesis; a statistical test for assessing the hypothesis including several reasons. Lastly, determine if the data requiresto 
run the statistical test. The hypothesis test  will show how the dataset in which there are five steps to the process. This is an overview of the process 
for the three lots statistical results and outcomes. 
  First the metric or metrics test the vechicle weight and the horse power of the car. The horse power is a point of pick up or speed of the car. 
  Secondly would be the null hypothesis or alternative hypothesis, of Ho : PH = 0.5 Ha: PH not equal 0.5
       
  ![image](https://user-images.githubusercontent.com/107796290/200202328-9302251a232-4a77-b1b5-c6c7c856278d.png)
  The results would implicate by random chance without influnces when null results is represented in the test. If fould insufficient then extensive
  staticical data testing must be continued. If the null hypothesis is true use the probability vlaue or p-value. 
  Thirdly, the statical test use to test the hypothesis with the probability value vs the significant level also referred to as alhpa. This design is to
  determine the importance on the dataset findings. When the significance level is 0.05 it is sufficient. However it can be small of using a marginal
  smaller dataset. 
        Next,the data need to run a statistical test, computing the p-value using statistical anaylsis, then compare to the p-value to the significant level. Lastly, generate conclusion by determining if fail to reject or reject the null hypothesis is in the tested dataset.  
  generate the null hypothesis, corresponding alternative and significant levels. 






