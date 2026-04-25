# Mobile Price Prediction using Machine Learning
Overview

This project implements a machine learning-based system to classify mobile phones into different price ranges based on their technical specifications. The model is trained using a structured dataset and predicts whether a mobile device falls into budget, mid-range, premium, or flagship categories.

An additional interactive interface is included to estimate resale price based on real-world factors such as device age, condition, and brand.

Problem Statement

Mobile pricing depends on multiple hardware and market-driven factors such as battery capacity, storage, connectivity, and brand value. Manual estimation is often inconsistent.

This project aims to:

Build a classification model to predict mobile price categories
Analyze feature importance for pricing decisions
Provide an interactive system for resale price estimation
Key Features
Machine Learning Model
Random Forest Classifier for multi-class classification
Predicts price range (0 to 3 categories)
Data Processing
Structured dataset handling using Pandas
Feature-target separation
Stratified train-test split for balanced evaluation
Model Evaluation
Accuracy Score for performance measurement
Classification Report (Precision, Recall, F1-score)
Feature Importance
Identifies most influential features affecting price
Helps understand model decision-making
Interactive Web Interface
HTML + JavaScript based UI
User inputs device details
Predicts resale price dynamically
Machine Learning Approach
Model Used
Random Forest Classifier
Target Classes
Class	Category
0	Budget
1	Mid-Range
2	Premium
3	Flagship
Workflow
Load dataset
Split features and target
Train-test split (80/20)
Train Random Forest model
Evaluate performance
Save trained model
Dataset Information
Input Features

The dataset includes mobile specifications such as:

Battery power
RAM
Internal memory
Screen dimensions
Camera specifications
Connectivity features
Target Variable
price_range (0–3 classification)
Model Performance
Training Accuracy: High (indicates learning capability)
Testing Accuracy: Evaluates real-world performance
Overfitting Check: Difference between train and test accuracy
Installation and Setup
Step 1: Clone Repository
git clone https://github.com/your-username/Mobile-Price-Prediction.git
cd Mobile-Price-Prediction
Step 2: Install Dependencies
pip install -r requirements.txt
Step 3: Run the Notebook

Open the notebook in Jupyter or Google Colab and execute all cells.

Usage
Upload the dataset (train.csv)
Train the machine learning model
View model accuracy and feature importance
Use the interface to estimate resale price
Project Structure
Mobile-Price-Prediction/
│
├── Mobile Price Prediction.ipynb
├── train.csv
├── test.csv
├── README.md
Limitations
Resale price UI uses rule-based logic instead of ML model
Model does not include real-time market data
Limited feature engineering
Future Improvements
Integrate resale prediction with trained ML model
Deploy as a web application (Gradio or Streamlit)
Use advanced models like XGBoost or LightGBM
Add real-world dataset integration
Learning Outcomes

This project demonstrates:

Supervised classification using Random Forest
Model evaluation techniques
Feature importance interpretation
Basic frontend integration with ML logic
Author

Jiten Hudda
B.Tech CSE (Artificial Intelligence)
Amity University Punjab

Conclusion

This project demonstrates the practical application of machine learning in mobile price classification and resale estimation by combining data analysis, model training, and user interaction into a single system.
