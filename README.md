
Fraudulent transactions pose a significant threat to online payment systems. This project implements a machine learning-powered fraud detection system that can identify and prevent fraudulent transactions in real-time using AI.


Key Features
Real-Time Fraud Detection – Classifies transactions as fraudulent or legitimate  
AI-Powered Risk Analysis – Uses Random Forest, XGBoost, and other ML models  
Interactive Dashboard – Provides fraud insights with live transaction monitoring 
Anomaly Detection – Detects unusual transaction behaviors 
Automated Alerts– Flags high-risk transactions instantly 

Tech Stack
Programming Python (FastAPI, Streamlit)
Machine Learning: Scikit-learn, XGBoost, Random Forest
Data Processing: Pandas, NumPy, Matplotlib, Seaborn
Database: SQLite / MongoDB for transaction storage
APIs: REST API for seamless integration with payment platforms

Dashboard Features
Fraud Heatmap – Highlights high-risk zones  
Live Logs – Tracks flagged transactions in real time  
Visual Insights – Pie charts, bar graphs for fraud trends  

Dataset
The dataset is collected from Kaggle, containing historical fraud transaction records. 

step: Represents time (1 step = 1 hour)
  type: Type of online transaction  
  amount: Transaction amount  
  nameOrig: Customer initiating the transaction  
  oldbalanceOrg: Balance before transaction  
  newbalanceOrig: Balance after transaction  
  nameDest: Recipient of the transaction  
  oldbalanceDest: Initial balance of recipient before the transaction  
  newbalanceDest: New balance of recipient after the transaction  
  isFraud: Indicates whether the transaction was fraudulen


Achievements
Achieved 90%+ accuracy** in fraud detection  
Optimized ML models** using feature selection & hyperparameter tuning  
Designed a scalable architecture** for real-world deployment  

 Future Enhancements
Implement LSTM models for better fraud pattern recognition  
Deploy model as API for fintech integration  
Use blockchain for enhanced transaction security  



