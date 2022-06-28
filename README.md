# Spotify-top-songs-analysis

I analyze spotify's top songs by using data mining techniques such as classification and regression. I use decision tree to classify songs' genre, using regression to predict songs' popularity score.

## Datasets
I use two datasets from Kaggle:
1. Spotify - All Time Top 2000s Mega Dataset: https://www.kaggle.com/datasets/iamsumat/spotify-top-2000s-mega-dataset
2. Top Spotify songs from 2010-2019 - BY YEAR: https://www.kaggle.com/datasets/leonardopena/top-spotify-songs-from-20102019-by-year?select=top10s.csv

## Classification songs' genre
### Workflow:
1. Combine two datasets to increase dataset's size.
2. Reduce the number of classes of "Top Genre" variables(from 134 classes to 10 classes).
3. Balance classes of "Top Genre" variable.
4. Transform variable type of "Artist" from categorical to numeric.
5. Build decision tree.
6. Prune tree to reduce overfitting.
7. Visualize tree.


Some research note I took: https://www.notion.so/Spotify-top-songs-analysis-80314ee040734f27849942449297fe37
