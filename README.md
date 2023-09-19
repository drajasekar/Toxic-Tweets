# Toxic Tweet Classification using Bag of Words and TF-IDF

Overview

This repository contains code and resources for a machine-learning project that aims to classify toxic tweets using the Bag of Words (BoW) approach and TFIDF. The Bag of Words model is a basic text representation technique 
that can be used for various natural language processing (NLP) tasks, including text classification. In this project, we will focus on identifying toxic tweets from a given dataset.

Prerequisites

Before you begin, ensure you have met the following requirements:

Python 3.x: You will need Python installed on your machine to run the code.

Jupyter Notebook: We recommend using Jupyter Notebook for interactive development.

Python libraries: Make sure to install the necessary Python libraries, such as NumPy, pandas, scikit-learn, and NLTK. You can install these libraries using pip:

Preprocessing the input
Lemmatization:

Lemmatization is a natural language processing (NLP) technique that reduces words to their base or root form, which is called a lemma.The goal of lemmatization is to simplify words while preserving their semantic meaning.

Stop word removal:

Stop word removal is a preprocessing step in natural language processing (NLP) that involves the removal of common words, known as "stop words,
" from a text. Stop words are words that are considered to be of little value in text analysis because they are very frequent in most texts and do not carry significant meaning on their own. Examples of common stop words in English include "the," "and," "is," "in," "of," "it," "to," "that," and "for."

TF-IDF

TF-IDF, or Term Frequency-Inverse Document Frequency, is a numerical statistic used in natural language processing and information retrieval to evaluate the importance of a word within a document relative to a collection of documents, often called a corpus. TF-IDF is a commonly used technique for feature engineering and text analysis, especially in tasks like document retrieval, text classification, and information retrieval.

Evaluation of Test Classification result for TFIDF
SVC 
F1 Score:  0.937527114967462

KNeighborsClassifier
F1 Score:  0.33041086470689357

LogisticRegression
F1 Score:  0.9271812814345068

DecisionTreeClassifier
F1 Score:  0.9188617370147043

RandomForestClassifier
F1 Score:  0.9327544212644288

MultinomialNB
F1 Score:  0.9027374533388635

![download (6)](https://github.com/drajasekar/Toxic-Tweets/assets/44079369/23563061-ceb2-44ea-8e0f-31f43df961e2)


Evaluation of Test Classification result for Bag of words
SVC
F1 Score:  0.9303318041182119

KNeighborsClassifier
F1 Score:  0.8677047160300213

LogisticRegression
F1 Score:  0.9334321092179068

DecisionTreeClassifier
F1 Score:  0.9214322781525688

RandomForestClassifier
F1 Score:  0.9300083822296731

MultinomialNB
F1 Score:  0.9026742220896711

![download (7)](https://github.com/drajasekar/Toxic-Tweets/assets/44079369/d132c1fb-eb19-42b2-a2e2-be52a5e65262)
