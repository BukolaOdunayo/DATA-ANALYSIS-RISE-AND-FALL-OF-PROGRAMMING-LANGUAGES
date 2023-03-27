# EXPLORATORY DATA ANALYSIS IN R : Analyzing the relative popularity of programming languages over time based on Stack Overflow data.

![stackoverflow-1](https://user-images.githubusercontent.com/105368173/228001250-b932b334-7592-4082-a8bd-2b7532f69888.png)

I carried out exploratory data analysis to discover the programming languages and technologies that are used by the most people? Also what languages are growing and which are shrinking, so that we can tell which are most worth investing time in?
 
 ## ABOUT THE DATASET
I used open data from the Stack Exchange Data Explorer to examine the relative popularity of languages like R, Python, Java and Javascript have changed over time. The data set was stored in two CSV files namely stack_overfow_data.csv and by_year_tag.csv. The dataset has 4 columns each namely

year: The year the question was asked.

tag: A word or phrase that describes the topic of the question.

number: The number of questions with a certain tag in that year.

year_total: The total number of questions asked in that year.

Stack Overflow is an excellent source of data, it is a programming question and answer site with more than 16 million questions on programming topics. By measuring the number of questions about each technology, I got an approximate sense of how many people are using it. Each Stack Overflow question has a tag, which marks a question to describe its topic or technology. For instance, there's a tag for languages like R or Python, and for packages like ggplot2 or pandas.

# DATA ANALYSIS AND VISUALIZATION
This section is focused on uncovering insights from the data and answering the business questions. After loading both csv files into the workspace I was able to 
analyse and visualize the insights belows:

1 What fraction of the total number of question asked in 2019 had the R tag ? 

Answer: 0.9657

2 What fraction of the total number of question asked in 2019 had the Python tag ? 

Answer: 4.3278

3 What were the 5 most asked about tags between 2015-2020 ?

Answer: Javascript, Java, Python, php, and Andriod in descending order.

4 How has R programming language changed in popularity over time ? 

Answer: R has been growing pretty fast in the last decade, it is yet to see a decline in popularity

5 How has ggplot2 and dplyr changed over time? 

Answer: ggplot2 and dplyr are both growing in popularity but not on the same pace as R

6 What are the most asked about tags? 

Answer: Javascript, Java, Python, php, and Andriod in descending order.

7 How has the large programming languages changed over time?

Answer: The six largest programming languages which include Javascript, Java, Python, php,Andriod and c# in descending order was visualized to examine how they  changeg in popularity over time. The graph shows that Javascript, Java, php, and C# started out growing in popularity but began to shrink or decline over time, while python has been growing rapidly without decline.

8 How has the 3 big mobile operating system (Andriod,IOS, and Windows phone) compared  in popularity over time?

Answer:  Android experienced a rapid growth between 2007 and 2012 after which it started declining, IOS experienced growth between 2007-2012 and started declining afterward, Windows phone on the other hand has been static over the years.

# CONCLUSION
Performing exploratory data analysis on the dataset helped me uncover valuable insight from the dataset,using statistical graphs and graphical visualization methods to analyze and investigate the datasets I was able to answer the business questions.

# CREDITS
This project is available on Datacamp as a guided and unguided project I completed both and merged it together.The guided project was created by David Robinson, while the unguided project was created by Sarah Billen. For the guided project I Followed step-by-step tasks to solve the problems/answer the business questions as provided by the creator,I received helpful feedback as I applied my skills to reach the solution. For the unguided project I Solved open-ended data science problems without step-by-step tasks. 
