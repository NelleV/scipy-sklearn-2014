================================================================================
Working on a machine learning challenge with scikit-learn
================================================================================

Instructors: Jake Vanderplas, Nelle Varoquaux

Machine learning has become an indispensable tool for analysing data,
predicting outcomes, classifying objects, learning patterns in a wide range of
domains. Scikit-learn is a toolbox written in Python, built on Numpy and
Scipy. It contains all the necessary bricks for many machine learning
challenges, from facial recognition, to sentiment analysis or patient outcome
prediction.

More and more, companies outsource this problem to data analysists (and geeks)
in the form of challenges. In this talk, we will cover all necessary blocks to
participate in such a challenge using scikit learn, from extracting features
to model selection and validation. Part of the tutorial will be devoted to
participating in a small challenge amongst attendees. It will consist in
doing sentiment analysis on tweets.


This is an intermediate tutorial: we expect attendees to have basic knowledge of Python,
including the use of Numpy and Matplotlib.


Outline
-------

- Installing and running scikit-learn (0:00 - 0:15)
- Representation of data in Machine Learning (0:15 - 1:00)

    - Downloading data within scikit-learn, data structure and visualization
    - Extracting features from a text corpus
    - Exercise: vectorization of tweets.
    
- Basic principles of Machine Learning & the scikit-learn interface (1:00 - 2:00)

    - Classification and regression.
    - Unsupervised Learning: Clustering & Dimensionality Reduction
    - Example: PCA/clustering on the STS-Test dataset
    - Exercise: Linear regression on the STS-Test dataset


- Model selection and validation (2:15 - 3:00)

    - Measuring the goodness of fit using cross validation
    - Using model selection to avoid overfitting.
    - Exercise: Regression on the STS-Test dataset

- Project: participating to a small challenge (3:00 - 4:00)

    - Sentiment analysis on the STS-Test dataset
