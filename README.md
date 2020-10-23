**[Fast Campus Data Science School]**

# Hotel Room Pricing Regression Project
![jeju2](https://user-images.githubusercontent.com/68367273/96717667-c9d9de00-13e1-11eb-8538-411e4aad24ff.jpg)


## Introduction
As the restrictions on overseas travel persist amid the COVID-19 pandemic, Jeju Island has been one of the favorite tourist destinations in the nation and is expected to continue to be one of the favorite until the end of the pandemic. The purpose of this project is to understand important pricing factors/variables and help travelers estimate their budget for hotel accomodation. The data used for modeling was extracted from Interpark Hotel website (http://hotel.interpark.com) using Selenium while the data from Booking.com was collected using an Apify actor (https://blog.apify.com/crawling-booking-com-47511a59eef). The data includes various attributes such as check-in date, name, price, star, rating score, review counts and other features.


## Contributors
- Jinseo Lee : in charge of Interpark Hotel data
- Hyungki Kim : in charge of Hotels.com data


## Process
- Data preparation
- Data understanding and exploration
- Outlier removal
- Model building and evaluation
- Cross validation

### Price Outlier Removal

- Interpark Hotel
<img src="https://user-images.githubusercontent.com/68367273/96967697-daf22e80-154a-11eb-988c-fabe037e7c3c.png" alt="drawing" width="650"/>

- Booking.com
<img src="https://user-images.githubusercontent.com/68367273/96967743-ee04fe80-154a-11eb-8345-e24d2e18484b.png" alt="drawing" width="650"/>

## Regression Models
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- XGB Regressor
- LGBM Regressor


## Evaluation

### Interpark Hotel
- Comparison of RMSE and R2 score of training and testing data sets
<img src="https://user-images.githubusercontent.com/68367273/96961009-b2fcce00-153e-11eb-94ba-d75b58458c39.png" alt="drawing" width="500"/>

- Box plot of cv scores of classifiers over 5-fold cross validation 
<img src="https://user-images.githubusercontent.com/68367273/96966247-6fa75d00-1548-11eb-900d-33545a3492c4.png" alt="drawing" width="650"/>

- Scatter plot of actual price vs predicted price
<img src="https://user-images.githubusercontent.com/68367273/96966479-d3318a80-1548-11eb-9a3d-5878b58291f1.png" alt="drawing" width="650"/>

### Booking.com
- Comparison of RMSE and R2 score of training and testing data sets
<img src="https://user-images.githubusercontent.com/68367273/96956718-d3735b00-1533-11eb-86c3-39e25244fcad.png" alt="drawing" width="500"/>

- Box plot of cv scores of classifiers over 5-fold cross validation
<img src="https://user-images.githubusercontent.com/68367273/96967797-01b06500-154b-11eb-809c-fdc785bddb48.png" alt="drawing" width="650"/>

- Scatter plot of actual price vs predicted price
<img src="https://user-images.githubusercontent.com/68367273/96967858-112fae00-154b-11eb-8c2a-4487b45dedb5.png" alt="drawing" width="650"/>





