# SENTIMENT-ANALYSIS-WITH-NLP

COMPANY : CODTECH IT SOLUTIONS
NAME : R GIRIDHAR
INTERN ID : CTIS2163
DOMAIN : MACHINE LEARNING 
DURATION : 4 WEEKS
MENTOR : NEELA SANTOSH

Task 2: Sentiment Analysis Using NLP

Task Description

Task 2 focuses on Sentiment Analysis, a key application of Natural Language Processing (NLP). The objective is to classify customer reviews as positive or negative using TF-IDF vectorization and Logistic Regression.
Customer reviews are unstructured text data, which cannot be directly used by machine learning models. Therefore, the task emphasizes converting raw text into meaningful numerical features.
Implementation Details
The task starts with loading a dataset of customer reviews and performing text preprocessing. This includes converting text to lowercase, removing punctuation, eliminating stopwords, and cleaning irrelevant characters. After cleaning, the TF-IDF (Term Frequency–Inverse Document Frequency) technique is applied to transform textual data into numerical vectors that capture the importance of words in each review.
A Logistic Regression classifier is then trained on the transformed data. Logistic Regression is chosen due to its simplicity, efficiency, and strong performance in text classification tasks.
Evaluation
The trained model is evaluated using accuracy, confusion matrix, precision, recall, and F1-score. These metrics help assess how well the model predicts sentiments and handles misclassifications.
Deliverable
A Jupyter Notebook showcasing:
•	Text preprocessing pipeline
•	TF-IDF feature extraction
•	Logistic Regression model training
•	Sentiment prediction and evaluation


Review 1: The movie was absolutely fantastic and I loved every scene
Prediction: Positive 😊 | Confidence: 97.83%
----------------------------------------------------------------------
Review 2: Worst movie ever, completely wasted my time
Prediction: Negative 😠 | Confidence: 99.93%
----------------------------------------------------------------------
Review 3: Amazing performance by the lead actor
Prediction: Positive 😊 | Confidence: 96.99%
----------------------------------------------------------------------
Review 4: The storyline was boring and predictable
Prediction: Negative 😠 | Confidence: 99.63%
----------------------------------------------------------------------
Review 5: I enjoyed the film, it was entertaining
Prediction: Positive 😊 | Confidence: 99.44%
----------------------------------------------------------------------
Review 6: Terrible acting and poor direction
Prediction: Negative 😠 | Confidence: 99.93%
----------------------------------------------------------------------
Review 7: One of the best movies I have seen this year
Prediction: Positive 😊 | Confidence: 99.00%
----------------------------------------------------------------------
Review 8: The movie was too long and very dull
Prediction: Negative 😠 | Confidence: 98.17%
----------------------------------------------------------------------
Review 9: Excellent visuals and great background music
Prediction: Positive 😊 | Confidence: 99.61%
----------------------------------------------------------------------
Review 10: I did not like the movie at all
Prediction: Negative 😠 | Confidence: 62.27%
----------------------------------------------------------------------
Review 11: The plot was interesting and engaging
Prediction: Negative 😠 | Confidence: 74.91%
----------------------------------------------------------------------
Review 12: Bad screenplay and weak characters
Prediction: Negative 😠 | Confidence: 99.67%
----------------------------------------------------------------------
Review 13: The film exceeded my expectations
Prediction: Negative 😠 | Confidence: 65.44%
----------------------------------------------------------------------
Review 14: Not worth watching, very disappointing
Prediction: Negative 😠 | Confidence: 94.96%
----------------------------------------------------------------------
Review 15: Outstanding direction and brilliant acting
Prediction: Positive 😊 | Confidence: 93.97%
----------------------------------------------------------------------
Review 16: The movie failed to impress me
Prediction: Negative 😠 | Confidence: 86.72%
----------------------------------------------------------------------
Review 17: A wonderful cinematic experience
Prediction: Positive 😊 | Confidence: 96.81%
----------------------------------------------------------------------
Review 18: The story lacked depth and emotion
Prediction: Negative 😠 | Confidence: 57.68%
----------------------------------------------------------------------
Review 19: Highly recommended movie
Prediction: Positive 😊 | Confidence: 98.56%
----------------------------------------------------------------------
Review 20: The movie was horrible and annoying
Prediction: Negative 😠 | Confidence: 99.89%
----------------------------------------------------------------------
