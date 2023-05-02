# Sentiment-Analysis-for-MYM-Intern-Assesment

Text Sentiment Analysis of IMDB Movie reviews using NLP (Word2Vec and RNN) for MYM Intern Assesment

Assesment Objectives:
- Preprocessing the data
- Converting Text(words) to Vectors using word2vec
- Using the word representations given by word2vec to feed a RNN and training the model
- Evaluating the model and plotting the performance graphs
- Improving the model by Transfer Learning
- Comparing Accuracy of Baseline model, The model and Improved model.
- Testing the model (predicting the model with new review)

1. The Data:
 - Starting with 20% of the sentences from TensorFlow Datasets of IMDB reviews to check the RAM compatibility of the PC to train the model faster by          splitting the datasets as X_train, y_train, X_test and y_test.
 - Then preprocessing the textual data to create input features for a natural language processing (NLP) model.
 
2. First, training a word2vec model (with the arguments that we want) on your training sentence. Store it into the word2vec variable.and then Embedding the training and test sentences.

3. Creating the Baseline model to test your own model against.

4. Training the RNN model.
 - Evaluating the model and plotting performance graphs

5. Imroving the model by Transfer Learning:
 - The accuracy of the above the baseline model, might be quite low. By improving the quality of the embedding we can Improve accuracy of the model.
 - Let's improve the quality of our embedding, instead of just loading a larger corpus, let's benefit from the embedding that others have learned. Because,    the quality of an embedding, i.e. the proximity of the words, can be derived from different tasks. This is exactly what transfer learning is.
 
7. Comparing Accuracy of Baseline model, The model and Improved model. 

6. Testing/predicting the model for new review.
   
