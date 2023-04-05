# Samuel Kuczynski MechaCar_Statistical_Analysis-

## Overview of Project

### Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Jill and I worked together to build up skills in the following that allowed us to tackle creating multiple machine learning models using different strategies to help provide us the best solution.

## Deliverables

### There were 4 main objectives we attacked during this task.
    - Part 1: Linear Regression to Predict MPG
    - Part 2: Summary Statistics on Suspension Coils
    - Part 3: T-Test on Suspension Coils
    - Part 4: Design a Study Comparing the MechaCar to the Competition

## Part 1: Linear Regression to Predict MPG

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

Using our model we were able to find that the intercept (5.08e-08), vehicle weight (2.60e-12) and ground clearance (5.21e-08) provided a non-random amount of variance in 3*s of significance.

Is the slope of the linear model considered to be zero? Why or why not?

The slope of the linear model does not consider to be zero due to having a p-value of 5.35e-11. 

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

This model can predict mpg of MechaCar with an effective rate of 71% from our R^2 being 0.71.

![Part_1](https://github.com/SKuczynski17/Credit_Risk_Analysis/blob/main/Supervised%20Learning%20Challenge/Photos/Naive_Oversampling.png)
* Balanced Accuracy Score: 63%

## Part 2: Summary Statistics on Suspension Coils

Our suspension coil summary statistics show that as a whole the manufacturing data meets our design specifications, fitting under our max variance target of 100. However, Lot 3 is a huge outlier that does not fit within the 100-psi variance, we need to dive deeper as this lot could put our entire process at risk. 

![Part 2](https://github.com/SKuczynski17/Credit_Risk_Analysis/blob/main/Supervised%20Learning%20Challenge/Photos/Naive_Oversampling.png)
![Part 2](https://github.com/SKuczynski17/Credit_Risk_Analysis/blob/main/Supervised%20Learning%20Challenge/Photos/Naive_Oversampling.png)

## Part 3: T-Test on Suspension Coils

Our Lots 1 & 2 do not show any significant differences coming in with p values of 1 & 0.6 respectively. However, Lot 3 does have a statistically significant mean difference with a p value of 0.4 which is lower than our threshold of 0.5.

![Part 3](https://github.com/SKuczynski17/Credit_Risk_Analysis/blob/main/Supervised%20Learning%20Challenge/Photos/Naive_Oversampling.png)
![Part 3](https://github.com/SKuczynski17/Credit_Risk_Analysis/blob/main/Supervised%20Learning%20Challenge/Photos/Naive_Oversampling.png)

## Part 4: Design a Study Comparing the MechaCar to the Competition

To start comparing our Mecha Car to other competitors we would first want to poll the population by city on which metrics they find the most important. 

Individuals living in California will most likely have different needs than somebody living in Ohio. We would then want to take these metrics and create a test that would show whether our Mecha Car is significantly better than a competitor’s car at.

Our null hypothesis would be that our MechaCar is not significantly better than other competitors at important metrics.
