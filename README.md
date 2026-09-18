SMS Spam Classification

This project is a basic machine learning application for classifying SMS messages as Spam or Ham (Not Spam).

Project Overview

The project uses text classification techniques to identify whether an SMS message is spam or a normal message.

Dataset
Total messages: 5,572
Training messages: 4,457
Testing messages: 1,115
Technologies Used
Python
Pandas
Scikit-learn
TF-IDF Vectorization
Multinomial Naive Bayes
Google Colab
Methodology
Load and clean the SMS dataset.
Convert text labels into numerical values.
Split the data into training and testing sets.
Convert SMS text into numerical features using TF-IDF.
Train a Multinomial Naive Bayes classifier.
Evaluate the model using accuracy, precision, recall, F1-score, and a confusion matrix.
Results

The model achieved:

Accuracy: 96.05%
Precision: 100%
Recall: 70.47%
F1-Score: 82.68%

The confusion matrix showed that 44 spam messages were classified as ham, while no ham messages were classified as spam.

Files
SMS_Spam_Classification.ipynb — Google Colab/Jupyter Notebook containing the complete code.
spam.csv — Dataset used for the project.
Conclusion

This project demonstrates a simple and effective approach to SMS spam classification using traditional machine learning techniques. TF-IDF and Multinomial Naive Bayes were sufficient for this basic text classification task.
