
---

# Quora Question Pair Classification 🚀❓🤔

## Project Overview 🎯

This project tackles the challenge of identifying **duplicate questions** on **Quora**. Have you ever asked a question only to realize it's already been asked and answered? 🤦‍♂️ This model helps classify whether two questions are duplicates (similar) or not. By doing this, Quora can instantly provide answers to questions already answered, saving time for both users and moderators. 📈

## Key Features ⚡

- **Dataset**: Worked with a massive dataset of **400,000+ question pairs** 📝.
- **Text Preprocessing & Cleaning**: Used **NLTK** and **Scikit-learn** to clean and preprocess the text data 🧹.
- **Text Vectorization**: Leveraged **TF-IDF** and **SpaCy** to turn text into meaningful vectors 🧠.
- **Exploratory Data Analysis (EDA)**: Visualized data trends using **Matplotlib** and **Seaborn** 📊.
- **Ensemble Modeling**: Built an ensemble model combining **Random Forest**, **XGBoost**, and **Decision Tree** to achieve an accuracy of **80%** 🎯.

## Problem Statement 🧐

We are tasked with predicting whether a pair of questions are duplicates or not on Quora. This is useful for delivering accurate answers to users faster. However, the **cost of misclassification** is high, as wrong predictions could either:
1. **Miss a duplicate**, causing redundancy in questions.
2. **Flag unrelated questions as duplicates**, leading to confusion.

Thus, we need to not only classify but also provide a **probability score** for a pair being duplicates, allowing for flexible threshold adjustments depending on the need.

## Tools & Libraries Used 🛠️

- **NLTK**: Natural Language Toolkit for text preprocessing.
- **Scikit-learn**: Used for cleaning data and building models.
- **SpaCy**: Advanced NLP library for text vectorization.
- **TF-IDF**: Text vectorization for feature extraction.
- **Matplotlib & Seaborn**: Visualization libraries for EDA.
- **Random Forest, XGBoost, Decision Tree**: Ensemble modeling techniques.

## Model Workflow ⚙️

1. **Text Preprocessing**: Tokenization, stopword removal, stemming/lemmatization.
2. **Feature Extraction**: Used **TF-IDF** and **SpaCy vectors** to represent question pairs numerically.
3. **Modeling**: Built an ensemble of classification algorithms:
    - **Random Forest** 🌳
    - **XGBoost** 🛠️
    - **Decision Tree** 🌲
4. **Evaluation**: Achieved **80% accuracy** on test data, with fine-tuning for threshold adjustment based on the **probability of duplicates** 📊.

## Results & Performance 📊

- Achieved an **80% accuracy** on test data.
- Visualized key relationships and data insights through **Matplotlib** and **Seaborn** plots.
- The model allows for dynamic threshold adjustments based on the desired confidence level for duplicate prediction.

## Visualizations 🖼️

Here are some cool visualizations from the EDA:

![Pair Plot](images/pairplot.png)
![Distribution](images/distribution.png)

## Future Improvements 🔮

- Implementing **deep learning** methods like **LSTMs** or **BERT** for improved text understanding.
- Adding **more advanced feature engineering** using question metadata (timestamps, question popularity).
- Exploring **active learning** to prioritize questions with uncertain classifications for manual review.

## Contributing 👫

Feel free to fork this project, create issues, or submit pull requests if you'd like to help improve it! 🙌

