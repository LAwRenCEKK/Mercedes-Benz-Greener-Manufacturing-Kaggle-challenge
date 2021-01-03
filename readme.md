# Mercedes-Benz Greener Manufacturing


## Problem Statement Scenario:

Since the first automobile, the Benz Patent Motor Car in 1886, Mercedes-Benz has stood for important automotive innovations. These include the passenger safety cell with a crumple zone, the airbag, and intelligent assistance systems. Mercedes-Benz applies for nearly 2000 patents per year, making the brand the European leader among premium carmakers. Mercedes-Benz is the leader in the premium car industry. With a huge selection of features and options, customers can choose the customized Mercedes-Benz of their dreams.

To ensure the safety and reliability of every unique car configuration before they hit the road, the company’s engineers have developed a robust testing system. As one of the world’s biggest manufacturers of premium cars, safety and efficiency are paramount on Mercedes-Benz’s production lines. However, optimizing the speed of their testing system for many possible feature combinations is complex and time-consuming without a powerful algorithmic approach.

You are required to reduce the time that cars spend on the test bench. Others will work with a dataset representing different permutations of features in a Mercedes-Benz car to predict the time it takes to pass testing. Optimal algorithms will contribute to faster testing, resulting in lower carbon dioxide emissions without reducing Mercedes-Benz’s standards.

For this project, the challenges are to tackle the curse of dimensionality and reduce the time that cars spend on the test bench. I works with a dataset representing different permutations of Mercedes-Benz car features to predict the time it takes to pass testing.

##### Models are evaluated on the R^2 value, also called the coefficient of determination.
### Following actions are performed:

-   If for any column(s), the variance is equal to zero, then you need to remove those variable(s).
-   Check for null and unique values for test and train sets.
-   Apply label encoder.
-   Perform dimensionality reduction.
-   Predict your test_df values using XGBoost.

### Data Description:

This dataset contains an anonymized set of variables, each representing a custom feature in a Mercedes car. For example, a variable could be 4WD, added air suspension, or a head-up display.

The ground truth is labeled ‘y’ and represents the time (in seconds) that the car took to pass testing for each variable.

### File descriptions:
Variables with letters are categorical. Variables with 0/1 are binary values.

-   train.csv: the training set
-   test.csv: the test set, you must predict the 'y' variable for the 'ID's in this file
