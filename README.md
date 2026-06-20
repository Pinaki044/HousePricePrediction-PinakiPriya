# House Price Prediction Using Machine Learning

## Project Overview

This project focuses on predicting house prices using machine learning techniques. The goal is to analyze various property features such as area, number of bedrooms, bathrooms, stories, parking availability, and other amenities to estimate the selling price of a house.

The project was completed as part of an AI/ML Internship Week 1 assignment.

---

## Objective

* Explore and understand the housing dataset.
* Clean and preprocess the data.
* Build machine learning models for house price prediction.
* Compare the performance of different regression models.
* Visualize important patterns and relationships in the data.
* Generate insights that can help real estate businesses make better decisions.

---

## Dataset

**Housing Prices Dataset**

Source: Kaggle Housing Prices Dataset

The dataset contains information about residential properties, including:

* Price
* Area
* Bedrooms
* Bathrooms
* Stories
* Main Road Access
* Guest Room
* Basement
* Hot Water Heating
* Air Conditioning
* Parking
* Preferred Area
* Furnishing Status

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Google Colab

---

## Data Preprocessing

The following preprocessing steps were performed:

* Checked for missing values
* Checked for duplicate records
* Converted categorical variables into numerical format using One-Hot Encoding
* Prepared feature and target variables for model training

---

## Machine Learning Models

### 1. Linear Regression

Used as the baseline regression model.

### 2. Random Forest Regressor

Used to compare performance with Linear Regression.

---

## Model Performance

| Model                   | MAE          | RMSE         | R² Score |
| ----------------------- | ------------ | ------------ | -------- |
| Linear Regression       | 970,043.40   | 1,324,506.96 | 0.6529   |
| Random Forest Regressor | 1,021,546.04 | 1,400,565.97 | 0.6119   |

### Best Performing Model

Linear Regression achieved the highest R² Score and lower prediction errors, making it the better-performing model for this dataset.

---

## Visualizations

The project includes the following visualizations:

1. Distribution of House Prices (Histogram)
2. Correlation Heatmap
3. Actual vs Predicted House Prices
4. House Price vs Area Scatter Plot

All charts are available in the `charts` folder.

---

## Key Insights

* House area is one of the strongest factors affecting house price.
* Bathrooms, parking availability, stories, and air conditioning also contribute significantly to property value.
* Most houses are concentrated in the lower and middle price ranges.
* Linear Regression performed better than Random Forest, suggesting a relatively linear relationship between features and house prices.

---

## Project Structure

```text
HousePricePrediction_PinakiPriya
│
├── analysis.ipynb
├── Housing.csv
├── summary.pdf
│
└── charts
    ├── price_distribution.png
    ├── correlation_heatmap.png
    ├── actual_vs_predicted.png
    └── price_vs_area.png
```

---

## Author

**Pinaki Priya**

AI/ML Internship Project – Week 1

House Price Prediction using Machine Learning
