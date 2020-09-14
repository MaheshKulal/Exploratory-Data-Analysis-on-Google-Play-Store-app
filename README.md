
This is an Exploratory Data Analysis of Google Play Store Apps Dataset from Kaggle. I chose this Kaggle data set to visualize some of the trends in apps downloaded by the users. First the dataset was loaded into pandas dataframe. This dataset consists of 10841 rows and 13 columns. . I have used matplotlib and seaborn libraries to visualize the dataset.
 
 Data Cleaning
 
•	The 'Installs' column had '+' sign and so to make this a floating point data type, I removed the '+' and converted the data type to float.
•	The 'Price' column had '$" symbol which I have removed and again converted the data type to float. 
•	The average rating for all the apps is 4.17 which is pretty descent. 
•	From the data, we can see that users tend to install apps which are free and priced between $1 - $30.
