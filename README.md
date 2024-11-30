California Housing Price Prediction using XGBoost:

This project uses the California Housing Dataset to predict house prices based on various features such as median income, house age, and geographical factors. The model is implemented using the XGBoost Regressor, a gradient boosting algorithm optimized for performance and accuracy.

Features:
1.Data Analysis: Explore and visualize the dataset to understand key relationships and distributions.
2.Machine Learning: Train and evaluate a regression model using XGBoost.
3.Performance Metrics: Evaluate the model with R² and Mean Absolute Error (MAE).
4.Visualization: Correlation heatmaps and scatter plots to interpret results.

Table of Contents:

Installation
Dataset
Usage
Results
Technologies Used
License

Installation:

1.Clone the repository:
git clone https://github.com/your-username/california-housing-price-prediction.git
cd california-housing-price-prediction

2.Install the required Python packages:
pip install -r requirements.txt


The main libraries include:

numpy
pandas
matplotlib
seaborn
xgboost
scikit-learn

Dataset:
The California Housing Dataset is loaded using fetch_california_housing() from the scikit-learn library. It provides features such as:

MedInc: Median Income
HouseAge: Average age of houses
AveRooms: Average number of rooms per household
Latitude/Longitude: Geographical location
Price (target): Median house price (scaled)
No additional dataset is needed; the data is fetched automatically.

Usage:
1.Open and run the Python script housing_price_prediction.py to train and evaluate the model.

2.Key Outputs:
1.Training and test R² and MAE scores.
2.Correlation heatmap for feature analysis.
3.Scatter plots comparing actual vs. predicted prices for training and test data.

Results:
Training Data:
R² Score: ~0.9
MAE: Approximation of model error for house price predictions.
Test Data:
R² Score: Varies depending on features and test split.
MAE: Approximation of real-world prediction error.

Visualizations include:
A heatmap showing correlations between features and price.
Scatter plots for actual vs. predicted prices.

License:
This project is licensed under the MIT License. See the LICENSE file for details.

Contributing:
Contributions are welcome! Feel free to fork the project, make improvements, and submit a pull request.
1.Fork the repository:
2.Create a new branch (git checkout -b feature-branch).
3.Commit your changes (git commit -m 'Add new feature').
4.Push to the branch (git push origin feature-branch).
5.Open a pull request.
