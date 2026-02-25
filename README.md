# Stock-Price-Movement-Analysis-Prediction
This project analyzes historical stock market data and predicts the next-day price movement (Up/Down) using Machine Learning models.
The goal of the project is not to predict the exact price, but to identify whether the stock price is likely to increase or decrease based on historical trading patterns and technical indicators.
Workflow: Data preprocessing -> Exploratory Data Analysis (EDA) -> Feature engineering -> Model training -> Model evaluation -> Visualization and insights
The dataset contains historical stock trading data with the following features: Date, Open price, High price, Low price, Close price, Volume
Target Variable: Target = 1 → Price goes up next day ; Target = 0 → Price goes down next day
Technologies Used : Python, Pandas & NumPy, Scikit-learn, Matplotlib & Seaborn, Machine Learning Algorithms
1. Data Preprocessing: Converted date column to datetime format
                       Sorted records chronologically
                       Removed missing values
2. Feature Engineering: Created technical indicators(Daily Return, 5-day Moving Average (MA5), 10-day Moving Average (MA10))
                        These indicators help capture short-term price trends.
3. Exploratory Data Analysis (EDA): Closing Price Trend
                                    Shows how stock price changes over time.
                                    Moving Average Trend
                                    Compares closing price with MA5 and MA10 to identify momentum and trend direction.
                                    Return Distribution
                                    Analyzes volatility of the stock.
                                    Correlation Heatmap
                                    Shows relationships between stock features and helps understand important predictors.
4. Machine Learning Models Implemented: Decision Tree Classifier
                                        K-Nearest Neighbors (KNN)
                                        Support Vector Machine (SVM)
5. Model Evaluation: Accuracy Score
                     Confusion Matrix
                     Classification Report (Precision, Recall, F1-Score)
                     A comparison chart was created to identify the best performing model.
6. Visual Outputs: Closing price time-series plot
                   Moving average chart
                   Return distribution plot
                   Feature correlation heatmap
                   Confusion matrix for each model
                   Model performance comparison bar chart
Key Insights : Moving averages helped identify short-term trend direction. Stock returns showed volatility clustering.

Decision Tree performed better in capturing non-linear price movement patterns compared to SVM and KNN.
