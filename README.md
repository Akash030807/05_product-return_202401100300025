# 05_product-return_202401100300025
Product Return Prediction uses machine learning to classify whether a purchased item will be returned based on order context and customer reviews. The project applies logistic regression and evaluates performance using accuracy, precision, recall, and a confusion matrix. 
# 🛍️ Product Return Prediction

This project focuses on building a machine learning model to classify whether a purchased item will be returned based on purchase context and customer reviews.

## 📌 Problem Statement
In e-commerce, predicting product returns can help optimize logistics and reduce losses. The goal is to use historical purchase data and review features to predict if an item is likely to be returned.

## 🧹 Data Preprocessing
- Handled missing values using column-wise mean imputation
- Applied one-hot encoding to categorical features
- Scaled features using StandardScaler
- Split dataset into 80% training and 20% testing

## 🔍 Model Used
- **Logistic Regression** for binary classification
- Evaluated using accuracy, precision, recall, and F1 score
- Confusion matrix visualized with Seaborn heatmap

## 📊 Evaluation Metrics
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **Confusion Matrix**

## 🧠 Results & Insights
- The model performed well on the test data
- Heatmap helped analyze false positives and false negatives
- Precision and recall revealed the model’s capability to detect actual returns

## 📈 Future Enhancements
- Try advanced models like Random Forests, XGBoost
- Address data imbalance using SMOTE or other techniques
- Incorporate sentiment analysis from customer reviews

## 📚 Libraries Used
- `pandas`
- `numpy`
- `scikit-learn`
- `seaborn`
- `matplotlib`

## 📝 How to Run
1. Clone this repository  
2. Install dependencies  
3. Run `product_return_prediction.py`  

```bash
git clone https://github.com/your-username/product-return-prediction.git
cd product-return-prediction
pip install -r requirements.txt
python product_return_prediction.py
