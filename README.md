# Fake News Detection Using Machine Learning

## Overview

Fake News Detection is a Natural Language Processing (NLP) task that aims to identify and classify news articles as **Real** or **Fake** based on their textual content.

This project implements a machine learning approach to fake news detection using **TF-IDF vectorization and a Linear Support Vector Machine (SVM)** classifier.

## Dataset

The project uses two datasets:
- `true.csv` – Contains authentic news articles.
- `false.csv` – Contains fake news articles.

Both datasets are analyzed and processed to prepare the text for machine learning.

## Methodology

The following steps are performed:

1. **Data Collection:** Load and analyze the `true.csv` and `false.csv` datasets.
2. **Data Preprocessing:** Clean and prepare the textual data for analysis.
3. **Feature Extraction:** Apply TF-IDF (Term Frequency–Inverse Document Frequency) to convert text into numerical feature vectors.
4. **Model Training:** Train a Linear Support Vector Machine (Linear SVM) classifier on the processed data.
5. **Model Evaluation:** Evaluate the trained model using classification metrics such as accuracy, precision, recall, and F1-score.

## Model Performance

The trained Linear SVM model achieved an accuracy of approximately **99%** on the test dataset.

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- spaCy
- Scikit-learn
- Matplotlib
- Seaborn
- WordCloud

## Repository

GitHub: https://github.com/Bhavik-Jikadara/Fake-News-Detection

## Conclusion

This project demonstrates how Natural Language Processing and machine learning techniques can be combined to classify news articles as real or fake. The Linear SVM model achieved approximately 99% test accuracy, showcasing the effectiveness of TF-IDF-based text representation for this classification task.

**Note:** The reported accuracy reflects performance on the selected test dataset and does not necessarily indicate the model's ability to detect fake news in all real-world scenarios.
