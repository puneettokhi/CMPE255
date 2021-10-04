# College Major Analysis based on economical factors
# CMPE 255  
# Professor Carlos Rojas

## Authors
Puneet Tokhi: @puneettokhi

Sai Kapadekar: @

Shivang Patel: @Shivang-Patel

Aaryaneil Nimbalkar: @aaryaneil

# Questions
## 1. Project title?
College Major Analysis based on economical factors

## 2. What data you’ll use and where you’ll get it?
https://github.com/fivethirtyeight/data/blob/master/college-majors/all-ages.csv
https://github.com/fivethirtyeight/data/blob/master/college-majors/grad-students.csv
https://github.com/fivethirtyeight/data/blob/master/college-majors/majors-list.csv
https://github.com/fivethirtyeight/data/blob/master/college-majors/recent-grads.csv
https://github.com/fivethirtyeight/data/blob/master/college-majors/women-stem.csv

## 3. Description of the problem you’ll solve or the question you’ll investigate.
Many students after high school have either a vague idea about their college major or they enter college with an undeclared major. Most of the students don’t have any idea about the prospective high-paying careers and end up settling for jobs that don’t require a college degree. Investing in a college degree has to be both fruitful and viable for the students because the economical factor is as important as the desire to pursue their field of interest.

There are multiple factors to consider like the employment ratio in that field, the number of job opportunities, and the median pay. This will help students to better understand and have a clear vision of their future goals. It will also help students in taking an informed decision about their future.

By analyzing the data on college majors, employment, and gender diversity, our goal is to provide a data model that can help students and parents choose a college major and understand how big a financial difference it makes.  

## 4. Potential methods you will consider apply (these can change as you play with the data).
To solve this problem, we have considered applying the data mining techniques of clustering and decision trees as the primary techniques for the project. Clustering can be useful in forming clusters of majors that fall within the defined salary ranges. With the help of classifications and decision trees, a major could be determined as economic or not. Other possible techniques which can be considered after starting the initial implementation and if time permits are Classification, Linear Regression, Outlier detection, and Association. We also consider using the random forest classifier technique which is a classification algorithm consisting of many decision trees. 

## 5. How will you measure success?
For this project, Decision Trees could be used as a measure to determine success. The number of correct predictions made is divided by the total number of predictions made to measure the success rate. Clustering could also be used to determine success as based on our algorithm we will validate whether the clusters formed according to the salary ranges are well-formed or not. We are going to use a confusion matrix to have an idea of the accuracy of our algorithm.
