# Kickstarting with Excel

## Overview of Project
Kickstarter crowdfunding projects help bring creative ideas into reality. Our analysis of looking at various factors influencing the success of our theater project lead us to believe that a project's success was heavily influced by its launch date and Goal amounts. 


### Purpose
The purpose of this analysis is to look at several crowndfunding projects to provide Lousie with some insight to uncover the relationship between factors influencing the success or failure of a certain project and make an informed decision on the success of the theater project. 

## Analysis and Challenges
Our analysis was primarily focused on the theater/Play category for the US market.
We looked at the outcome of the campaign based on its launch date and goals.


### Analysis of Outcomes Based on Launch Date

### Analysis of Outcomes Based on Goals

### Challenges and Difficulties Encountered
Some of the challenges we faced in our analysis was our start date and end date for our campaigns were in a unix timestamp format which needed some initial formatting before we could start our analysis.

We had extremely values set for some of our goal amounts that caused our dataset to have some outliers. We mostly saw this happening for our failed campaigns. 

## Results

### What are two conclusions you can draw about the Outcomes based on Launch Date?

Based on our analysis of the theater category we can conclude that May/June is the best month for launching a successful kickstarter project and the success rapidly drops towards the end of the year. 

The launch date has very minimal affect on the failure or cancelation of a project and it says pretty consistent throughtout the year. 


### What can you conclude about the Outcomes based on Goals?

Our outcome for success was negatively correlated to the goal amount. Our success rate was the highest when the goal amount was the lowest and as the goal amount kept increasing the success rate kept going down with an exception of a spike at the goal amount of 35000 to 44999.

Similary the outcome for failure was positively correlated to the goal amount. Our failure rate was the lowest when the goat amount was the smallest and as the goal amount kept increasing the failure rate kept going up with it, again with an exception of a spike at the goal amount of 35000 to 44999.

The cancled outcome did not depend on goal amounts at all thus the line stayed flat on the x-axis with no variation.

The sudden spike in both the  successful and failed outcomes leads us to believe that there was some amount of standard deviation from the average in our dataset which is often times an outlier. Using the 1.5 IQR method we know that is the data point is more than that value then we have an outlier. 
In case of our Succesful US kickstarter we se values for our goal column to be greater than 1.5 IQR ( 1.5* 3500 =5250)
Similarly for our failed US kickstarter we see values for our goal column to be greater than 1.5 IQR (1.5 * 8000 = $12000)

The average successful plays project has a project goal 2 times less than failed projects, as well as average pledged amount of almost 10 times more than failed projects.


### What are some limitations of this dataset?

We saw that about 75% of our dataset had projects those were launched in the United States but since we dont have the information on each state where the project was launched, we cannot drill down further to see if certain states had more success rate than the others. 


### What are some other possible tables and/or graphs that we could create?

We could create a graph for success percentage per country to see the top 5 and bottom 5

We could also create a bar chart to look at the success rate for each parent category and then under each category look at the success rate of each subcategory.

We could look at the project duration to see if the lenght of time that the project ran had any relation to its outcome.




