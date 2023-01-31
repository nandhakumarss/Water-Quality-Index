# Water-Quality-Index
Water Quality Index (WQI) and quality status of the water is predicted through some parameter that affects the water quality.

# WATER QUALITY PREDICTION

## ABSTRACT
We all know water is one of the most essential resource for our living. Water is used for various practices, such as drinking, agriculture, and industry. But as the development is increasing, we are exploiting water by wasting it and treating it with harmful materials which makes water impure and unfit for use. Water quality has a direct impact on public health and the environment. This is the reason it is very important to know the quality of water.

Among various sources of water supply, due to easy access, rivers have been used more frequently for the development of human societies. As rivers are the main source of water we have to know the water quality of these rivers.

In this notebook, Water Quality Index (WQI) and quality status of the water is predicted through some parameter that affects the water quality. Performed Data cleaning steps, EDA and used two ML models for predictions, namely Linear regression model and Logistic Regression model

## ABOUT THE DATA
The data contains water quality parameters of different rivers of India. There are 8 parameters and each parameter is the average values measured over a period of time.

## CONTENTS
- Setting up the environment
- Importing libraries
- Uploading the data
- Data Cleaning
- EDA
- Feature Engineering
- Model Creation
- Predictions

## INFRENCE
The Water Quality Index is calculated by aggregating the quality rating with the weight linearly,

WQI = ∑ (qn x Wn)

where qn =Quality rating for the nth Water quality parameter, Wn= unit weight for the nth parameters.

Using the two ML models we have predicted the Water Quality and classified their status into 
“Excellent”,”Good”,”Poor”,”Very poor”,”Unsuitable”

The Logistic Regression has better accuracy than the Linear Regression.
