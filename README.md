# Stock-Price-Prediction-Using-Machine-Learning-

## Project Overview  
This project implements **machine learning models** to predict stock price trends and optimize trading strategies using **historical stock data**. The analysis is performed on **Lockheed Martin Corporation (LMT) stock** to evaluate different ML approaches for forecasting buy/sell signals.  

## Key Features  
- **Stock Data Collection**: Fetched **8 years (2015–2022)** of historical data using Yahoo Finance.  
- **Trading Strategy 1 - Classification Approach**: Predicted buy/sell signals using **KNN, Random Forest, SVM, Gradient Boosting, and XGBoost**.  
- **Trading Strategy 2 - Moving Averages**: Implemented **50-day & 200-day moving averages** to enhance trend forecasting.  
- **Model Performance Evaluation**: Compared accuracy across multiple classifiers, achieving **98.6% accuracy** with Gradient Boosting & XGBoost.  
- **Hyperparameter Tuning**: Optimized models using **GridSearchCV** to improve performance.  
- **Data Visualization**: Generated **heatmaps, bar plots, and scatter plots** for insights and model evaluation.  

## Technologies Used  
- **Python**  
- **Pandas, NumPy** – Data Processing  
- **Matplotlib, Seaborn** – Data Visualization  
- **Scikit-learn, XGBoost** – Machine Learning Models  
- **Yahoo Finance API** – Stock Data Collection  

## Project Structure

```
📁 Stock-Analysis-ML

┣ 📜 stock_analysis.ipynb # Jupyter Notebook with complete code
┣ 📜 ML Project 1.pdf # Project Problem statement
┣ 📜 README.md # Project documentation
```

## Results  
- **Strategy 1 (Classification Approach)**: Achieved **54% accuracy** with SVM.  
- **Strategy 2 (Moving Averages)**: Outperformed classification models, achieving **98.6% accuracy** with XGBoost & Gradient Boosting.  
- **Final Conclusion**: The moving average strategy proved more reliable for stock trend prediction.  

# License
This project is open-source and available under the MIT License.



