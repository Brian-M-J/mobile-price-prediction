# **Mobile Price Prediction Project**
This project analyzes mobile phone features to predict their price range using Machine Learning. It uses Ensemble Learning (Random Forest) with automatic hyperparameter tuning and includes model explainability using SHAP. The dataset is originally from [Kaggle](https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification).

## **Prerequisites**
* **Pixi**: This project uses [pixi](https://prefix.dev/) for package management. Please install it first if you haven't already.

## **Setup \& Running**
1. **Install Dependencies**:
Navigate to this folder in your terminal and run:
```
pixi install
```
2. **Start Jupyter Lab**:
Run the following command to open the notebook interface:
```
pixi run start
```
3. **Run the Analysis**:
Open `mobile_price_analysis.ipynb` in the Jupyter interface and run all cells to see the analysis, model training, and explanation.

## **Project Structure**
- `train.csv` / `test.csv`: The dataset files.
- `mobile_price_analysis.ipynb`: The main notebook containing:
  - Data Cleaning & EDA
  - Feature Engineering
  - Model Selection (Random Forest + Grid Search)
  - Evaluation
  - Explainability (SHAP & Feature Importance)
