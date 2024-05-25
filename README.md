# N-GRAMS ASSISTED YOUTUBE SPAM COMMENT DETECTION
#### Paper Link: https://ymerdigital.com/uploads/YMER210440.pdf


## ABSTRACT

This project presents a novel technique for detecting intrusive comments or spam on YouTube. Spam comments are those with persuasive intent or contextually irrelevant to the video. The rise in YouTube’s popularity has attracted malicious users who deploy automated bots to spread spam, harming channel reputation and user experience. YouTube's current methods for blocking such comments are inadequate, as spammers find ways to bypass them. Standard machine learning algorithms like Random Forest, Support Vector Machine, and Naive Bayes, combined with custom heuristics such as Count Vectorizer, offer a promising solution. This work aims to enhance spam detection accuracy using these approaches.


## INTRODUCTION

YouTube, founded in 2005 and acquired by Google in 2006, has grown into the largest video-sharing platform, allowing users to interact through comments. However, this feature is exploited by malicious users to post spam, which negatively affects video perception. This projectr proposes an ensemble machine learning method to improve spam detection accuracy, addressing YouTube’s existing inadequacies. With the increased computing power available, we apply various machine learning algorithms and heuristics to identify and combat spam effectively.


## SYSTEM DESIGN AND PROPOSED METHODS

* The detection framework includes Data Collection, Data Pre-processing, Feature Extraction, Classification, and Result Comparison. 
* We use the YouTube Spam Collection Data Set and apply Count Vectorizer for feature extraction.
 * Machine learning classifiers such as Random Forest and Naive Bayes are employed to categorize comments as spam or ham.

## TECHNOLOGY DESCRIPTION

Utilized Jupyter Notebook for an interactive data science environment and Visual Studio Code for building and debugging applications.

## IMPLEMENTATION

* Data Collection: We use the YouTube Spam Collection Data Set with manually labeled comments.
 * Data Preprocessing: It involves cleaning text and splitting the dataset for training and testing. 
* Feature Extraction: Uses Term Frequency-Inverse Document Frequency (TF-IDF).
* Classifier Techniques: We employ various classifiers, including MLPs, SVM, k-NN, Logistic Regression, Naive Bayes, Random Forest, and Decision Tree, to predict spam comments.

## TESTING

Used cross-validation and k-fold methods to evaluate performance, with metrics such as Accuracy, Precision, Recall, and F1 Score. SVM with character-grams and n=6 yielded the highest F1 score.

## CONCLUSION AND FUTURE SCOPE

This project demonstrates the effectiveness of machine learning algorithms in detecting YouTube spam, achieving high accuracy. Future work could explore Deep Learning models with Word Embedding and GRU for further improvements in 
