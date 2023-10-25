# Project Name

> Surprise Housing is a US-based housing company, that decicded to enter the Australian market. The comapany aims to utilize data science to purchase house on discount to its intensic value and flip them at a higher price. It collected 1460 samples of house sales in Australia, and we aim to utilize it to generate a regression model to predict sale price. In this project, we will use Lasso and Ridge regression methods to overcome overfitting issue in the simple regression model.

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

Surpise Housing provided 1460 sample of house sales along with their features to predict sale price. It aims to use the model to decide on the price to purchase and flip at a higher price. Along with the price estimation, the company interested in identify top predictors of the sale price.

To solve the problem, we aim to utlize Lasso and Ridge regression methods to address overfitting issue, observed in the simple linear regression method. Overfitting the model to the train dataset leads to sub-optimial solution in the test performance and do not generalized to the unseen dataset. In the lasso and ridge regression method, we will find the optimize regualization scale that yields better test performacne while maintaining lower divergernce between train and test evaluation metric.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

Lasso regression method results in best R-square with 0.829 at alpha 0.0197. Under these settings, the error between the actual and predicted is expected to be minimum. The top 5-predictors of house sale price are ovearll quality, living ara, garage size fits # of cars, overall condition, and year built. The coefficients are positive for all these predictors and that means with increase in values, the sale price is expected to increase exponentially.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used

- numpy - version 1.23.5
- pandas - version 1.5.3
- matplotlib - version 3.7
- seaborn - version 0.12.2
- sklearn - version 1.2.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact

Created by [@@nagaraju-oruganti] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
