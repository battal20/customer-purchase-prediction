### **Predicting Customer Purchases and Timing with Machine Learning**

📌 **Project Overview**

This project predicts whether a customer will purchase a product within the next four weeks and, if so, determines in which specific week the purchase will occur. The dataset consists of transactional and product-related data, which have been preprocessed and used to train models for both classification and regression tasks. The insights generated can help businesses optimize marketing strategies and forecast demand effectively.

⚙️ **Methods Used**

Classification Approach: Predicts whether a customer will make a purchase within four weeks.

Regression Approach: Determines the exact week of purchase if the customer is predicted to buy.

Machine Learning Models:

CatBoostClassifier & XGBoostClassifier for classification tasks.

CatBoostRegressor & XGBoostRegressor for predicting purchase timing.

LSTM & TCN for deep learning-based predictions.

🛠 **Technologies**

Python

Libraries: XGBoost, CatBoost, Scikit-Learn, Pandas, NumPy, Matplotlib, TensorFlow, Keras, PyTorch, TorchVision

🚀 **Getting Started**

Installation & Usage

Clone the repository:

git clone https://github.com/battal20/customer-purchase-prediction.git

Navigate to the project folder:

cd customer-purchase-prediction

Install required dependencies:

pip install xgboost catboost scikit-learn pandas numpy matplotlib tensorflow keras torch torchvision

Run the Jupyter Notebook:

jupyter notebook purchase_prediction.ipynb

🔮 **Future Enhancements**

Performance can be improved by implementing ensemble learning techniques that combine multiple models for better predictive accuracy. Exploring transformer-based models, such as BERT or Wav2Vec, could enhance time-series forecasting and improve predictions. Additionally, developing an interactive dashboard visualization would allow businesses to interpret the predictions more effectively and make data-driven decisions in real-time.

👥 **Contributors**

Aybike Battal - CatBoost and XGBoost Implementation

İlayda Kara - LSTM and TCN Implementation

📂 **Repository**

GitHub Link: https://github.com/battal20/customer-purchase-prediction

