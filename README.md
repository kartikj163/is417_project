## Financial Market Analytics using Machine Learning and Natural Language processing

The purpose of the project is to use machine learning and natural language processing techniques to analyze the financial market index of DJIA (Dow Jones Industrial Average) that consists of only 30 major companies traded on the NYSE and NASDAQ such as Apple, Microsoft, Nike, etc. We also analyze news headlines from social media pages on international affairs over the same period to anticipate the index movement.

Question: When it comes to delivering the correct frame of speech, social media can be deceitful at times. Is it possible that news stories and headlines on social media have an impact on the overall market movement (in our case DJIA)?

The news headlines and stories from a given day will be used to predict the difference in the closing price of that day, and the opening price of the following day. This enables us to incorporate all the major headlines of a particular day and see the impact it has on DJIA the next day.

Workflow
We would like to use different NLP methods. 
1) Bag of words - to extract features from news headlines for modeling, 
2) CountVectorizer - to convert a given headline into a vector based on frequency, 
3) The n-gram model - to determine if the model's prediction accuracy improves or not,
4) Latent Dirichlet allocation topic modeling - to categorize news texts in certain topics to a document. 

We use supervised classification algorithms like Naive Bayes, Random Forest, Logistic Regression, and Support Vector Machines to anticipate the stock price movement and compare the accuracy of different models. In addition, we will also develop data visualizations with wordcloud and matplotlib to offer a clear understanding of what the data means by putting it in context with graphs.
