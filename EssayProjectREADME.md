Grading Student Essays Project

Paul Kruger 


Project Goals

Teachers often have to grade hundreds of student essays on the same subjects year after year.  What if we could use machine learning to grade their students’ papers for them, saving valuable educator time and energy?

The Dataset

The text of ~13,000 real student essays and the grades assigned to them by actual human teachers.
(source: Kaggle)

Feature Engineering

Features engineered:  Counts per essay of words, misspellings, punctuation, proper nouns, stopwords, average length of word, and average length of sentence.  NLP techniques used include:  TFIDF vectorization, count vectorization, word tokenization, stopword removal, bigram and trigram measures

The Best Model

Multi-Layered neural network for linear regression, trained on 68 epochs, produced best result of 1.7% RMSE





