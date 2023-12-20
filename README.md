# CSC448 Final - Accidents Prevention & Preparation

Sohail Ahmad, Tanmim Ahmmed, Uzma Kapadia

This project focuses on preventing and preparing for traffic accidents by analyzing various driving conditions.

## Table of Contents
- [The Problem](#the-problem)
- [Dataset](#dataset)
- [Project Goals and Accomplishments](#project-goals-and-accomplishments)
- [Project Organization](#project-organization) (final code link included here)
- [Tanmim's Contributions](#tanmim's-contributions)
- [Sohails's Contributions](#sohail's-contributions)
- [Uzma's Contributions](#uzma's-contributions)

## The Problem
- Given different driving conditions such as the traffic, location or the time/season, it can impact the accident statistics and often increase it
- However, the city is usually not prepared to quickly respond to the increased accidents that can happen due to fluctuations in number of driver on the road or some areas where it might be very accident prone which can block roads and create additional problems for driver
- The increased response time can also affect death rates in accidents
- Here, we want to examine ways to help prevent against or prepare for such conditions

## Dataset
- Data sourced from [NYC Open Data portal for Motor Vehicle Collisions](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95), including extensive details on incidents.
- This dataset is made of of 2.05M rows, 29 columns, with each row showing a motor vehicle collision
- It includes columns for data such as date/time, location, causes, vehicle types, injuries, and fatalities with large volume of data detailing incidents over extensive time periods
- Features granular details suitable for in-depth analysis and real-time updates.


## Project Goals and Accomplishments
The aim of this project is to develop a model for predicting accident likelihood based on region, time, or season to enhance public safety and city planning strategies.

We accomplished this by:
- creating a trained model using the dataset
- Using the model to predict accidents likely to happen based on a given region, day and time
- Expected outcomes include improved emergency response times and strategies to reduce accidents

## Project Organization
- View the [final scripts](https://github.com/uzmakap/CSC448_Final/blob/main/Code/Accident_Analysis.ipynb) for this project
- View the [report](https://github.com/uzmakap/CSC448_Final/blob/main/Project%20Report/CSC448%20final%20report%20Group%206.pdf) for this project to get more in-depths about the model results and visualization analysis
  
- Libraries used for this project include:

### Data Manipulation and Analysis
- **NumPy** (`numpy`): A fundamental package for scientific computing in Python.
- **Pandas** (`pandas`): A powerful data analysis and manipulation library for Python.

### Data Visualization
- **Matplotlib** (`matplotlib.pyplot`): A comprehensive library for creating static, animated, and interactive visualizations in Python.
- **Seaborn** (`seaborn`): A Python visualization library based on Matplotlib that provides a high-level interface for drawing attractive and informative statistical graphics.
- **Folium** (`folium`, `folium.plugins.MarkerCluster`): A Python library used for visualizing geospatial data.

### Interactive Python Display
- **IPython** (`IPython.display.IFrame`): An interactive computing environment for writing and running Python code.

### Machine Learning
- **Scikit-learn** (`sklearn`):
  - Model Selection (`sklearn.model_selection.train_test_split`)
  - Linear Models (`sklearn.linear_model.LinearRegression`, `sklearn.linear_model.LogisticRegression`, `sklearn.linear_model.Perceptron`, `sklearn.linear_model.SGDClassifier`)
  - Tree Models (`sklearn.tree.DecisionTreeRegressor`, `sklearn.tree.DecisionTreeClassifier`)
  - Ensemble Models (`sklearn.ensemble.RandomForestClassifier`)
  - Support Vector Machines (`sklearn.svm.SVC`, `sklearn.svm.LinearSVC`)
  - Neighbors (`sklearn.neighbors.KNeighborsClassifier`)
  - Naive Bayes (`sklearn.naive_bayes.GaussianNB`)
  - Metrics (`sklearn.metrics.mean_squared_error`, `sklearn.metrics.r2_score`, `sklearn.metrics.accuracy_score`, `sklearn.metrics.classification_report`)
  - Preprocessing (`sklearn.preprocessing.StandardScaler`)


## Instructions to run
1. Download a CSV of the dataset.  [NYC Open Data portal for Motor Vehicle Collisions](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95)
2. Clone this project repository
3. Set up a venv and install the python packages listed in "requirements.txt" in the [Code Folder](https://github.com/uzmakap/CSC448_Final/tree/main/Code)
4. Run Accident_Analysis.ipynb file in the [Code Folder](https://github.com/uzmakap/CSC448_Final/tree/main/Code)
5. Run the cells to see the results.
6. To view the interactive map with the accident hotspots run the [top accident locations map](https://github.com/uzmakap/CSC448_Final/blob/main/Code/top_accident_locations_map.html) html file from the downloaded project repository


## Tanmim's Contributions
- Click here to see [Tanmim's code](https://github.com/uzmakap/CSC448_Final/blob/main/Code/Team%20Contributions/Tanmim/Accident_Visualization_Tanmim_Contribution.ipynb)

## Sohail's Contributions
- Click here to see [Sohail's code](https://github.com/uzmakap/CSC448_Final/blob/main/Code/Team%20Contributions/Sohail/Sohail_contributions.ipynb)

## Uzma's Contributions
- Click here to see [Uzma's code](https://github.com/uzmakap/CSC448_Final/blob/main/Code/Team%20Contributions/Uzma/Uzma_Contributions.ipynb)
