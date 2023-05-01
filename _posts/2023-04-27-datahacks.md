---
toc: true
comments: true
layout: post
title: Data Analysis Hacks
description: Data Analysis Hacks 
---

# PANDAS Hacks
- make your own data using your brian, google or chatgpt, should look different than mine.
modify my code or write your own
- output your data other than a bar graph.
- write an 850+ word essay on how pandas, python or irl, affected your life. If AI score below 85%, then -1 grading point
answer the questions below, the more explained the better.
**SEE ESSAY, CODE, AND DATA BELOW**
> https://tanishapatil1234.github.io/test-fastpage-tp/2023/03/21/GDP_vs_CO2.html


Questions
1. What are the two primary data structures in pandas and how do they differ? 
> The two primary data structures in pandas are CSV files and databases. 
2. How do you read a CSV file into a pandas DataFrame?
> import pandas as pd, df = pd.read_csv()
3.  How do you select a single column from a pandas DataFrame?
> df['column_name']
4. How do you filter rows in a pandas DataFrame based on a condition?
> You can use a conditional like an if/else statement and do: df['Column'].apply(conditional_function). You can also use df[df['Column'] >= integer]
5.  How do you group rows in a pandas DataFrame by a particular column?
> df.groupby('category')['column'].count()
6. How do you aggregate data in a pandas DataFrame using functions like sum and mean?
> df.groupby('category')['column'].mean()
7.  How do you handle missing values in a pandas DataFrame?
> You can upload the csv file into a sqlite database and create a cursor and then use cursor.execute("DELETE FROM table WHERE column IS NULL")
8. How do you merge two pandas DataFrames together?
> merged_df = pd.merge(df1, df2, on='key')
9. How do you export a pandas DataFrame to a CSV file?
> df.to_csv('data.csv', index=False)
10. What is the difference between a Series and a DataFrame in Pandas?
> Dataframe is the entire table whereas the series is the column in the table. 

# NUMPY HACKS
[CLICK HERE](https://tanishapatil1234.github.io/test-fastpage-tp/2022/04/23/numpyhacks.html)

# DATA ANALYSIS AND PREDICTIVE ANALYSIS Hacks
1. How can Numpy and Pandas be used to preprocess data for predictive analysis?
> Numpy and Pandas can be used for data cleaning, normalization, standardization, and data transformation to preprocess data for predictive analysis.
3. Can you explain the process of building a handwriting recognition system using TensorFlow?
> Collecting and preprocessing the data of different letters in handwriting, then using training data in an ANN, testing the data , making appropriate fixes
5. What machine learning algorithms can be used for predictive analysis, and how do they differ?
> ML algos such as linear regression, decision trees, and neural networks can be used for predictive analysis and differ in their approach.
7. Can you discuss some real-world applications of predictive analysis in different industries?
> Twitter uses predictive analysis and ML to monitor the content on the app, and detect trends
9. How can Numpy and Pandas be used to manipulate and filter data for more accurate predictions?
> Numpy and Pandas can do mathematical operations such as averages to evaluate data and make it more scalable. 
11. What are some challenges associated with handwriting recognition, and how can they be overcome?
> Variability in handwriting can be a challenge for the algorithm. A way to overcome it is to use a variety of training data.
13. Can you explain the role of feature engineering in predictive analysis, and how it can improve model accuracy?
> Feature engineering involves selecting the relevant parts of data. It is important to use relevant data when creative predictive analysis models. 
15. How can machine learning models be deployed in real-time applications for predictive analysis?
> Machine learning models can be used and deployed using Flask, Django. 
17. Can you discuss some limitations of Numpy and Pandas, and when it might be necessary to use other data analysis tools?
> One limitation I have come across is the lack of ability to handle very large data sets or iterate through complex, multidimensional datasets. 
19. How can predictive analysis be used to improve decision-making and optimize business processes?
> Predictive analysis can help with identifying consumer trends, market behavior, and more processes which can help with the decision making process of the buisness's operations.

# TENSORFLOW Hacks
> A personal project I did recently
[CLICK HERE](https://github.com/tanishapatil1234/sourcecode-repo/blob/master/_notebooks/2023-04-02-Breast_Cancer_LR.ipynb)
