# Customer Churn Prediction for PowerCo 🚀

This project aims to  predicts customer churn for PowerCo a utility company by identifying the key drivers of attrition and forecasting high-risk customers. Through comprehensive analysis of price sensitivity - particularly the impact of peak vs. off-peak pricing differentials - we investigate whether price variations drive customer decisions to leave. The insights aim to help PowerCo improve customer retention strategies and optimize their pricing structure. 📊

**Important Note**: This project was completed during the virtual internship provided by BCG X on Forage. It should not be mistaken for actual work conducted directly for BCG X.

## Project Highlights 🌟
- 🔍 Conducted a thorough Exploratory Data Analysis (EDA) to uncover patterns and trends in customer behavior.
- 🛠️ Engineered features to enhance model performance and capture critical churn indicators.
- 🤖 Developed and evaluated predictive models, achieving 92% accuracy with an XGBoost classifier.
- 🧠 Analyzed feature importance using SHAP values to explain the model's predictions.

## Files 📂
- **Notebook**: Complete analysis and workflow in `Customer_Churn_Analysis.ipynb`.
- **Data**: Processed datasets for analysis:
  - `client_data.csv`: Contains customer demographic and subscription details.
  - `price_data.csv`: Includes pricing and tariff information.
  - `combined_and_merged.csv`: Final dataset used for modeling.
- **Model**: Pre-trained XGBoost model saved as `xgb_model.joblib` for reuse.
- **Output**: Predicted churn results available in `predictions.csv`.
- **Dependencies**: All required Python packages listed in `requirements.txt`.

## Usage 🖥️
1. 🔗 Clone the repository and navigate to the project directory.
2. 📦 Install dependencies using:
   ```bash
   pip install -r requirements.txt
   ```
3. 📓 Open and run the Jupyter notebook `Customer_Churn_Analysis.ipynb` to replicate the analysis.
4. 📁 Load the saved model and use it for predictions:
   ```python
   import joblib
   xgb_model = joblib.load('xgb_model.joblib')
   ```
5. 📈 Inspect the predictions in `predictions.csv` for insights into customer churn.

## Contact ✉️
Krishna Kasera
- **Email**: kkasera025@gmail.com
