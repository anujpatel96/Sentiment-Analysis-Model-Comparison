# Sentiment-Analysis-Model-Comparison
Sentiment analysis is the interpretation and classification of emotions (positive, negative and neutral) within text data using text analysistechniques.Sentiment analysis allows businesses to identify customer sentimenttoward products, brands or services in online conversations and feedback. The dataset has Phrases which are the movie reviews given by
different people and it has also respective Sentiments for those reviews.

The dataset we used has five classes.
Positive
Negative
Somewhat Positive
Somewhat negative
Neutral
The Data exploration and visualization, Data prepossessing and Vectorizationare same of each model. After the verctorization part I split the data into training and testing- 80 percentage training and 20 percentage testing. After that I built three different models.The results are obtainedby running 50 epochs for each model and the training time we got is in seconds. It is clearly visible in the table that CNN model outperformed its counter parts in every aspects. The training time is low in compare to rest of two and the
accuracy is remarkably high than LSTM and RNN.

Model   Accuracy  Loss    Training-Time(seconds)
LSTM    0.7188    0.6702  4750
RNN     0.5650    1.081   3973
CNN     0.9263    0.1670  2300
