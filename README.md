# NLP and Recommender Systems with Amazon Movies & TV Reviews
## Summary 
* Extracted and worked with 650,000 observations of Amazon movies and T.V reviews data and metadata extracted from multiple Json files obtained from the UCSD data repository. 
* Cleaned, tokenized and pre-processed data using techniques like stemming and lemmatizations to visualize frequencies and get the data ready for machine learning. 
*Used a Naive Bayes model with 4 different combinations of word embeddings with bag of words and tf-idf models to find the best possible combination for being able to predict the overall rating a review represents using just the text of the review(Multi-class classification)
* Used the pre-processing and model pipeline to make predictions on unseen recent reviews pulled from Amazon for titles that did not exist in the dataset and used local surrogate models approach using LIME( Local Interpretable Model Agnostic Explanations ) library to visualize why the model made the prediction it made and what the model has learned from the training vectors.
* Used more sophisticated libraries like Spacy and Gensim to pre-process the data and use LDA topic modeling to create a theme based recommender system based on high rated reviews from the users in the dataset and created a second more computationally efficient recommender system using a model based collaborative filtering system with SVD matrix factorization.


