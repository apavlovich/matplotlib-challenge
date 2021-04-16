# matplotlib-challenge

<h1>Pymaceuticals</h1>

>Observations
1. The correlation coefficient between mouse weight and tumor volume is 0.84. This is a high positive correlation so we can infer that the heavier the mouse, the larger their tumor will be. 
2. The R^2 value is 0.709, indicating that that around 70% of the data fit the regression model of y = 0.74 - 10.15. Therefore, this is a pretty reliable model for predicting values.
3.  Capomulin and Ramicane seem to be most effective at reducing the size of tumors. They had the lowest median tumor sizes and even upper outliers were smaller than the two next best drugs Infubinol and Ceftamin.


>Check for any duplicates
- There was one duplicate mouse (ID: g989)

>Generate a Summary Statistics Table
- The summary statistics table was saved as CSV 

>Total number of measurements taken for each treatment regimen:
- ![measurements taken](https://github.com/apavlovich/matplotlib-challenge/blob/main/Instructions/Images/measurements.png)

>Distribution of male and female mice in the study: 
- ![pie chart](https://github.com/apavlovich/matplotlib-challenge/blob/main/Instructions/Images/male_vs_female_pie.png)

>Tumor Volume Data for Capomulin, Ramicane, Ifubinol, and Ceftamin
- **CAPOMULIN**

  - Lower quartile of tumor volume for mice on Capomulin: 32.37735684
  - Upper quartile of tumor volume for mice on Capomulin: 40.1592203
  - Interquartile Range for tumor volume for mice on Capomulin: 7.781863460000004
  - Median tumor volume for mice on Capomulin: 38.125164399999996
  - Values below 20.70456164999999 could be outliers for Capomulin
  - Values above 51.83201549 could be outliers for Capomulin

- **RAMICANE**

  - Lower quartile of tumor volume for mice on Ramicane: 31.56046955
  - Upper quartile of tumor volume for mice on Ramicane: 40.65900627
  - Interquartile Range for tumor volume for mice on Ramicane: 9.098536719999998
  - Median tumor volume for mice on Ramicane: 36.56165229
  - Values below 17.912664470000003 could be outliers for Ramicane
  - Values above 54.30681135 could be outliers for Ramicane

- **IBUFINOL**

  - Lower quartile of tumor volume for mice on Infubinol: 54.04860769
  - Upper quartile of tumor volume for mice on Infubinol: 65.52574285
  - Interquartile Range for tumor volume for mice on Infubinol: 11.477135160000003
  - Median tumor volume for mice on Infubinol: 60.16518046
  - Values below 36.83290494999999 could be outliers for Infubinol
  - Values above 82.74144559000001 could be outliers for Infubinol

- **CEFTAMIN**

  - Lower quartile of tumor volume for mice on Ceftamin: 48.72207785
  - Upper quartile of tumor volume for mice on Ceftamin: 64.29983003
  - Interquartile Range for tumor volume for mice on Ceftamin: 15.577752179999997
  - Median tumor volume for mice on Ceftamin: 59.85195552
  - Values below 25.355449580000002 could be outliers for Ceftamin
  - Values above 87.66645829999999 could be outliers for Ceftamin

>Box and Whisker Plot for Capomulin, Ramicane, Ibufinol, and Ceftamin
- ![box and whisker](https://github.com/apavlovich/matplotlib-challenge/blob/main/Instructions/Images/box_plot.png)

>Tumor Volume vs. Timepoint for Mouse f966
- ![line graph](https://github.com/apavlovich/matplotlib-challenge/blob/main/Instructions/Images/line_graph.png)

>Linear Regression Model for tumor volume vs. mouse weight for mice on Capomulin
- ![regression](https://github.com/apavlovich/matplotlib-challenge/blob/main/Instructions/Images/linear_regression.png)



