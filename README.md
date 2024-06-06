# NLPNewsClassification
Using Natural language processing to classify News Articles.
Context:

The Gurugram-based company ‘FlipItNews’ aims to revolutionize the way Indians perceive finance, business, and capital market investment, by giving it a boost through artificial intelligence (AI) and machine learning (ML). They’re on a mission to reinvent financial literacy for Indians, where financial awareness is driven by smart information discovery and engagement with peers. Through their smart content discovery and contextual engagement, the company is simplifying business, finance, and investment for millennials and first-time investors
Objective:

The goal of this project is to use a bunch of news articles extracted from the companies’ internal database and categorize them into several categories like politics, technology, sports, business and entertainment based on their content. Use natural language processing and create & compare at least three different models.

Objective:

The goal of this project is to use a bunch of news articles extracted from the companies’ internal database and categorize them into several categories like politics, technology, sports, business and entertainment based on their content. Use natural language processing and create & compare at least three different models.
Attribute Information:

Article

Category

The features names are themselves pretty self-explanatory

Concepts Tested:

Natural Language Processing

Text Processing

Stopwords, Tokenization, Lemmatization

Bag of Words, TF-IDF

Multi-class Classification

What does ‘good’ look like?

Installing & Importing all the required libraries and Loading the dataset.

Conduct a preliminary analysis to understand the structure of the dataset and the distribution of news articles in each category.

Create a user defined function to process the textual data (news articles).

Remove non-letters

Remove Stopwords

Word Tokenize the text

Perform Lemmatization

Display how a single news article looks like before and after the processing.

Encode the target variable (category) using Label/Ordinal encoder.

Create an option for the user to choose between Bag of Words and TF-IDF techniques for vectorizing the data.

Perform train-test split and train a Naive Bayes classifier model using the simple/classical approach.

Evaluate the model’s performance and plot the Confusion Matrix as well as Classification Report.

Functionalize the code and train & evaluate three more classifier models (Decision Tree, Nearest Neighbors, Random Forest).

Observe and comment on the performances of all the models used.

Evaluation Criteria (100 points)

1. Importing the libraries & Reading the data file (10 points)

2. Exploring the dataset (10 points)

Shape of the dataset

News articles per category

3. Processing the Textual Data i.e. the news articles (30 points)

Removing the non-letters

Tokenizing the text

Removing stopwords

Lemmatization

4. Encoding and Transforming the data (20 points)

Encoding the target variable

Bag of Words

TF-IDF

Train-Test Split

5. Model Training & Evaluation (30 points)

Simple Approach

Naive Bayes

Functionalized Code (Optional)

Decision Tree

Nearest Neighbors

Random Forest

Questionnaire:

How many news articles are present in the dataset that we have?

Most of the news articles are from _____ category.

Only ___ no. of articles belong to the ‘Technology’ category.

What are Stop Words and why should they be removed from the text data?

Explain the difference between Stemming and Lemmatization.

Which of the techniques Bag of Words or TF-IDF is considered to be more efficient than the other?

What’s the shape of train & test data sets after performing a 75:25 split.

Which of the following is found to be the best performing model..

a. Random Forest b. Nearest Neighbors c. Naive Bayes

According to this particular use case, both precision and recall are equally important. (T/F)

