## 📱 SMS Spam Detection

A machine-learning project that classifies SMS messages as **Spam** or
**Ham (Not Spam)**.

## 🚀 Project Overview

This project loads an SMS dataset, cleans the data, performs
preprocessing, extracts text features, trains ML models, and evaluates
accuracy.

## 📂 Dataset

-   **target** --- spam or ham\
-   **text** --- SMS message content\
    Unused columns are removed.

## 🧹 Steps Performed

### 1️⃣ Data Cleaning

-   Removed unnecessary columns\
-   Renamed columns\
-   Checked for missing values\
-   Handled duplicates

### 2️⃣ Exploratory Data Analysis

-   Checked spam vs ham distribution\
-   Visualized counts

### 3️⃣ Text Preprocessing

-   Lowercasing\
-   Removing punctuation\
-   Removing stopwords\
-   Stemming\
-   TF-IDF vectorization

### 4️⃣ Model Training

Models used: - Naive Bayes\
- MultinomialNB\
- Other classifiers

### 5️⃣ Model Evaluation

-   Accuracy\
-   Confusion matrix\
-   Classification report

## 🛠️ Technologies Used

-   Python\
-   Pandas\
-   NumPy\
-   Matplotlib\
-   Seaborn\
-   Scikit-Learn

## 🏁 Final Output

A classifier that predicts whether a given SMS is **Spam** or **Ham**.
