# MechaCar_Statistical_Analysis- R language ggplot and statistics
**Deliverable 1:**

## Linear regression to Predict MPG
    The linear regression model is on a dataset containing 50 mpg test results for fifty MechaCars. The MechaCar prototypes were bsed on the idea 
    performance of each vehicle. As you can see the dataset first was set to pass the first six variables in the dataset.
  
    Linear regression predict MPG                                 
   ![image](https://user-images.githubusercontent.com/107796290/200182337-524dc0d1-bf82-4bb9-83e5-620c13e943d4.png)
   
  
    In our analysis, We implemented the funciton of lm() to create the data frame. This then implicated the variables and correlation to the coefficients 
  with r-values as multiple R-squared" 0.7085 which is utilized as a powereful tool to determine the quantified realtion between the variables and 
  predicatively can be utilized as a influencial decision making within the prcess baed on the meanfulness to the model.
   
  The R-squared is 0.7085 which is 71% approzimately of the variables of the dependnet variables which is moderate strength correlation.  The p-value of our linear regression model is 2.767e-06, (2.76 x 10 to the 6th power) which is least than the assused 0.05%. Therefore it results a slope of the linear model not being zero, in turn it is suffiencent to reject the null hypythosis. The adjusted R-squared as 0.6524 which means there is a likelihood that the probablity that the date points will fit the linear model.  
    
    As you can see in the data for the multiple linear regression model for predictive modeling tool to measure p-value as 2.767e-06 so that this will be a fail to reject the null hypothesis which quantifies suffiencent level to reject the null hypothesis of the paired t-test. This implicates there is limited to no distribution difference across the mpg dataset. A well designed linear regression model should approximate the two data points with a strong interrelationship within the two or more data variables points. 
   
   The Slope of the linear model as you can see is not considered to be 0 due to interrelated performance. 
   
  In the linear model,  Pr(>|t|) value that each coefficent contribution to a random amount of variance to the model. The mpg Pr(>|t|) implicates that the random amounts. 
    
    
 The Liner model predict mpg of MechaCar prototypes can be see as 
    
                                                        *********************************

 ##Deliverable 2:

 Summary Statistics on Suspension Coils:
 
 Total summary of suspension coils calcluating the mean, mode, variance and standard deviation. The total summary data for suspension PSI mean was 1,498.78. the median was 1500, the varience was 62.29356 and the standard deviation was 7.892627. Now lets compare to the three manufacturing lots.
 

Summary 
![image](https://user-images.githubusercontent.com/107796290/200188693-061ce89d-146e-4944-8604-759b101eb1b1.png)

  As you can see within the total summary the 1 manufacturing lot mean was 1500 and meadian was the same 1500. In this situation the mean and median are the same value, so there is minimal impact to downstream analysis reflecting no skew. The summary mean was in a close range. while the median was exactly on target. The variance for lot 1 was 0.9795918 which was dynamically in a different level from the summary. The standard deviation was 0.9897433 again lowed than the trending summary. Manufacturing lot 2 mean consisted of 1,500.20 similarly to the summary and lot 1. Lot 2 mean was exactly the same as lot 1 1,500.0 however the varience was 7.4693878 slightly highter than manufacture lot 1 and low than the summary.  The standard deviation was 2.7330181 which reflected highter level than lot 1 however lower than the summary. 
 Lastly. Manufacturing lot 3 mean was 1,496.14 close to that of the summary and lot 1 and 2. The median was 1,498.50 similarly the same of 1500.0 however this may implicate skewed data distribution. The varience was 170.2861224which was very high comparable to the two manufacturing datasets and the summary. 
 
Lot SUMMARY   
![image](https://user-images.githubusercontent.com/107796290/200187982-2b70c671-1bc2-4b16-812f-a8273c0841fe.png)

                                              
 The MechaCar suspension coils imposed that the varience must not out perform the 100 pounds per square inch for the suspension coils. The prevailing manufacturing data suggests that this designs specification based on the three manufacturing lots. 

This was determined by ________


                                                        **********************************



Deliverable 3
T-Tests on Suspension Coils

Manufacturing Lot 1:
![image](https://user-images.githubusercontent.com/107796290/200192977-88b823a9-a34c-460c-8455-aea2e88e3a6f.png)

**
The hypothesis test  will show how the dataset in which there are five steps to the process. I will review the sets frist then projec the three lots statistical results and outcomes. First, gereate the null hypothesis, corressopnding alternative and significant levels. Secondly, identfy and assess the truth of the null hypostesis as a statistical analysis. 3. Compute the p-value. 4. Compare the significant level and the p-value. 5. Determine the null hypothesis and generate a conclusiont of reject or fail to reject. 

The overall interpertation of the t-test result findings were for the first lot data: suspension data, Manufacturing Lot 1
= 0, df = 49, p-value = 1
alternative hypothesis: true mean is not equal to 1500 meaning the observations and measurements used in our statistical test should have been attributed to random chance, but we attributed them to something else.
95 percent confidence interval: 1499.719 1500.281. The sample estimates: mean of x  1500 


![2022-11-06 15 32 26](https://user-images.githubusercontent.com/107796290/200193665-c42682ca-1c53-421b-9507-98f377f6b805.png)

The Second overall interperation of the t-test results were data:  subset(suspension_data, Manufacturing_Lot == "Lot2")$PSI
t = 0.51745, df = 49, p-value = 0.6072
alternative hypothesis: true mean is not equal to 1500
95 percent confidence interval:
 1499.423 1500.977
sample estimates:
mean of x 
   1500.2 
