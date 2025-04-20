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
 Navigate to project directory
    cd Credit-Card-Fraud-Detection
Set up the environment:
    python -m venv venv
    source venv/bin/activate  # On Windows, use venv\Scripts\activate
    pip install -r requirements.txt
    python fraud_detection.py

#### 3. **Code Quality Guidelines**
- **Clean, Well-Structured Code**: 
   - Make sure that your Python code is clean and well-commented.
   - You can use meaningful variable names, avoid hardcoding values, and structure the project in a modular way (e.g., separate the data preprocessing, model training, and evaluation into different functions or files).
   
- **Functionality**: Ensure that your code works well and meets the objectives stated above (i.e., trains a model, evaluates it, and produces meaningful results).

#### 4. **Innovative Features**
Here, you can highlight any special features or optimizations you made to improve the model's performance or make the project unique.
For example:
```markdown
### Innovative Features:
- Implemented SMOTE to handle the highly imbalanced dataset.
- Added hyperparameter tuning for the Random Forest model to optimize its performance.



