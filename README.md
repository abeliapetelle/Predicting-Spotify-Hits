# Predicting-Spotify-Hits

## Objective 
Predicting spotify hits using supervised machine learning algorithms 
        
## Context 
Every music producer wants to put the track that has the best chance of becoming a hit at the first posoition of the album.
But how do you know if the song has a chance of becoming a hit?

Music tracks can be analyzed using a large number of parameters such as their key, the level of danceability, the acousticness, they duration, etc. By analyzing these parameters and trying to find the best supervised machine learning model, we can try to predict which tracks have the most potential to become a hit.

## Data 
<img src="https://www.01net.com/i/0/0/92a/a2f743ce5d1441920d9e4828870d0.jpg" width="15%" height="15%">
This is a dataset consisting of features for tracks fetched using Spotify's Web API. I took only the smaller version of it from Kaggle.
The tracks are labeled '1' or '0' ('Hit' or 'No hit') depending on some criterias of the author.

## Process
- Data manipulation
- Exploratory data analysis
- Supervised learning
- Supervised learning with PCA
- Summary

## Method 
As we want to predict which class a track is part of which (hit or no hit), we will use classification algorithms.

## Conclusion

## Built With
* [Python](https://docs.python.org/3/) - The programming language used
* [Pandas](https://pandas.pydata.org/pandas-docs/stable/index.html) - library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language
* [MatPlotLib](https://matplotlib.org/contents.html) - Matplotlib is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms
* [Sklearn](https://scikit-learn.org/stable/) - Sklearn is a machine learning library featuring various classification, regression and clustering algorithms including support vector machines, random forests, gradient boosting and k-means.
* [Seaborn](https://seaborn.pydata.org/index.html) - Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.
* [NumPy](https://numpy.org/) - NumPy is a library adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays. 
* [SciPy](https://www.scipy.org/) - SciPy is an ecosystem of open-source software for mathematics, science, and engineering.

