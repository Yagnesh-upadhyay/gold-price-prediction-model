# gold-price-prediction-model

Predicting commodity prices requires capturing complex, non-linear interactions between global asset classes. In this project, I built a predictive framework leveraging ensemble learning to model and forecast Gold ETF ($\text{GLD}$) prices based on historical macroeconomic indicators.

# 🛠️ Technical Breakdown & Methodology:
Macroeconomic Data Sourcing: Sourced a comprehensive historical dataset from Kaggle containing critical global market proxies: the S&P 500 Index ($\text{SPX}$), Silver ETF ($\text{SLV}$), United States Oil Fund ($\text{USO}$), and the $\text{EUR/USD}$ currency exchange rate.

Feature Correlation Analysis (EDA): Utilizing Pandas, NumPy, and Seaborn, I constructed a feature correlation matrix and distribution visualizations. This exploratory data analysis uncovered vital market dependencies—such as the historically strong positive collinearity between silver ($\text{SLV}$) and gold—allowing for better contextual understanding before training.

Ensemble Modeling with Random Forest: Implemented a Random Forest Regressor via Scikit-learn. This algorithm was selected for its exceptional ability to handle multi-dimensional financial features, resist overfitting through bootstrap aggregating (bagging), and capture complex non-linear relationships without requiring rigid assumptions of normality.

Model Evaluation: After conducting a rigorous train-test split, the model achieved an exceptional R-squared ($R^2$) score of $0.989$ on unseen validation data, proving its high precision and strong generalization capabilities.



# 💻 Tech Stack:
Environment: Google Colab

Data Manipulation: Pandas, NumPy

Machine Learning: Scikit-learn (Random Forest Regressor)

Data Visualization: Matplotlib, Seaborn
