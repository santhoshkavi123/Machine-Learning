# Machine-Learning
1.	Scrape this medium article (https://towardsdatascience.com/data-science-and-machine-learning-interview-questions-3f6207cf040b) and create a word cloud to visualize frequently used words 

(Note: Select all paragraphs and join them together as a single string and pass it to python word cloud package)

2.	Using amazon reviews data set do the following
a.	create a corpus using sklearn package. 
b.	Create the Document Term Matrix using unigrams
c.	Identify top 25 unigrams and filter their respective columns from DTM
d.	Using these 25 columns, compute correlation matrix (if possible visualize the same using seaborn heatmap function). 
e.	Using correlation matrix, Identify the pair of unigrams which has the highest correlation value

3.	Using the above Document Term Matrix
a.	Use K-means clustering to cluster the reviews in to four groups
b.	Plot a bar chart to display no. of documents under each group
c.	Create Word cloud for each group

4.	Using imdb movies reviews data set (imdb_sentiment.csv: https://bit.ly/2S2yXEd), create a supervised model to predict the sentiment of user reviews.
a.	Create a word cloud using the user reviews
b.	Use random_state=100 while splitting data in to training (80%) and testing(20%).
c.	Comment if the target variable contains balanced or imbalanced classes (In target variable: 0 = negative, 1 = positive sentiment)
d.	Build various supervised classification models using the training data set
e.	Predict and compute accuracy of the model on test data set
f.	Identify which model is best for sentiment prediction

5.	Identify sentiment for the imdb user reviews using vader package. Comment the performance of supervised vs unsupervised sentiment prediction.

6.	Apply topic modelling to cluster news based on their headlines. Using abcnews.csv (https://github.com/skathirmani/datasets/raw/master/abcnews.csv.zip file, randomly select 10,000 rows. Using multiple iterations, choose appropriate number of topics. Visualize number of documents under each cluster using a bar chart
