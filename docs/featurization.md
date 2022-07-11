# featurization stage

```python
from sklearn.feature_extraction.text import CountVectorizer

max_features = 4
ngrams = 2 # tri gram

vectorizer = CountVectorizer(max_features=max_features, ngram_range=(1, ngrams))
X = vectorizer.fit_transform(corpus)
print(X.toarray())
print(vectorizer.get_feature_names_out())
```

We get the data extracted from the data.xml as split into two sets train and test. Header are PID, Tag(Python) and Title + Body.
Then we convert it into dataframe and apply feature extraction from this above code showm using Sklearn Feature extraction. 