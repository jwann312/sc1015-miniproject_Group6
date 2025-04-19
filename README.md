# SC1015-miniproject_Group6

## About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on music streaming services from 
[🎹 Spotify Tracks Dataset](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset) from Kaggle.

For a walkthrough, follow the source code in order from:
1. [Data Extraction and Cleaning](https://github.com/jwann312/sc1015-miniproject_Group6/blob/main/Data%20Extraction%20and%20Cleaning.ipynb)
2. [Exploratory Data Analysis](https://github.com/jwann312/sc1015-miniproject_Group6/blob/main/Exploratory%20Data%20Analysis.ipynb) (As plotly's interactive plot is not supported in Github, do use nbviewer (https://nbviewer.org/) for visualisation of our "average sound features for each genre" plot.)
3. [Song Recommendation System](https://github.com/jwann312/sc1015-miniproject_Group6/blob/main/Song%20Recommendation%20System.ipynb) (As plotly's interactive plot is not supported in Github, do use nbviewer (https://nbviewer.org/) for visualisation of our "PCA visualisation of sound clusters" plot.)


## Contributors
- [bigballernation](https://github.com/bigballernation) (Data Extraction, Data Cleaning, EDA)
- [jwann312](https://github.com/jwann312) (EDA, Song Recommendation Model)
- [freth0](https://github.com/freth0) (KMeans Clustering, Song Recommendation Model)

## Problem Definition
- Are we able to succesfully recommend similar songs to users?
- How well can our model find similar songs, with the variable we chose?

## Models Used
- KMeans Clustering
- Decision Tree Classification


## Conclusion and Takeaways
- We found out that sound features are important for song recommendations, and that duration/runtime surprisingly had a weak correlation with our final model.
- Some clusters were well defined, but some clusters were not due to the similarity in sound features. This was due to limitations in our dataset, which we believe will be improved on when scaled with a larger one.
- We incorporated clustering and finding Euclidean distance to recommend songs of similar sound features, which was successful in accounting for users listening preferences since clustering helps avoid overfitting to only the most similar tracks, which can feel repetitive for users.

## References
- https://www.kaggle.com/code/vatsalmavani/music-recommendation-system-using-spotify-dataset/notebook
- https://www.kaggle.com/code/prashant111/recommender-systems-in-python
- https://www.kaggle.com/code/eishkaran/spotify-music-recommendation-system/notebook
