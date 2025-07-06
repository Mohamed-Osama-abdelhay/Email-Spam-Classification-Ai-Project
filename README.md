📧 Email Spam Classification – AI Project
A machine learning-based project to classify email messages as spam or ham using various supervised learning algorithms. This project demonstrates preprocessing techniques, feature selection, visualization, and evaluation of multiple models.

🚀 Project Overview
The goal of this project is to accurately detect whether a given email is spam or not by training ML classifiers on labeled email data. The models learn patterns in email content using vectorized features and are tested against known labels to evaluate their performance.

📋 Features
📊 Data Preprocessing: Cleaning, duplicate removal, null handling, mapping labels.

📦 Data Representation:

Boxplots for outlier detection

Histograms of text length

Pie chart for spam vs ham distribution

Word frequency analysis

🤖 Models Used:

Logistic Regression

Decision Tree

Support Vector Machine (SVM)

Random Forest

K-Nearest Neighbors (KNN)

🧠 Feature Engineering:

Text vectorization

SelectKBest feature selection

Correlation analysis

🧪 Preprocessing Steps
Load and Explore Dataset

View size, columns, summary statistics

Handle null and duplicate values

Label Encoding

Map labels: "spam" → 1, "ham" → 0

Visualization

Pie chart of spam vs ham

Histogram of message lengths

Word clouds or bar charts of common terms

🧠 Models & Hyperparameters
Model	Hyperparameters
Logistic Regression	C=1.0, solver='liblinear'
Decision Tree	criterion='entropy'
SVM	kernel='rbf', C=1.0
Random Forest	n_estimators=100, random_state=42
KNN	n_neighbors=5

All models are trained on the preprocessed data and evaluated using accuracy and classification metrics.

⚙️ Technologies Used
Python 3

scikit-learn

pandas, NumPy

matplotlib, seaborn

📈 Results & Conclusion
The system successfully classifies user-input emails into spam or ham using trained models. Among the tested algorithms, performance may vary depending on the feature selection and model parameters.

👥 Team Members
Mariem Naeem Senada — 2022170419

Simon Hanna Reyad — 2022170201

Amira Tharwat Hanna — 2022170076

Mohamed Osama Ahmed — 20201700664

Beshoy Akram Alfy — 2022170102

Youssef Ashraf Abdo — 2022170511
