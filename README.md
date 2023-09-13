# Bike Sharing Assignment

> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

> The business goal is to create a demand prediction model for shared bikes using various independent variables. This model will help management understand how demand changes with different factors, enabling them to adapt their business strategy to meet customer expectations and evaluate demand dynamics in new markets.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- All variables containing the +ve coffecients like temp , yr, season summer , value of cnt increases as the value of vars increases
- All variables containing the -ve coffecients like windspeed, weekday_Sun,holiday value of cnt decreases as the value of vars increases
- Based on the R-Squared and Adjusted R-Squared values for both the training and testing datasets, it can be inferred that these variables effectively account for more than 81% of the variation in bike demand
  Addtional Information for the company based on the univariate and bivariate analysis
- Most of the data in the dataset is uniformaly distributed ie contains no major outliers
  The company should prioritize the months of January, July, September, November, and December due to their notably higher demand compared to other months.
- During holidays, biking appears to be less appealing. Implementing additional motivation and marketing strategies could potentially enhance interest and demand during these times.
- Preparing for the winter season is crucial, as the demand experiences a notable surge during this period.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used

Pandas - version 1.5.3
NumPy - version 1.23.5
Seaborn - version 0.12.2
MatplotLib - version 3.7.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.

## Contact

Created by [Priyanshu Kumar](https://github.com/priyanshu966106) - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
