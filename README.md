# PySpark_recommender

The aim of this project is to use pyspark for the implementation of a movies recommender (or recommendation) system.

The data_set we will use is the famous one provided by MoviLens.
We will use the small version to avoid memory limitations on CPU implementations.

Our recommender system will be based on the alternating least squares (ALS) algorithm.

We will train our model and test it using evaluation metrics such as: RMSE, Recall and MAP.

Finally, we will use our model to recommend movies to a new user.


For the implementation of this project, we will use the notebook included in this repository, which structure is as follows:

1) FIRST STEPS:<br>
  1.1) Create Spark Session<br>
  1.2) Import data_sets<br>
2) DATA PREPROCESSING
3) RECOMMENDER SYSTEM<br>
3.1) Data_sets: training, validation and test<br>
3.2) Quick look at the model (ALS)<br>
3.3) Hyperparameters tuning<br>
4) TEST<br>
4.1) RMSE from the test data_set<br>
4.2) Additional metrics: Recall and MAP<br>
5) OUR RECOMMENDER SYSTEM IN ACTION
6) CONCLUSIONS
7) ACKNOWLEDGMENTS

I hope this notebook helps to make PySpark more understandable.
Thank you very much for your time!!!


### Acknowledgment:

This notebook is a personal extension of the post by Jose A. Dianes that you can find on the following link:
https://www.codementor.io/jadianes/building-a-recommender-with-apache-spark-python-example-app-part1-du1083qbw

Some of my contributions consist of:

- Data Prepocessing (see '3.Data Prepocessing' section)
- Showing some functionalities of the ALS from Spark.ml (see '3.2) Quick look at the model (ALS)' section).
- Hyperparameters tuning using a cross_validated grip seach strategy (see '3.3) Hyperparameters tuning' section).
- Additional evaluation metrics (Recall and MAP) for model testing purposes (see '4.2) Additional metrics: Recall and MAP' section).
- Using data_frames (in addition to RDDs) and SQL code.
