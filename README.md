# NLP Sentiment Analysis Project
This project is a Natural Language Processing (NLP) pipeline built using Python to classify the sentiment of text data. It was developed in Google Colab as part of my learning journey in Machine Learning and NLP.
---
## Objective
To build a machine learning model that can classify text (tweets) into sentiment categories using preprocessing, feature extraction, and a classification algorithm.
---
## Dataset
- Source: Airline tweets dataset (cleaned version)
- Contains:
  - `text_clean`: preprocessed text
  - `sentiment`: target labels
---
## Workflow
The project follows these main steps:
1. **Data Loading**
   - Mounted Google Drive and imported the dataset using Pandas
2. **Text Preprocessing**
   - Tokenization using NLTK
   - Stemming using Porter Stemmer
   - Stopwords removal
3. **Feature Extraction**
   - CountVectorizer with custom tokenizer
   - Bag-of-words representation
4. **Model Training**
   - Support Vector Machine (SVC) with:
     - Linear kernel
     - Balanced class weights
     - Probability enabled
5. **Cross-Validation**
   - Stratified K-Fold (5 splits)
6. **Evaluation Metrics**
   - Accuracy
   - Precision
   - Recall
   - F1 Score
   - AUC (ROC)
7. **Model Evaluation**
   - ROC Curve visualization
   - Prediction on sample tweets
8. **Model Export**
   - Saved trained model using `joblib`
---
## Results
The model was evaluated using multiple metrics and ROC curve analysis to understand its performance in distinguishing between sentiment classes.
---
## Example Predictions
The model was tested on sample tweets with varying sentiment intensity to observe generalization behavior.
---
## Technologies Used
- Python
- Google Colab
- Pandas & NumPy
- NLTK
- Scikit-learn
- Matplotlib & Seaborn
- Joblib
---
## Key Learnings
- Text preprocessing techniques in NLP
- Building ML pipelines
- Feature extraction from text data
- Model evaluation using ROC and classification metrics
- Handling real-world text data limitations

This project was built as part of my learning journey in Machine Learning and NLP.
Feedback and suggestions are welcome!
