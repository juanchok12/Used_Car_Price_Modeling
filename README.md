# Used Car Price Modeling
<img src=https://github.com/juanchok12/Used_Car_Price_Modeling/assets/116334702/06bde452-7404-4f4f-8af1-a6bd9a83f918 width="85%" alt="data_source">

## Overview & Objectives

### Research questions:
* What are the main characteristics of a used car which have the most impact on the car price?
* How do we assess if a dealer is offering a fair value for a trade-in car?
* How do we assess if we are placing a fair value on a used car?

## Data
* `make`
* `num-of-doors`
* `body-style`
* `drive-wheels`
* `engine-location`
* `wheel-base`
* `length`
* `width`
* `height`
* `curb-weight`
* `engine-type`
* `num-of-cylinders`
* `engine-size`
* `fuel-system`
* `bore`
* `stroke`
* `compression-ratio`
* `horsepower`
* `peak-rpm`
* `city-mpg`
* `highway-mpg`
* `price`
* `city-L/100km`
* `horsepower-binned`
* `fuel-type-diesel`
* `fuel-type-gas`

## Methodology
### Data Cleaning:
* Familiarized myself with the data.
* Displayed descriptive statistical metrics
### Data Wrangling:
* Replaced null values with useful ones, such a mean values or other.
* Calculated means of selected columns to understand trends in data.
* Changed data types.
* Standardization of data metrics.
* Normalized data.
* Created histogram to understand trends in horsepower in data.
* Created indicator variables to create categorical binary variables (e.g. whether car use gas or diesel)
## Exploratory Data Analysis:
* Linear regression.
* ANOVA hypothesis testing and F-testing.
* P-value and Pearson Correlation Coefficient asssessment.
* Descriptive statistical analysis.
* Value counts and statistics by grouping


## Used Tools
* Matplotlib
* Numpy
* Pandas
* Seaborn
* Scipy
* Sklearn

## Key Takeaways
For predicting price of used cars, we can narrow down the variables that have correlations. For numerical variables: 
* Length
* Width
* Horsepower
* Curb-weigth
* Engine-size
* City-mpg
* Highway-mpg

For categorical variables:
* Drive-wheels

