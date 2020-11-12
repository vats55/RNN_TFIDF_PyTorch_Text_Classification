# RNN_TFIDF_PyTorch_Text_Classification
Binary Text Classification using TF-IDF, RNN architecture and PyTorch in the GOOGLE COLLAB environment.
* dataset can be obtained from https://drive.google.com/drive/folders/1qJ0LZpZYvtCU-GQrGIrKqUmO_nVzrPw8?usp=sharing

The training dataset has reviews, and a flag denoting whether it had a positive sentiment or negative (binary). The task is to classify a given review as positive or negative. 

As we know, machine learning algorithms cannot take raw text data as input, hence converting text data into numbers is essential. There are numerous methods for feature extraction from text data as follows: 
-> Bag-of_Words
-> TF-IDF 
-> Word2Vec

But we have considered TF-IDF for this binary text classification problem. A brief description is as follows: 
-> do note that 200 is the max number of features considered. Means that the top 200 out of the pool of words which are rare in the whole document but frquently occurs across various documents. 

-> Even handled issue of variable length of documents. 

-> each word within a doc is represented as a vector of 200. 

Next is to use Recurrent Neural Network architecture to train our model and make predictions over a validation dataset. The performance is then evaluated by comparing to the ground truth labels known and the predicted labels obtained from model. 

Have made sure to include comments where ever necessary for reader's reference. 


