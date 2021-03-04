# Sentiment-Analysis---Amazon-Fine-Food-Reviews

Team Members: Amrita Jose, Asmita Singh, Prateek Chitpur 

The project aims to implement a sentiment analysis system using NLP to interpret language complexities such as context, ambiguity, sarcasm, or irony in user reviews. The dataset being used for this project is the fine food reviews from Amazon. Sentiment analysis would help Amazon customers in making faster and more informed decisions regarding the products. Apart from predicting and analyzing sentiment of reviews using three machine learning models, the project also aims to summarize user reviews to less than 20 words using two summarization techniques to target customer segments who do not wish to read full reviews and require reduced reading time.  Sentiment capture and analysis is done using both machine learning and summarization.


Dataset: -

The selected dataset (.csv file) contains reviews of fine foods from Amazon. The dataset ca be downloaded from the following link: -

https://www.kaggle.com/snap/amazon-fine-food-reviews


Solution Implementation: -

1) Data Preprocessing to handle missing values, duplicate values, redundant data, and adding new variables to the data frame for analysis.
2)Random Under Sampling of the data to ensure even class distribution for better training classification and performance. 
3) Classifying ratings based on positive and negative sentiment 
4) Exploratory analysis to analyze data distribution, word clouds, top products with positive and negative reviews and top products with most helpful and least helpful reviews. 
4)Analyze the subjectivity and polarity of reviews and identify the positive. Negative and neutral reviews and the subjective, objective and averagely subjective reviews.
5) Predicting sentiment by implementing three machine learning models to predict/classify the sentiment of the reviews. Logistic regression, Naïve Bayes and K Nearest Neighbor are implemented and compared to determine the best performing model for predicting sentiment. 
6)Each of the three models are implemented with the data being subjected to two vectorization techniques including Bag of Words and TF-IDF.
7)Evaluate the best model and vectorization approach for better classification accuracy. 
8)Summarize the reviews to less than 20 words using NLTK to enhance reading time for customers. 
9)Identify the positive and negative reviews at product level and capture the sentiment of NLTK generated summaries. 
10)Calculate accuracy of the sentiment captured by the NLTK summaries by comparing it with the sentiment of the original text reviews and calculating its percentage.
11) Steps 8-10 are performed again using Ngrams to compare accuracy of sentiment in Ngrams generated summaries.
12)The two summarization techniques are evaluated to identify the best accuracy in capturing sentiment.


Sample Input and Output: -

For Sentiment Analysis Using Machine Learning:-

Any unseen new data can be fed to the three machine learning models and the sentiment of the input will be predicted accurately as given in the below sample: -

1)Input :-
User Review 1: This is one food that when mixed with their dry food, my dogs will eat every last drop. They love this. Our older dog (just turned 2) needs to be on a grain free diet, so that is what our puppy gets too. I love that this is 95% Turkey and that the dogs really like it.

Output :-
Predicted Sentiment: 1 (Positive)

2)Input: -
User Review 2: My son is on a restricted diet due to allergies and he is very picky. It was hard to find things that he would even try. After tasting one of these cookies he was hooked. Now this is a favorite snack of his.

Output :-
Predicted Sentiment: 1 (Positive)

3)Input: -
User Review 3: This is so frustrating. Where is the nutritional information? They tell you what's not in it, but they don't tell you what is in it. Furthermore, I had to enlarge the image to get that information. What are they trying to hide? Due to their less-than-generous return policy, I would never buy a product from Amazon.com unless I know exactly what I am getting. Ya got that Amazon?!

Output :-
Predicted Sentiment: 0(Negative)

4)Input:-
User Review 4: Followed the directions to a the letter and ended up with a ridiculously sticky mess that had to be thrown out.

Output: -
Predicted Sentiment: 0(Negative)

