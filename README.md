# Credit Card Fraud Detection Using Random Forest

This project implements a fraud detection system using machine learning. The model uses the Random Forest Classifier to predict fraudulent credit card transactions. The dataset is highly imbalanced, so SMOTE (Synthetic Minority Over-sampling Technique) is used to address the class imbalance.

### Task Objectives:
- Train a Random Forest Classifier on the dataset.
- Handle class imbalance using SMOTE.
- Evaluate model performance using various metrics like accuracy, precision, recall, and F1-score.

## Steps to Run the Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/Credit-Card-Fraud-Detection.git
2. **Navigate to project directory**:
   ```bash
   cd Credit-Card-Fraud-Detection
3. **Set up the environment**:
   ```bash
   python -m venv venv
4. **Activate the virtual environment**:
   ```bash
   source venv/bin/activate  # On Windows, use venv\Scripts\activate
5. **Install required dependencies**:
   ```bash
   pip install -r requirements.txt
6. **Run the script**:
   ```bash
   python fraud_detection.py

