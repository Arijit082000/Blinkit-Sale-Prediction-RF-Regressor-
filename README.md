#  Blinkit Grocery Sales Analysis and Sales Prediction using Machine Learning

##  Project Overview
This project analyzes Blinkit's grocery sales data and builds a **Random Forest Regressor** to predict product sales. It includes data cleaning, exploratory data analysis (EDA), feature engineering, preprocessing, model training, and performance evaluation.

##  Objectives
- Analyze sales trends across products and outlets.
- Identify factors affecting sales.
- Predict product sales using Machine Learning.

##  Dataset
**File:** `BlinkIT Grocery Data.xlsx`

### Target Variable
- **Sales**

### Features
- Item Weight
- Item Fat Content
- Item Visibility
- Item Type
- Outlet Size
- Outlet Type
- Outlet Location Type
- Outlet Establishment Year
- Rating
- And other product/outlet attributes.

##  Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

##  Exploratory Data Analysis
The notebook includes:
- Missing value analysis
- Average sales by Item Type
- Average sales by Outlet Type
- Average sales by Outlet Size
- Sales vs Rating
- Sales by Item Fat Content
- Outlet Establishment Year analysis
- Sales vs Item Visibility
- Top 5 selling product categories
- Outlet Location Type distribution

##  Data Preprocessing
- Missing values filled using mean
- Standardized Item Fat Content labels
- Created **Outlet_Age**
- Created **Item_Category**
- Replaced zero Item Visibility values
- Label Encoding of categorical variables
- Train-Test Split (80:20)

##  Machine Learning Model
**Algorithm:** Random Forest Regressor

Parameters:
- n_estimators = 300
- random_state = 42

##  Evaluation Metrics
- R² Score (Training)
- R² Score (Testing)
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

The notebook also visualizes:
- Actual vs Predicted Sales (Line Plot)
- Actual vs Predicted Sales (Scatter Plot)

##  Project Structure
```
Blinkit Data Analysis and sale prediction using ML.ipynb
BlinkIT Grocery Data.xlsx
README.md
```

##  Installation
```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
```

Run:
```bash
jupyter notebook
```

##  Results
The Random Forest model achieved a high training R² score and good testing performance, demonstrating its effectiveness in predicting grocery sales while providing business insights through EDA.

##  Future Improvements
- Hyperparameter tuning using GridSearchCV
- XGBoost and LightGBM comparison
- Cross-validation
- Feature importance visualization
- Streamlit deployment

##  Author
**Arijit Dasgupta**


