# netflix_movies_analysis
Netflix a well-known streaming service has an extensive collection of films, TV programs, and original content. The information consists of contents that the platform established between 2008 and 2021. The earliest content dated back in 1925 and most recent one is 2021.

###	Data Processing
First of all, the necessary python libraries must be imported such as matplotlib, seaborn, pandas and numpy

Importing the netflix dataset

Checking the data has any null values or not.
 
Checking if the data types are correct or not
 
 
It is observed that date is in object type
 
 
It can be observed that date format has been changed.
For further processing, data cleaning should be performed
 
A subset of dataset is created.
 
Here, in duration of movie subset dataframe min is removed and turned it into an integer.
 
 
Changing listed_in column into list to normalize the data and stored as another dataframe. 
 
4.	Data Analysis
 
First, the dataset is visualized to analyze how many movies and tv-shows 
 
Here, we can see the relation between duration and year where movies were released. It can be seen that the duration of some movies has been increasing as year passed. 
 
The pie chart illustrates the number of movies released under the streaming platform.
 
The number of movies released in 2020-21 and different genres. 
5.	Pros and Cons
Matplotlib
Pros
•	It offers numerous ways to generate excellent visualizations.
•	It has the ability to generate simple as well as complex visualizations.
•	It can be used with libraries such as pandas and numpy.
•	It has community support and documentations.
•	It can handle large datasets.
Cons
•	It can be challenging for beginners to learn who are inexperienced with programming.
•	It can take a lot of coding to produce complex visualization.
•	Some features or functions are removed or changed with release of newer version.
Seaborn
Pros
•	It can be used for advanced statistical visualization.
•	It is based on matplotlib so it can be switched between two libraries while being used.
•	It can generate visually pleasing plots.
Cons
•	It is less flexible compared to Matplotlib.
•	Doesn’t have community support and used less than Matplotlib.
•	For larger dataset, rendering of the plots can take a lot of time.
Reference
Matplotlib Documentation <https://matplotlib.org/stable/index.html >
Seaborn Documentation <https://seaborn.pydata.org/>

