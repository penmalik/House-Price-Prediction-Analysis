# House-Price-Prediction-Analysis
This project explores how different housing characteristics influence property prices using data analysis and multiple linear regression. The goal of the project is to understand which features contribute most to housing value and to build a model capable of estimating house prices based on those features.

The dataset contains 545 housing records with variables such as area, number of bedrooms, number of bathrooms, number of stories, parking availability, air conditioning, preferred location, and other structural or facility related attributes. These variables were used to predict the final house price.

The workflow of this project follows a standard data science process. The dataset was first inspected and cleaned to ensure there were no missing values or incorrect data types. Several categorical features such as main road access, guest room availability, basement presence, air conditioning, hot water heating, and preferred area were converted into numerical form to make them suitable for modeling.

Exploratory data analysis was then performed to understand the distribution of house prices and how individual features relate to the target variable. Visualizations were used to observe patterns and potential relationships between housing characteristics and price.

After the exploratory stage, the dataset was split into training and testing sets in order to evaluate the model properly. A multiple linear regression model was trained using several housing attributes including area, bedrooms, bathrooms, stories, parking, and other housing facilities.

The model was evaluated using Mean Absolute Error and R squared scores. The results show that the model explains a significant portion of the variation in housing prices while maintaining consistent performance between training and testing data. This indicates that the model generalizes reasonably well to unseen data.

Feature importance was also analyzed using regression coefficients to understand which housing characteristics influence prices the most. The analysis shows that factors such as house area, number of bathrooms, air conditioning availability, and location preference have strong effects on housing value.

This project demonstrates a complete regression analysis workflow including data inspection, feature preparation, model training, prediction, and evaluation. It provides a practical example of how machine learning techniques can be used to estimate property prices and understand the factors that drive housing value.

Technologies used in this project include Python, Pandas, NumPy, Matplotlib, Seaborn, and Scikit learn.

```
house-price-prediction-analysis
│
├── data
│   Housing.csv
│
├── notebook
│   house_price_analysis.ipynb
│
└── README.md
```

The data folder contains the dataset used for the analysis.
The notebook folder contains the Jupyter notebook where the entire workflow was implemented including data exploration, modeling, and evaluation.
