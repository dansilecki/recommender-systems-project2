# Project 1 -  Content-based recommender

### Project description
The aim of this project was to create a content-based recommender for real data from hotel. The Recommender predicted for each user the most likely characteristics of a hotel stay, such as the season, the number of people and the number of days.

- The original data was completely raw, so in the first file <code>project_1_data_preparation</code> basic data preprocessing had to be done. Firstly data such as the hashed name and phone number were deleted and after further filtering, the values from the most important features were aggregated into buckets.

- Once the data had been properly prepared in <code>project_1_recommender_and_evaluation</code> file, it was necessary to define user and item features based on reservations. The next step was the content-based recommender itself, tuning of the recommender and eventually final evaluation.

#### User and item features
To represent features for each user and item, I have grouped all interactions for them and selected the most common values in each feature. Then one-hot encoding was used, so as a result I obtained a vector with a length of 25.

### Archieved results
![Recommender results in comparison with Amazon Recommender](img/results.PNG?raw=true "Results in comparison with Amazon Recommender") <br>
These results were obtained with the Linear Regression Recommender with the parameters selected by the previous tuning of the recommender.

### Requirements to run
<pre>
- Python 3
- pip install pandas
- pip install numpy
- pip install seaborn
- pip install collections
- pip install matplotlib
- pip install hyperopt
- pip install scikit-learn
- pip install jupyter
</pre>
