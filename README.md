# twitter_sentiment_analysis

This model uses multiple classification model to predict the sentiment, all models are trained on the same data and given a vote weight based on it's accuracy.
all models are already trained and saved as ```.pickle``` in the ```pickled_algos``` folder

  -first run ```twitter.py``` to write realtime sentiment prediction in to file ```twitter-out.txt```
  -then run plot.py to plot sentiment prediction in real time

Because i can not upload files bigger than 100mb
so first time running please uncomment following code
```#featuresets = [(find_features(rev), category) for (rev, category) in documents]```
```#save_featuresets = open("pickled_algos/featuresets.pickle","wb")```
```#pickle.dump(featuresets, save_featuresets)```
```#save_featuresets.close()```

in file ```sentiment_mod.py``` and run it once to create ```featuresets.pickle```

once done you can comment or delete it again
