Title: BigQuery Querrying for Stack Overflow

Description: The python file runs a query of a stack overflow dataset and takes the first 100 rows and pulls the tags along with total questions, average scores, average views, unanswered quesstions, average answers, and two new rows unanswered score and engagement score. It then stores this information in a csv file.

How to Run: Download files, make sure everything in requirements.txt is downloaded and connected to your python file, run the program and it should work. 

Pipeline Architecture: Function query is implemented only to run the query, transform actually fixes the data into rows and columns organized according to tags and their data, load then saves this information into an actual file, and main runs everything together. 

Question 1: The tag, "npm", has the highest engagement_score(1.27). That does not surprise me, because npm is globally known since it is almost essential for Javascript users. So many people know Javascript and it makes sense that npm would be right up there for also being so well known. Another reason for this statistic is that there are less questions asked about npm than some other tags which could help boost the score if lots of these questions have engagement.

Question 2: Windows has the highest percentage of unanswered questions(36.04%). I think a big reason for this is that a windows tag is most likely going to contain questions that are less programming based, which is what stack overflow is for, and more just overall computer based, could be hardware or anything else windows related. That could be a big reason as to why people may not have a direct answer to those windows questions.

Question 3: Querying BigQuery is different from querying a local CSV file because when you query from BigQuery, the data is already structured in a way that makes it much easier to pull apart and you also are using Google's technology for storage and file management. Overall, BigQuery is much more organized than a local file.

Question 4: If I were a Developer Advocate or Product Manager at Stack Overflow, I would use these results to implement features that may decrease engagement scores, like an AI assistant that can answer questions before they are posted, helping those who want to post questions that may not have much engagement get an answer before posting them.  I think adding communities, instead of just tags, where people can socialize easier and have their questions answered quicker would also be a great implementation.

