**Classifying Song Genres from Audio Data**
This project uses Machine Learning Techniques in Python to classify songs based on their genre.

Using a dataset comprised of songs of two music genres (Hip-Hop and Rock), I trained a classifier to distinguish between the two genres based on only on track information derived from Echonest (now part of Spotify). Used pandas and seaborn packages in python for subsetting the data, aggregating information, and creating plots.

Next, I used scikit-learn package to predict whether I can correctly classify a song's genre based on the features. After initial training found that my model was biased because of skewed training and test samples, which I solved by resampling. Although balancing removed bias it had a significant hit on the performance. I was able to achieve final accuracy of 87.5% using Logistic Regression.

**Technologies**
pandas
numpy
seaborn
matplotlib
sklearn

**Dataset**
The dataset we use can be found on kaggle: https://www.kaggle.com/datasets/veronikafilippou/fmarockvshiphop
