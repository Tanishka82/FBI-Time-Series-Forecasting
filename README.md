# 🕵️ FBI Daily Crime Time Series Forecasting

This project uses machine learning to forecast daily crime incidents based on historical FBI time series data. We built and compared multiple models to find the best performing solution for real-world deployment.

## 📊 Models Implemented
- **ARIMA**: For traditional univariate time series forecasting.
- **Prophet**: Captures seasonality and trends easily.
- **XGBoost** ✅ *(Final Model)*: Performed best with highest R² and flexibility for feature engineering and explainability.

## 📈 Final Model Performance (XGBoost)
- **MAE**: 11.21  
- **RMSE**: 22.81  
- **R² Score**: 0.49  

The model was further explained using **SHAP values** to understand the feature impact on predictions.

## 📂 Dataset Access
Due to size constraints, the training and testing datasets are stored in Google Drive.

➡️ [Download Dataset (Train + Test)](https://drive.google.com/drive/folders/1RfyLQLXYylhzx02wGyyzyHh-HeTF9Xo1?usp=sharing)

> Please download and upload the files manually before running the notebook.

## 🚀 How to Run & Deploy
1. Clone this repository.
2. Open the notebook in **Google Colab**.
3. Upload the datasets from the Drive link.
4. Run all cells to:
   - Train the model
   - Evaluate performance
   - Generate SHAP explainability plots
5. Export the trained model as `.joblib` or `.json`.
6. Use Flask, FastAPI, or Streamlit for deployment *(future scope)*.

## ✅ Project Status
✔ Model trained and evaluated  
✔ SHAP explainability integrated  
✔ Ready for deployment  
✔ All files organized for reproducibility

## 📌 Conclusion
This project demonstrates how machine learning can effectively forecast time-based crime data. XGBoost emerged as the best model, combining prediction accuracy and model interpretability for deployment-ready performance.
