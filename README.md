# budget-wise
💸 Personal Finance Assistant using Machine Learning and Time Series Forecasting
This project is a complete personal finance assistant that helps users analyze their monthly household expenses using machine learning and predict future spending trends using time series forecasting. It also offers smart investment suggestions based on the user's savings.

📌 Features
✅ Expense Categorization (ML-powered):

Automatically categorizes transactions into Food, Fixed Expenses, and Miscellaneous.

Uses a Convolutional Neural Network (CNN) trained on the "Note" column for accurate classification.

📈 Monthly Expense Forecasting:

Predicts future monthly expenses using historical data.

Uses ARIMA time series model to forecast next month’s spending based on current trends.

💡 Investment Planning:

Suggests suitable investment strategies based on the savings of the current month.

Investment advice ranges from Emergency Funds to SIPs, Mutual Funds, and Full Diversification.

Includes a trained Random Forest Classifier to automate investment suggestions.

🔧 Tech Stack

Backend: Python, Pandas, Numpy

ML Models:

CNN (for text classification)

ARIMA (for forecasting)

Random Forest Classifier (for investment suggestion)

Libraries: Scikit-learn, TensorFlow/Keras, Statsmodels, Matplotlib, Joblib
📊 How it Works

Categorization
Each row is classified into a category using a trained CNN model.

Monthly Forecasting
Based on previous expenses, the model predicts the next month's expected expenses (with a ±₹5000 range).

Investment Suggestions
Net savings are calculated and passed to a Random Forest model that recommends a tailored investment plan.
