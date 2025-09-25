<div style="text-align: center; margin-bottom: 20px;">
  <h1>Linear Regression</h1>
</div>

- Built a Linear Regression model to predict housing prices using features like area, bedrooms, bathrooms, stories, parking, and amenities.
- Prepared the dataset by:
    - Handling outliers in numerical columns (price, area, etc.) using IQR capping to stabilize variance.
    - Encoding categorical columns using one-hot encoding for model compatibility.
- Split the data:
    - Used an 80:20 train-test split to evaluate prediction performance.
- Trained the model using scikit-learn's LinearRegression implementation.
- Evaluated model performance with key metrics:
    - Mean Absolute Error (MAE) on test set: 1,023,421.83
    - Mean Squared Error (MSE) on test set: 1.71×10<sup>12</sup>
    - R-squared score: 0.4236 (moderate explanatory power)
- Analyzed regression coefficients:
    - Found that area and number of bedrooms most strongly drive predicted price.
    - Amenities (air conditioning, basement, guestroom, etc.) add incremental value when present.
- Visualized model coefficients as a bar plot for interpretability.
- Noted that the intercept represents the baseline price when all features are zero.

This approach establishes a transparent baseline for house price prediction and feature impact analysis, setting the stage for further model improvements.
