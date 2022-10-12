# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![image](https://user-images.githubusercontent.com/107373721/193969991-5c82f960-f130-4727-b35a-9a51b375e521.png)

1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

The most significant variables in the dataset which provide a non-random amount of variance to the MPG value are the Vehicle Length and Ground Clearance. 
- vehicle length: 0 < .05, statistically significant, non-random amount of variance
- ground clearance: 0 > .05 statistically significant, non-random amount of variance

The intercept is also significanly significant. The intercept indicates there are also values, not shown in this dataset, that  have affect on the MPG.

2. Is the slope of the linear model considered to be zero? Why or why not?

If we convert the coeficients from scientific notion, the slopes of the varibles are non-zero and the null hypothesis must be rejected.

Coefficients: 
- vehicle length: 6.267 
- vehicle weight: .001 
- spoiler angle: .069 
- ground clearance: 3.546 
- AWD: -3.411

The multiple linear regression formula for mpg = -.01 + 6.267(vehicle length)+.001(vehicle weight)+.069(spoiler angle)+3.546(ground clearance)-3.411(AWD), which results in a non-zero slope.

3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The r-squared has a value of 0.7149, indicating that the model is 71% accurate. This is a strong corelation and shows this is an effective dataset. However, r-squared is not the only consideration for effectiveness. There may be other variables not included in the dataset contributing to the variation in the mpg.

## Summary Statistics on Suspension Coils

### Total Summary
![image](https://user-images.githubusercontent.com/107373721/195218691-a53845e9-7b27-4cc8-b513-42c106fd6ded.png)

### Lot Summary
![image](https://user-images.githubusercontent.com/107373721/195218983-0718f268-b9f4-444e-a6ab-2714096c30b3.png)

The Total Summary above shows the mean of 1498.78 for this sample and the population mean was determined at 1500. The lot means fells within range of the poplation mean and the sample mean. 

1. The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
- The variance from the Total Summary meets the design specification for not exceeding 100 PSI. However, the variance from Lot 3 in the Lot Summary greatly exceeds the design specification with a variance of 170. 

## T-Tests on Suspension Coils

#### All Manufacturing Lots: 
![image](https://user-images.githubusercontent.com/107373721/195226959-eec8529c-c7b5-454a-975c-a11fb49f6ff7.png)
- This is not statistically significant from the normal distribution and normality can be assumed. The mean falls within the 95% confidence interval.

### Lot 1
![image](https://user-images.githubusercontent.com/107373721/195228433-df68816b-482e-4c5c-b637-9236b0759f2f.png)
 -Lot 1 shows that they are not statistically different from the population mean, and the p-value is not low enough for us to reject the null hypothesis.

### Lot 2
![image](https://user-images.githubusercontent.com/107373721/195233134-985f3bd8-2c43-4f86-8b9e-fe4b86967300.png)
- Lot 2 is not statistically significant from the normal distribution and normality can be assumed, the mean falls within the 95% confidence interval.

### Lot 3
![image](https://user-images.githubusercontent.com/107373721/195234794-577c2529-d22f-4bc7-b0a7-4f3c679498a0.png)
- Lot 3 is is statistically significant from the normal distribution and normality cannot be assumed. However, the mean falls within the 95% confidence interval.

## Study Design: MechaCar vs Competition
In a world where most people are now work from home (WFH), a person interested in a vehicle is most likely to take into consideration the maintance of owning a vehicle at the time of purchase. 

### Metric to test
For consumers who want a relaible vehicle while driving sparingly, the next metrics to test would be fuel efficienty and cost per drive.


