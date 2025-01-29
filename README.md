# Credit Card Fraud Detection

## Business Problem

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset consists of transactions labeled as fraudulent or legitimate, and the goal is to build a predictive model to minimize financial losses due to fraud.

## Dataset

The dataset contains transaction details such as time, amount, and anonymized features.

It is highly imbalanced, with fraudulent transactions being a small percentage of the total.

## Technologies Used

Programming Language: Python

Libraries:

Data Processing: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Machine Learning: Scikit-learn, Imbalanced-learn

Dimensionality Reduction: PCA, t-SNE

Model Evaluation: Classification metrics, ROC-AUC

## Installation

Clone the repository:

git clone https://github.com/your-username/credit-card-fraud-detection.git
cd credit-card-fraud-detection

## Install dependencies:

pip install -r requirements.txt

Usage

Open and run the Jupyter Notebook:

jupyter notebook Data_Science_project.ipynb

The notebook walks through data preprocessing, model training, and evaluation.

## Results

Using the SMOTE technique on our dataset led to improved outcomes compared to Random Undersampling. Metrics such as the average precision-recall score, accuracy, and recall score were all enhanced with SMOTE. Based on these results, Logistic Regression performed better than the other classification algorithms evaluated.

## Contributing

Feel free to fork this repository and contribute improvements.

## License

This project is licensed under the MIT License.
