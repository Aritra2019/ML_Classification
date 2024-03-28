# ML_Classification
# Machine Learning Project: Rock vs Mine Prediction and Spam vs Ham Classification

## Overview
This repository contains Python scripts for two machine learning projects:
1. **Rock vs Mine Prediction**: Classifying sonar signals as either rocks (R) or mines (M).
2. **Spam vs Ham Classification**: Identifying spam and ham (non-spam) messages.

Both projects utilize supervised learning techniques and feature engineering to train classification models.

## Project Structure
- `rock_vs_mine_prediction.ipynb`: Jupyter Notebook containing code for the Rock vs Mine Prediction project.
- `spam_vs_ham_classification.ipynb`: Jupyter Notebook containing code for the Spam vs Ham Classification project.
- `sonar_data.csv`: Dataset used for the Rock vs Mine Prediction project.
- `mail_data.csv`: Dataset used for the Spam vs Ham Classification project.

## Technologies Used
- Python
- Libraries: Pandas, NumPy, Scikit-learn, NLTK
- Machine Learning Models: Logistic Regression, Support Vector Machine (SVM)

## Key Features
### Rock vs Mine Prediction:
- Data preprocessing: Cleaning, normalization, and feature selection.
- Model training: Utilizing Logistic Regression and SVM for classification.
- Evaluation: Assessing model performance using accuracy metrics.

### Spam vs Ham Classification:
- Text preprocessing: Tokenization, stop word removal, and TF-IDF vectorization.
- Model training: Implementing Logistic Regression for text classification.
- Evaluation: Measuring classification accuracy and predicting on new text inputs.

## Results
### Rock vs Mine Prediction:
- Achieved a training accuracy of 83.42% and a test accuracy of 76.19% using Logistic Regression.

### Spam vs Ham Classification:
- Attained a training accuracy of 96.97% and a test accuracy of 96.95% with Logistic Regression.

## Future Improvements
- Explore additional machine learning algorithms for better performance.
- Conduct more extensive hyperparameter tuning.
- Implement advanced natural language processing techniques for text classification.

## Usage
1. Clone the repository: `git clone https://github.com/your-username/machine-learning-projects.git`
2. Navigate to the project directory.
3. Open the Jupyter Notebooks to view and run the code.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
