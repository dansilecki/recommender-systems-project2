# Project 2 -  Neural Network Recommender 

### Project description
The aim of this project was to create a recommender based on a neural network model for real data from hotel. The Recommender predicted for each user the most likely characteristics of a hotel stay, such as the season, the number of people and the number of days.

- The original data was completely raw, so in the first file <code>project_1_data_preparation</code> basic data preprocessing had to be done. Firstly data such as the hashed name and phone number were deleted and after further filtering, the values from the most important features were aggregated into buckets.

- Once the data had been properly prepared in <code>project_2_recommender_and_evaluation</code> file, it was necessary to define user and item features based on reservations. The next step was the content-based recommender itself, tuning of the recommender and eventually final evaluation.

### Archieved results
![Recommender results in comparison with Amazon and Netflix Recommenders](img/results.PNG?raw=true "Results in comparison with Amazon and Netflix Recommenders") <br>
These results were obtained with the MLP Model with the parameters selected by the previous tuning of the recommender.

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
