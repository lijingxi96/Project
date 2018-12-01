# Project
Group Name: TFA GROUP PROJECT  Section: 001     
Project Name: Rental Analysis
Team Members: Jingxi Li, Xuanyi Jin, Hanxuan Li, Xinran Zhang

# WHAT IS IT ?
This is a project to realize an expressive rental price comparative statistics of four main cities in UK: London, Liverpool, Leeds and Manchester, by defining a class called Rental. It aims to get detailed house rental information by web scraping and complete data cleaning to illustrate them in Data Frame. Most importantly, It is also capable of flexibly visualizing data distribution in bar, pie, line graphs and mapping for better view effect, which can be all realized using OOP class named rental. In addition, this is a program with interaction function, that is to say, users can choose whether or not utilize API to get the center point of 4 cities for mapping. Finally, it can intellectually realize a scatter plot and regression model to show how population factor influences rental pricing level in postcode district. 

# INSTALLATION:
<li>To install requests and bs4 for Web Scraping </li>

![image](https://github.com/lijingxi96/Project/blob/master/p1.jpg)

<li>To better read, clean and visualize data, install pandas; to accomplish further function we use numpy and folium to cooperate with pandas </li>

![image](https://github.com/lijingxi96/Project/blob/master/p2.jpg)

<li>To draw bar charts, line charts and pie charts for analysis, install matplotlib and seaborn.</li>

![image](https://github.com/lijingxi96/Project/blob/master/p3.jpg)


# RUN INSTRUCTIONS:
<li>1. Users need to first import all the libraries shown in the above installation part to allow realize this program’s some functions.
<li>2. For the mapping visualization, users should download all the geojson files containing zip_code information.
<li>3. In the mapping part, if user chooses to use API to get the center point information, you need to input the specific API key. </li>

## Detailed Instructions:
<li>1. Users should run each of the function in Define Functions part, which includes 11 various functions we created to be used later.
<li>2. Users can instantiate different objects for cities in UK using the class called Rental. By using methods we created for this class, users can implement gender_preference_analysis, size_analysis, price_analysis……
<li>3. In the Further Analysis part of our project, we realize to plot the relationship between average rental price and population.

# SOURCE OF DATA (pop_by_zip.csv)
<li> https://www.gov.uk/government/statistical-data-sets
