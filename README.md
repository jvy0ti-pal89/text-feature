# Text Feature Engineering

## Overview

This project demonstrates how raw text data (product reviews) can be converted into numerical features for machine learning using basic NLP techniques.

---

## Dataset

The dataset consists of 100 product-style reviews created to simulate real-world e-commerce user feedback. It includes both positive and negative opinions stored in a single column `review_text`.

Due to time and access constraints, a synthetic dataset was used instead of live web scraping. However, in real-world scenarios, such data can be collected from platforms like Amazon or Flipkart using tools such as Selenium or BeautifulSoup.

The dataset is sufficient for demonstrating text preprocessing, feature engineering, and model building tasks.

---

## Techniques Used

- Text preprocessing
- Vocabulary creation
- One Hot Encoding
- Bag of Words
- TF-IDF

---

## Model

- Logistic Regression for sentiment classification

---

## Key Findings

- Bag of Words captures frequency but ignores importance
- TF-IDF provides better feature representation
- Feature matrices are highly sparse

---

## Outputs

### Preprocessing

![Preprocessing](screenshots/preprocessing.png)

### Vocabulary

![Vocabulary](screenshots/vocab.png)

### Bag of Words

![BoW](screenshots/bow.png)

### TF-IDF

![TF-IDF](screenshots/tf-idf.png)

### Accuracy

![Accuracy](screenshots/accuracy.png)

---

## Files

- `review.ipynb` → implementation
- `reviews.csv` → dataset
- `report.docx` → detailed explanation
- `README.md` → Documentation

---

## Conclusion

TF-IDF is more effective than Bag of Words for representing important words, though both methods have limitations in understanding context.

---
