# NLP
#### Abstract
* Organisations today have a huge and wide variety of data with them to deal with. Like – names, phone numbers, email. In context with the data provided to me, is of a e-commerce website, ‘Flipkart’,  having variety of data like, brand, products, retail price, discount price, description to name a few. 
It takes a lot of effort and time to make this huge data useful. Natural Language Processing is one of the very important skills in extracting information from text data.
Data cleaning and preparation is the most critical first step. It is a process of detecting and correcting/removing the inaccurate records from a database.
Data visualisation is the graphical representation of information and data in the form of graphs, charts. It helps in understanding the pattern in the data and analysing and making data-driven decisions. 

#### Built with
* Jupyter Notebook

#### Dataset
* Flipkart (https://docs.google.com/spreadsheets/d/1pLv0fNE4WHokpJHUIs-FTVnmI9STgog05e658qEON0I/edit?usp=sharing)

#### Objectives
* Show how you would clean and process the data
* Show how you would visualize this data
* Show how you would measure the accuracy of the model
* What ideas do you have to improve the accuracy of the model? What other algorithms would you try?

#### Jupyter notebook Index
* Preprocessing and cleaning of data
* Data preparation & data cleaning
* Data visualization
* Training model and finiding accuracy

#### Libraries uses
- Pandas
- Numpy
- Matplotlib
- seaborn

#### Approach
* The very first thing to do is to import libraries for data preprocessing. Most important python libraries for working on data are Numpy, Matplotlib and pandas.
Numpy  This library is used for all mathematical calculations.
Pandas  This library is used for importing and managing datasets.
Matplotlib  This library is used to make charts.
* Once you have downloaded your data set and named it as a .csv file, you need to load it into a pandas dataframe. Now you can perform some basic cleaning tasks.
* Have spent some time exploring it and understanding what feature each column represents. It is important, to avoid mistakes in data analysis and the modelling process.
* From the visualizations I have observed that there are lot of data missing in the bran column, so I have dropped the brand column to avoid further hurdles while analysing the data.
Then I have performed column study one by one to observe the pattern of data and clean it if required.
* Since product_category_tree consist of categories followed by sub-categories. So, this will be splitted into sub-categories using split() command. I have splitted the product_category_tree into primary, secondary, tertiary and quaternary categories.
* selected few columns from the set of columns, which would be important for me to analyse and train my model on.
Performing cleaning to those selected columns.
* Here I have selected few columns from the set of columns, which would be important for me to analyse and train my model on.
Performing cleaning to those selected columns.
* saved a clean data to the new csv file called preprocessed data.  
* Separating data into training and testing sets is an important part of evaluating data models. By using given data for training and testing, you can reduce the effects of data inconsistency and better understand the feature of the model.
* Feature extraction aims to reduce the number of features in a dataset by creating new features from the existing ones and then disposing the original features. Its importance are:-
1.	Reduces Overfitting: - Less unnecessary data means less opportunity to make decisions based on noise.
2.	Improves accuracy: - Less confusing data means modelling accuracy improves.
3.	Reduces training time: - Less data means that algorithm train faster.

* tf-idf is a statistical measure that evaluate how applicable a word to a document in a collection of document. This is done by multiplying two metrics: how many times a word appears in a document, and the inverse document frequency of a word across a set of documents.
* Logistic regression is used to solve the classification problem, so its called as classification algorithm.
After First run Accuracy is coming out to be 95.0%.
First two predictions are clothing and furniture.

#### Conclusion
* 1.	The data is good enough even small amounts of missing data available.
* 2.	Periodical sales distribution is achieved in years and months.
* 3.	Between December and January much products were sold (People looks more interesting in buying things during New year
* 4.	2015 sales observed higher compared to 2016 sales as per the data available.
* 5.	Automotive, Mobiles & accessories, clothing categories are having highest discounts.
* 6.	Clothing, Jewelery & footwear are the top most sol items.

