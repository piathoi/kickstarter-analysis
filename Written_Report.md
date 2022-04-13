# Outcome based on Goals and Outcome based on Launched Date

## Overview: this project is created to analyze the relationship between Outcome versus Goals as well as Outcome versus Launched Date. Using several techniques such as pivot table and functions like countifs(), sum() and round() to generate graphs for client.

### Purpose
Using graphs based on the data to provide a better understanding for client. Based on the graphs, client can determine what needs to improve and/or what can be done to reach the highest goal.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
 
For the successful campaigns, the line punctual a little bit for the first few months from Jan to March. There is a significant increase from March to May, and starts decrease significantly from May to the end of the year, even though there is a small increase from Sep to Oct. 
For the failed campaigns, the line mimics with the line from the successful campaigns where it increases and starts slowly decreases. 
For the canceled campaigns, it also mimics with the line from the successful campaigns.

### Analysis of Outcomes Based on Goals
![Theater Outcomes_vs_Launch](Resources/Theater_Outcoms_vs_Launch.png)
For the successful campaigns, the percentage of success declines from the smallest goal to around $29,999. From $25,000 to $35,000, there is small increase and stables until $44,999, it begins to decline. 
For the failed campaigns, the percentage increased significantly between the smallest goal to around $29,000, and then thereÕs a small decline going from $29,000 until $39,000, it hovers to 44,999 and then increases again.
For the canceled campaigns, the line is flat since there is no canceled campaign in the Play Subcategory club.

### Challenges and Difficulties Encountered
There were no challenges or difficulties. However, any database can have its problem. For example, to split from Category to Parent Category and Subcategory, the data should be the same. In this case, we do. In a less perfect world, some might not be written the same and therefore, making it difficult to split it.    

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
The three lines mimic each other.
The people who participated in these campaigns, regardless of the outcome such as failed or success, is significantly higher during springtime, particularly from March to May. The more people participate, the more campaigns reach its finished date. 

- What can you conclude about the Outcomes based on Goals?
The Percentage Successful (PS) line and the Percentage Failed (PF) line compliments each other. Whenever the PS line goes up, the PF line goes down; and vice versa. When PS reaches a plague, PF does the same. 

- What are some limitations of this dataset? The limitation is that both graphs donÕt tell the full story. There are too many factors as to indicate why each campaign got its own outcome, whether it is a success or a failure. 

- What are some other possible tables and/or graphs that we could create?
The column chart.
