# Collaborative-and-Content-based-Approach-for-Movie-Recommendation-System

Welcome to the Collaborative and Content-based Movie Recommendation System repository!

## Overview

This repository contains the code and resources for building a movie recommendation system. We have used the MovieLens dataset for this project.

## Dataset

### Types of Datasets

1. **The Full Dataset**: This dataset comprises 26,000,000 ratings and 750,000 tag applications applied to 45,000 movies by 270,000 users. It also includes tag genome data with 12 million relevance scores across 1,100 tags.

2. **The Small Dataset**: This dataset consists of 100,000 ratings and 1,300 tag applications applied to 9,000 movies by 700 users.

For our recommendation system, we are using the Full Dataset.

### Data Description

The Full Dataset contains 100,004 ratings and 1,296 tag applications across 9,125 movies. These data were created by 671 users between January 09, 1995, and October 16, 2016. This dataset was last generated on October 17, 2016.

Users were randomly selected for inclusion, and all selected users had rated at least 20 movies. No demographic information is included. Each user is represented by an ID, and no other personal information is provided.

The data are contained in the following files:
- credits.csv
- keywords.csv
- links.csv
- links_small.csv
- movies_metadata.csv
- ratings.csv
- ratings_small.csv

## Dependencies

To run the code in this repository, you'll need the following dependencies:

- Python >= 3.5
- pandas
- numpy
- scipy
- scikit-learn
- scikit-surprise
- lightfm
- matplotlib
- seaborn
- jupyter notebook
- jupyter lab
- textblob

## Installing Dependencies

You can install the dependencies using the following commands:

```bash
$ sudo pip install nltk
$ sudo pip install numpy
$ sudo pip install scipy
$ sudo pip install -U scikit-learn
$ sudo pip install scikit-surprise
$ sudo pip install pandas
$ sudo apt-get install libfreetype6-dev libpng-dev
$ sudo pip install matplotlib
$ sudo pip install seaborn
$ sudo apt-get -y install ipython ipython-notebook
$ sudo -H pip install jupyter
$ sudo pip install jupyterlab
$ sudo pip install textblob


