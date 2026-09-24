# Python-DA-Assignment-2
Project Title:Data Visualizations
Project overview:Taxi services generate large amount of trip data everyday.Analyzing this data can help identify travel patterns and fare behaviour.

## Description
In this project,taxi trip data is cleaned,analyzed and visualized using Python,Pandas,Matplotlib and Seaborn.The analysis focuses on handling missing values,exploring numerical and categorical variables and identifying meaningful patterns in taxi trips.
Objectives:
*Clean and preprocess the taxi trip dataset using Pandas.
*Identify and handle missing values.
*Explore the distribution of important numerical variables
*Analyze relationships between distance,fare,tip and other trip-based datas
*Identify potential outliers in the dataset
*Create meaningful visualizations using matplotlib and Seaborn
*Derive useful insights from analyzed data

Tools and Technologies:
Python,Pandas(data cleaning and analysis),Matplotlib(Data visualization),Seaborn(Statistical visualization),Jupyter Notebook/Google Colab

Data Cleaning:
*Checking dataset structure and data types
*Handling missing values where required
*Preparing cleaned data for visualizations

Exploratory Data Analysis:
The following visualizations were created to undrstand taxi trip data:
*Using matplotlib:
1.Line Chart:Used to visualize fare over pickup time
2.Bar Chart:Used to show total fare for each pickup borough
3.Pie chart:It shows ditribution of trips for different payment methods
4.Histogram:Used to visualize distribution of distance
5.Box Plot:Used to compare tip amounts across pickup boroughs
*Using Seaborn:
6.Count Plot:used to show number of trips for each pickup borough
7.Scatter plot:shows relationship between distance and fare based on pickup borough
8.Heatmap:Using correlation matrix,visualizes relations between distance,fare,tip,tolls and total(numerical variables)
9.Pair Plot:to visualize pairwise relations between distance,fare,tip,total according to the pickup zone
10.Violin Plot:It shows distribution of fare for each payment method

Key Insights:
*Short distance taxi trips occur frequently than longer trips
*Fare generally increases with increasing trip distance
*Correlation analysis helps to identify relationships among numerical variables
*fare distributions differ across payment methods
*Most of the observations fall within normal range, with only few outliers

Conclusion:
This project demonstrates the use of Python,Pandas,Matplotlib and Seaborn for cleaning,visualizing real-world taxi trip data.The project also demonstrates fundamental Exploratory Data Analysis(EDA)which is required for a Data Analyst 

## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]()
* 0.1
    * Initial Release

## License

This project is licensed under the [Mythili.V] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* [dbader](https://github.com/dbader/readme-template)
* [zenorocha](https://gist.github.com/zenorocha/4526327)
* [fvcproductions](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46)
