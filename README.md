# MechaCar_Statistcal_Analysis
R-studio


                                                              **Module 16 Challenge**
                                                              
                                                              
                                                   
**Linear Regression to Predict MPG 
  
 ![Snip20230125_1](https://user-images.githubusercontent.com/112818881/214751062-c467ba32-9842-48db-8869-c3e2c62353f9.png)
 
 Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
      The two variables that stick out the most of have the highest possible chance to be able to get meaningful data from is the vehicle length and ground clearance. These two variables may have a causation relationship with mpg effects.This is shown in the picture and you can see from our linear analysis there is basis for us to delves deeper in these two variable to see how vehicle length and ground clearance actually is the direct cause that effects a vehicle mpg.
      
 Is the slope of the linear model considered to be zero? Why or why not?
      No our slope is not zero due to the results of our data analysis: Multiple R-squared:  0.7149 and p-value: 5.35e-11, so the reults is much smaller than our predicted amount.
      
Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
      No it is not the most effective way, but it is a good place to start to see basis of relationships with the variable we suspect have an effect on MPG and with the analysis we can start removing varible that we can see no effect at all.
      
**Summary Statistics on Suspension Coil

  The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
    
  ![Snip20230125_2](https://user-images.githubusercontent.com/112818881/214753791-3da56b00-9fd2-4e71-93b6-538803433587.png)
    
   I believe that the design does not because you can see large variance between each lots, which is shown in the picture. Please use the picture as a reference to see all the variance it would seem that lot one is the closes lot meet designs requirements.
    
**T-Test on Suspension Coils

  Lot1
      ![Snip20230125_3](https://user-images.githubusercontent.com/112818881/214754486-276e6854-3179-4a0d-a928-27f0f583d6e9.png)
      
  Lot2
      ![Snip20230125_4](https://user-images.githubusercontent.com/112818881/214754567-dc6e3ed0-8477-4d82-a270-23b1f6bcba17.png)
      
  Lot3 
      ![Snip20230125_5](https://user-images.githubusercontent.com/112818881/214754610-a9cfc166-c581-4fde-92fc-3453fb55fec5.png)
      
  From the picture the test simply says there is no true mean a becauase the p values because the value is not above our 0.05 and as a result of the data. We cannot reject the null hypothesis.


**Study Design:MechaCar VS. Competition

   Consumer will be very interested in city and highway mileage. The metric we would use MPG and how it varies from highway performance and city performance.
    - Null hypothesis would be any that would have nothing to do with MPG and has no effect on the outcome whether consumer will find that appealing and does our competitor have factors that interest the consumer.
    - Alternative hypothesis the consumer are showing that MPG is important to them.
I would use the two-tailed test to see if the data has equal ends. Data is necessary for statistical test because we need data to find a way to predict an outcome for our hypothesis with information we know.
  

        
    
    


    
