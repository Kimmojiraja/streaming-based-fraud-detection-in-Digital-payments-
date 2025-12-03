# streaming-based-fraud-detection-in-Digital-payments-
This project presents a machine-learning powered real-time fraud detection system designed for India’s digital payment ecosystem (UPI &amp; Wallets). It focuses on detecting suspicious transactions instantly using advanced ensemble learning and explainable AI.

## 1. Introduction
The growing adoption of digital payments in India, especially through UPI and mobile wallets, has also led to a significant increase in online fraud activities such as phishing, fake apps, unauthorized access, and social engineering attacks. These security threats result in financial loss and reduced trust in digital platforms. Therefore, a real-time, intelligent, and transparent fraud detection system is required to identify suspicious transactions instantly.

## 2. Problem Statement
Traditional rule-based fraud detection systems are limited because they cannot adapt to rapidly changing fraud patterns. Fraudulent transactions form only a very small portion of total transactions, making them difficult to detect. Real-time detection is essential so that suspicious activities can be stopped before financial damage occurs.

## 3. Project Objective
The aim of this project is to design a real-time fraud detection framework that:
	- Automatically classifies transactions as legitimate or fraudulent
	- Learns behavior patterns to detect evolving fraud strategies
	- Handles severe data imbalance
	- Provides transparency in predictions to support financial auditing
	- Operates in near real-time to assist payment systems and banks

## 4. Methodology
The project follows a structured machine learning pipeline consisting of:
	- Data preprocessing to clean and transform raw transaction records
	- Feature engineering to create behavioral and time-based indicators
	- Data balancing using SMOTE to overcome minority class scarcity
	- Model building using gradient boosting techniques
	- Evaluation through fraud-appropriate metrics
	- Explainability using SHAP for transparent decision-making
	- Real-time simulation to demonstrate live transaction scoring

## 5. Machine Learning Approach
The system compares multiple ensemble learning models such as LightGBM, XGBoost, and CatBoost to identify the most suitable model for real-time deployment. These models are selected because they effectively handle complex and imbalanced datasets while maintaining high predictive performance

## 6. Explainable AI
The project incorporates SHAP (Shapley Additive Explanations) to analyze the contribution of each feature toward model predictions. This ensures:
	- Clear reasoning behind flagged transactions
	- Compliance with financial regulations
	- Increased trust among system users and auditors

## 7. Real-Time Streaming Simulation
To replicate real operational scenarios, a simulation environment processes each transaction sequentially with minimal latency. This demonstrates the ability of the model to function in real-world payment systems such as banks, UPI gateways, and fintech platforms.

## 8. Conclusion
This project proposes a scalable, real-time, and interpretable machine learning system for detecting fraud in digital payments. By combining behavioral analytics, data balancing techniques, ensemble learning, and explainable AI, the framework helps financial institutions improve security and protect users against evolving cyber threats while promoting trust in the digital economy.
