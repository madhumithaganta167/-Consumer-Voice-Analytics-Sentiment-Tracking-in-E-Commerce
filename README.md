**README: Consumer Voice Analytics – Sentiment Tracking in E-Commerce**

**Overview**

This project explores sentiment analysis within the e-commerce space, focusing on customer review data from Amazon Fashion. By leveraging Natural Language Processing (NLP) and machine learning, the team uncovers trends, evaluates product sentiment, and derives actionable insights from consumer feedback to support strategic business decisions.

**Objectives**

Perform Exploratory Data Analysis (EDA) to clean and understand the dataset.

Conduct sentiment analysis using machine learning and deep learning models.

Analyze how review characteristics (e.g., length) impact product ratings.

Perform trend analysis to observe changes in sentiment and engagement over time.

**Dataset**

Source: Amazon Fashion reviews

Size: ~883,000 reviews

Features: Ratings, review text, verification status, timestamps, product info

Technologies & Tools
PySpark and Databricks for distributed data processing

TensorFlow, Keras for neural networks

Scikit-learn, XGBoost for model development

Pandas, Matplotlib, Seaborn for analysis and visualization

Models Implemented
XGBoost Classifier – Best performing model (88.73% accuracy)

Logistic Regression – Fast and interpretable (88% accuracy)

Random Forest Classifier – Balanced performance (83.67% accuracy)

Neural Network (MLP) – Effective for nonlinear patterns (86.57% accuracy)

**Key Findings**

Positive sentiment dominates Amazon Fashion reviews.

XGBoost outperformed all other models in both accuracy and computational efficiency.

Longer review texts slightly correlate with lower ratings.

Review counts peaked in 2016, then declined—reflecting product lifecycle or market shifts.

**Conclusion**

Consumer voice analytics provides deep visibility into customer satisfaction and behavioral patterns. This project illustrates how scalable sentiment analysis using big data and machine learning can empower e-commerce businesses to optimize products, services, and customer engagement strategies.
