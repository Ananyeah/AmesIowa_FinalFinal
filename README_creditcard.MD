## Domain Background
This dataset has information on credit line and payments for customers from Taiwan for a series of months.
The purpose of this data set is to explore and find the defaulters before they default.


## Problem Statement
The problem to solve is to find if a customer will default or not (Yes / No)
The strategy towards building the model would be this:

1. Reading, cleaning the data
2. Setting the categoricals / numericals
3. Scaling and transforming the data
4. EDA on the data to find the best predictors
5. Setting a benchmark
6. Running a classification model
7. Seeing how it performs

## Metrics
For classification - AUROC, f-score(not even distributed), accuracy(even distribute)
default payment next month	
0	23364
1	6636

So we will use the F score.

## Data Exploration
Abnormalities:
   Categories not defined ( Marriage = 0 and Education 0, 5, 6 removed)
   zeroes, NA
   Outliers

Exploratory Visualization




Solution Statement

Algorithms and Techniques

• Are the algorithms you will use, including any default variables/parameters
in the project clearly defined?
• Are the techniques to be used thoroughly discussed and justified?
• Is it made clear how the input data or datasets will be handled by the
algorithms and techniques chosen?

Benchmark

• Has some result or value been provided that acts as a benchmark for
measuring performance?
• Is it clear how this result or value was obtained (whether by data or by
hypothesis)?

Project Design
