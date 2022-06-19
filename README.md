# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![C1C75B45-ACEC-466F-812A-589347CC92C7](https://user-images.githubusercontent.com/101157423/174481892-2faadeef-a4c7-46a0-b202-54480cfbb06a.jpeg)

After running a linear regression model on the MPG dataset, several factors stood out as having non-random amounts of variance. Those can be seen in the image above as intercept, vehicle_length and ground_clearance. Depending on our dataset, a significant intercept could mean that the significant features (such as vehicle_length and ground_clearance) may need scaling or transforming to help improve the predictive power of the model. Alternatively, it may mean that there are other variables that can help explain the variability of our dependent variable that have not been included in our model. Depending on the dataset and desired performance of the model, you may want to change your independent variables and/or transform them and then re-evaluate your coefficients and significance. 

Although the multiple linear regression model is far better at predicting our current dataset than a single model, the lack of significant variables is evidence of overfitting.

## Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch.

![3995D0DA-7F3C-4199-A2F7-FFF668D794C9_4_5005_c](https://user-images.githubusercontent.com/101157423/174483253-8242b7be-50d7-45a2-82a0-0f20f00b4f11.jpeg)

![0999333A-B07E-4CDB-AD7F-5C09CBEFAA59_4_5005_c](https://user-images.githubusercontent.com/101157423/174483262-a514725f-4e72-406c-82b4-02ce407fb61d.jpeg)

As you can see from the dataframes above, Lot 3 does not meet this requirement as it's variance is 170.28.

## T-Tests on Suspension Coils

![C6C9C5E5-C4C6-4593-BE79-6FC7C474FC8D_4_5005_c](https://user-images.githubusercontent.com/101157423/174484471-2ca22288-b8ce-4e4f-b335-c4a68cbc9be8.jpeg)

![7BEEF624-3A20-4BF9-9D7D-BC7AE8B85C28_4_5005_c](https://user-images.githubusercontent.com/101157423/174484482-4c57b1df-3e18-4ebb-bd56-607953a07de2.jpeg)

![B685F934-9664-41EF-965B-CB29EFB4B1E7_4_5005_c](https://user-images.githubusercontent.com/101157423/174484490-50df0e1c-cb62-4286-9bad-e4a477ebbd0f.jpeg)

![35DB06CE-602F-4C15-B5FF-E380753FD230_4_5005_c](https://user-images.githubusercontent.com/101157423/174484497-ad28be19-d270-4580-84ee-b0c79f65f158.jpeg)

The results of our T-Tests for each of the three lots are shown above. Assuming our significance level was the common 0.05 percent, our p-value is above our significance level for Lot 1 and 2. Therefore, we do not have sufficient evidence to reject the null hypothesis for those lots, and we would state that the two means are statistically similar. The p-value for Lot 3 is below the 0.05 level and therefore we would reject the null hypothesis.

## Study Design: MechaCar vs Competition

In today's climate of sharply rising gas prices, a linear regression model of MPG vs the competition would be an important potential selling point for MechaCar. Multiple metrics, such as vehicle length, vehicle weight, spoiler angle, drivetrain, and ground clearance, could be collected for comparable vehicles from several competitors. A linear model that predicts the mpg of each vehicle could then be performed to compare the fuel efficiency of MechaCar vs the competition.
