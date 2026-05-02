# Movie Recommendation System

## Team Members

* Charvi Parashar

## Project Overview

This project builds a movie recommendation system using the CiaoDVD dataset. The goal is to explore user-movie rating data, build recommendation models, and compare their performance using RMSE and MAE.

## Dataset

* movie-ratings.txt (main dataset)
* trusts.txt (bonus dataset)

## Models

* Global Average
* User-Based Collaborative Filtering
* SVD (Matrix Factorization)

## Results

* Global Avg → RMSE: 1.0821, MAE: 0.8351
* User-CF → RMSE: 1.0839, MAE: 0.8200
* SVD → RMSE: 0.9548, MAE: 0.7378
* Trust-Based → RMSE: 1.0820, MAE: 0.8351

SVD performed the best.

## How to Run

Install libraries:
pip install pandas numpy matplotlib seaborn scikit-learn scikit-surprise

Open:
notebooks/eda.ipynb
