# Resume-scanner-NLP-

I got the data set from the kagil and I did EDA and did preprocessing with regular expressions, next we did label encoding next we did vectorization using “Tfidfvectorizer”, next we we trained “Knn” and “onevsrest” clasifer model then we did the prediction  

Step 1: data collected from the kagil
Step 2: performed EDA like viewed the distribution of the data
Step 3:performed Preprocessing (utilized Regular expression library to remove numerical data HTML tags etc.)
Step 4:	label encoded the categorical data and performed vectorization using TF-IDF (TF-IDF vectorization results in a sparse matrix where each row corresponds to a document and each column corresponds to a unique word in the corpus, with values representing the TF-IDF score of each word in the document.)
Step 5: used onevsrest(KNN) to for classification 
(KNN is a simple algorithm that classifies data points based on the majority class among their k nearest neighbors. OvR classifier decomposes the multi-class classification problem into multiple binary classification problems, where each class is treated as the positive class against the rest. These models were trained on the TF-IDF vectors of the text documents along with their corresponding numerical labels.)

Step 6: Prediction:
Once the models were trained, you used them to make predictions on new, unseen text data. The input text documents were first transformed into TF-IDF vectors using the same TF-IDF vectorizer that was used during training. Then, the trained models were applied to predict the categories or labels of the new documents.
