# Used-Car-Price-Prediction 
## Uses data such as the year, manufacturer and title status of many cars to predict the price of another car.

### Used Car Prices
As we can see from the chart below, the dataset has been trimmed to only include cars in the < 50k range. This was done for getting rid of outliers.
![Untitled](https://github.com/amoogat/Used-Car-Price-Prediction/assets/61531986/32a73be9-d769-4c14-96e3-56023ef139c6)

### Prediction Assumptions
I assumed that information such as VIN, state, and region were not important and left them out in order to get a more generalized answer. 

### Data Cleaning + Feature Engineering
There was a fair amount of incomplete data, roughly 30% that was dropped. Some features were made by multiplying other scaled numerical columns together.

### Results
Overall, this model could be used to predict a price of a car well within +/- 25% of the car's price on average. The mean absolute error was 3600.
