# Amazon Review Analysis: Sentiment & Helpfulness Prediction

This project applies Natural Language Processing (NLP) and Machine Learning techniques to analyse customer reviews and predict both sentiment and perceived helpfulness.

The objective is to extract meaningful insights from textual data and build predictive models that classify reviews based on user opinion (sentiment) and usefulness (helpfulness).

---

## Key Features

* Data preprocessing and cleaning of raw review data
* Feature engineering including:

  * Sentiment labels derived from ratings
  * Helpfulness ratio based on user votes
  * Review length analysis
* Text processing using:

  * Lowercasing and regex-based cleaning
  * Stopword removal
  * TF-IDF vectorisation
* Machine Learning models:

  * Logistic Regression
  * Multinomial Naive Bayes
* Model evaluation using:

  * Accuracy, Precision, Recall, F1-score
  * Confusion matrices
  * Cross-validation
* Comparative analysis between:

  * Sentiment classification
  * Helpfulness classification

---

## Results Summary

* Sentiment classification achieved higher accuracy (~87–88%) and more balanced performance.
* Helpfulness classification (~86%) was more challenging due to:

  * Strong class imbalance
  * Subjective nature of helpfulness
* Logistic Regression consistently outperformed Naive Bayes in both tasks.
* Models showed bias toward majority classes, highlighting the importance of evaluating beyond accuracy.

---

## Key Insights

* Sentiment is easier to predict because it is directly expressed in text.
* Helpfulness is more complex and depends on user perception, making it harder to model.
* Class imbalance significantly impacts model performance, especially for minority classes.
* TF-IDF is effective for capturing important textual features in review data.

---

## Technologies Used

* Python
* Pandas & NumPy
* Scikit-learn
* Matplotlib
* Natural Language Processing (NLP)

---

## 📁 Project Structure

```
├── DS_Assignment2.ipynb       # Main analysis notebook
├── processed_reviews.csv     # Cleaned dataset
├── README.md                 # Project documentation
```

---

## Future Improvements

* Apply advanced models (e.g., SVM, Random Forest, or Deep Learning)
* Address class imbalance using techniques like SMOTE
* Incorporate additional features such as review metadata
* Explore word embeddings (Word2Vec, BERT)

---

## Author

This project was developed as part of a Data Science assignment, demonstrating skills in data preprocessing, NLP, and machine learning.
