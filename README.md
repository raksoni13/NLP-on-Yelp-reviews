# NLP-on-Yelp-reviews
I tried to apply my Pandas, Seaborn and text processing skills to classify yelp reviews in 1 or 5 catagory

a) Explored the data with the help of seaborn's count plot, heatmap and box plot
b) Used corr() from pandas to understand the corelation between attributes such as "funny", "useful", "text length"
c) Used NLTK for a little text processing such as removing punctuations and removing the stop words.
d) Created feature and target variable and split the "original" text data into train and test data
e) Applied countvectorizer to convert text document into tokens
f) Used MultinomialNB from Naive bayes as a classifier
g) Observed results using classification report
h) Repeated above steps with TF-IDF transformer to allocate weights and implementing Pipeline
i) Again did train-test split and applied Count vectorizer, TF-IDF transformer, and MultinomialNB
j) Again obained results with classification report
