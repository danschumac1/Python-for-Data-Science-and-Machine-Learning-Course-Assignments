# Python-for-Data-Science-and-Machine-Learning-Course-Assignments
Assignments for https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/
This was my first time taking a Data Science course. I learned so much!

Here is a summary of this repositorie's conents:
1 - Python Crash Course
	
  -splitting strings into words
  -basic math in python
  -using .format()
  -indexing nested lists
  -variable types
  -writing simple functions
    -returning domain name of email
    -checking to see if 'dog' is in string
    -counting the number of times 'dog' is in string
  -lambda functions
    -filtering out words in a string that don't start with 's'
  -if/elif/else
    -caught speeding problem


2 - Numpy
	-import
	-creating arrays
	-creating matrices
	-reshaping matrices
	-creating identity matrices
	-random number generator
	-creating an array of 25 random numbers with a standard normal distribution
	-sums, std, sums columns of an array
	

3 - Pandas 
	01 - Salaries Exercise
		Explores SF Salaries Dataset Kaggle
			-import data
			-What is the average base pay?
			-What was the highest overtime pay?
			-What is the job title of a named employee?
			-What is ^that employees pay?
			-Who are the lowest/highest paid employees?
			-What is the average base pay for each year 2011-2014?
			-What are the unique job titles?
			-What are the top 5 most common job?
			-What job titles only have 1 employee?
			-What people have the word 'Chief' in their job title?
			-What is the correlation between Job Title length and Salary?
	03 - E-Commerce Purchases Exercise
		Explores fake data about Amazon purchases
			-How many columns and rows?
			-What is the average purchase price?
			-What are the max and min purchase prices?
			-How many people chose english as their chosen language?
			-Who are the individuals with the job title 'lawyer'?
			-How many people purchase during AM vs PM??
			-What are the 5 most common job titles?
			-who made a purchase from lot 90? What was the purchase price?
			-What is the email for a person with a given card number?
			-How many people have American Express as their credit card provider and made a purchase above 95$?
			-How many people have a credit card the expires in 2025?
			-What are the top 5 most popular email domains?
	

4 - Matplotlib ##numbers are weird here
	-Creating figures
	-adding axises
	-plotting
	-setting x/y labels
	-setting titles
	-overlapping figures
	-setting x/y limits
	-changing line color, style, and width
	-nrows and ncols
	-adjusting figsize

5 - Seaborn
	-setting style
	-jointplots
	-distplot
	-boxenplot
	-swarmplot
	-countplot
	-heatmap
	-FacetGrid

6 - 

7 - Pandas Built in
	- .scatter()
	- .hist()
	- .style()
	- bins and alpha
	-.plot
		.box()
		.kde()
	-plotting columns
	-area plot of all columns for first 30 rows

8 -

9 - Geographical Plotting
	-create choropleth plot of power consumption by countries
	-create choropleth plot of 2012 election data

10 - Data Capstone Projects
	911 Calls
		Explores Kaggle data base 911 calls for Montgomery County
		-What are the most frequent zip codes?
		-What are the top townships?
		-how many unique title codes are there?
		-create a new column called 'reason' that contains EMS/Traffic/Fire
		-What is the most common reason for a 911 call?
		-countplot by reason
		-convert timestamp into columns 'hour','month','day of week'
		-convert day of week column from number (0-6) to string ('Monday')
		-countplot by month and day of week
		-.count() aggregation
		-plot calls per month
		-create 'Data' column and plot calls
		-plot 911 calls by date for Fire then Traffic then EMS
		-create heatmap of day of week vs time of day for 911 calls
		-create heatmap of month vs day of week for 911 calls
	Finance Project
		Explores historical stock prices of 6 banks from 2006 to 2016
		-use we.DataReader() to pull data from yahoo
		-use pd.concat to concatenate bank dataframes together
		-What was the max clase price for each bank stock?
		-create a new dataframe that contains the returns of each bank's stock.
		-pairplot returns dataframe
		-What was each bank's best and worst single day return?
		-Setting indexes
		-Which stock was riskiest overall? 
		-Which stock was riskiest in 2015?
		-create distplot of 2015 Morgan Stanley returns
		-create distplot for 2008 CitiGroup returns
		-create line plot showing close price for each bank for the entire index of time
		-for one bank at a time?
11 - Linear Regression
	Part 1 - Explores artificial housing data that compares avg area income, avg area house age etc to price
	-Exploratory Data Analysis
	-Create heatmap of correlated numerical data
	-Separating data into X(columns - label) and y(label)
	-Train_test_split
	-Make a linear regression model
	-Fit model to data
	-find coefficients per X column
	-mean absolute error
	-Mean squared error
	

12 - 

13 - Logistic Regression
	Explores Fake data set which indicates whether a user clicked on the age of the person etc.
	-Exploratory Data analysis
	-X y split
	-Make a logistical regression model
	-do a classification report

14 - K Nearest Neighbors

15 - Decision Trees and Random Forests

16 - 

17 - K Means Clustering
	Use K means clustering to determine whether a university is public or private
	-import data
	-reset index
	-Exploratory data analysis
	-create kmeans model
	-get dummy variables for private vs public
	-confusion matrix & classification report

18 - Principal Component Analysis
	-using a database about breast cancer tumors, find the variables that most correlate to the tumor being benign or malignant.

19 - Recommender Systems
	Explores a database of movie reviews on a 5 star scale
	-What movies are the highest rated?
	-What are the most rated?
	-plot rating vs number of ratings
	-use pivot table to make matrix
		-index is the user_id
		-columns are all of the individual movies
	-recommend similar movies with .corrwith()
		-filter out movies with less than 100 ratings
20 - Natural Language Processing
	Classifies Yelp Reviews into 1 star or 5 star categories based off the text content in the review
	Use lambda expressions and .split() to separate reviews into individual words
	Feature engineer a review length column
	Exploratory data analysis
	Redefine the dataframe to disclude 2-4 star rating reviews
	Import,create and fit a CountVectorizer object
	Train test split
	Train and fit model (MultinomialNB)
	View classification and confusion matrix
	
	Using pipeline

21 - Big Data and Spark

22 - Deep Learning
	Given historical data on loans given out with information on whether or not the borrower defaulted (charge-off), can we build a model that can predict whether or not a borrower will pay back their loan? This way in the future when we get a new potential customer we can assess whether or not they are likely to pay back the loan.
	
-exploratory data analysis
-zooming in on plots
-cleaning data
  -getting rid of redundancy
  -getting rid of missing data
  -filling missing data based on another columns data
-reordering plots
-creating dummy variables
-feature engineering
-train_test_split, set variables
-Normalize the data
-Creating a model
-Saving the model
-evaluate the models performance
-Given a customer, would you give them a loan?


