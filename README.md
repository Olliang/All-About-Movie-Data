# What Can You Do with Movie Data?
<br>

## Introduction

Being a movie & tv show enthusiast, I have been intrigued to understand user viewing behavior using data and think about how to provide the right content to the right people from a user's stand point. This repository is a play ground of my data analysis on movie related data. 
<br>
<br>

## Data
1. MovieLens 20M data (https://grouplens.org/datasets/movielens/20m/)

2. MovieLens 1M data(https://grouplens.org/datasets/movielens/1m/)

3. Netflix Prize data on Kaggle (https://www.kaggle.com/netflix-inc/netflix-prize-data)

<br>

## Data Science and Analysis

**1. Exporatory Data Analysis (EDA)**
<br>
<br>
File: `MovieLens_EDA.ipynb` - jupyter notebook that contains the EDA on the MoviLens Dataset
<br>
<br>
**a.** How is the ratingcount distributed across movies released in different years?
<br>
<br>
**b.** How are the ratingcount and usercount distributed across different genre?
<br>
<br>
**c.** What are the popular topics of movies distributed by different rating scores? <br>
<br>
==> Techniques used: NLP analysis and wordcloud visualization
<br>
<br>
<br>
**2. Dashboard Visualization**
<br>
<br>
Business Problem: The number of movies released was growing exponentially from 1880s to 2010s. However, more ratings are seen on the movies released during the year from 1993 to 1996. While there was an exponentially increasing number of movies released after this period, there are exponentially decreasing number of ratings on the newer movies. Is this a natual peak due to the cumulated ratings covering a longer period?  Has the MovieLens Website become less popular after that period? What movies caused this great popularity? Are those ratings mostly positive?
<br>
<br>
File: `Movie Rating Dashboard Analysis.md` - Markdown file recording the storyline of analysis on the MoviLens Data
<br>
<br>
![dashboard v1](https://github.com/Olliang/All-About-Movie-Data/blob/master/images/MovieLens_Dashboard%20v2-4.PNG)

<br>
<br>

**3. Building Recommender System**
<br>
<br>
**a.** Recommender System with Memory-based Collaborative Filtering 
<br>
<br>
File: `Memory_Based_CF.ipynb` - a notebook explaining and showcasing how memory-based collaborative filtering works
<br>
<br>
**b.** Recommender System with Matrix Factorization
<br>
<br>
File: `Matrix_Factorization_CF.ipynb` - a notebook explaining and showcasing how matrix factorization works with SVD algorithm
<br>
<br>
**c.** Content-based Recommender System 
<br>
<br>
File: `Content_based_Filtering.ipynb` - a notebook explaining and showcasing how Content-based Filtering works with TF-IDF algorithm

<br>
<br>

## References:
<br>
https://github.com/adashofdata/nlp-in-python-tutorial <br>
https://github.com/khanhnamle1994/movielens <br>


