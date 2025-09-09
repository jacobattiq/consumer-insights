# Who Actually Uses Coupons?

Consumer insights is a big reason why companies perform data analysis. With that being said, here a is project I whipped up on SQL to show how customers used promo codes. 
Uncovering trends using data is one of my favorite aspects of being a Data Analyst. In light of that, I wanted to do a quick project using SQL. Please let me know your thoughts and any feedback is appreciated! 

## The Goal:
The goal of this project was to compare coupon usage when buying products. Specifically, I wanted to see who males vs females compare and if their age and location (state) had an impact. 

## Hypothesis:
Being a male living in California who is his mid-twenties, I find myself to be a frequent coupon user. You won't see me cutting any out of the paper, but I will search for first-time buyer promos and even signup for reward cards - if necessary. 

However, I believe males ages 41-50 who reside in California will have the highest percentage of coupon usage. 

## Steps I Took:
Understand the Data - Sorted by age, gender, type of clothing etc.
Making a Hypothesis - As seen in 'Hypothesis' section right above
Start Analyzing (the fun part) - Import data from Excel to SQL and ran queries to get desired outcome. 
Present Findings - Which you are reading right now, thank you so much if you had it this far!

Technical Data Stuff (SQL):
This may or may not look like a lot of gibberish depending on your understanding of SQL but let me break it down. Directly under is a screenshot of SQL. I wrote a query to group ages together. What you are seeing is the query I used to make sed age groups. 

<img width="412" height="256" alt="Technical Data Query " src="https://github.com/user-attachments/assets/2d7bfd81-7b2e-44c0-9284-2d78a65938db" />


Query I used to create age groups.
If the last query didn't overwhelm you a bit, than this one may. However, I discovered something about this dataset that blew my mind. I wrote the first query at the top of screenshot just to confirm my findings.

What I found was, per the dataset, there were no females in any age group or state that used promo codes. Only males used promos codes. I even went a step further and went into the raw excel file to confirm (just to make sure I did't make a mistake while importing the data to SQL). The results were the same thought. 

In light of this finding, I decided to only run the data on males, thus the bottom query is using the same age groups but filtered only to show males. See, that wasn't so bad!

<img width="826" height="492" alt="no female promos pic" src="https://github.com/user-attachments/assets/43e14594-541c-4e6f-80b1-a7f77c1c5823" />

Article content
Females did not use promos, only males.
Alright, we are just about at the end. 

Below is the last query I ran. It shows which location had the highest promo code usage for males, sorted by age groups.

The results, surprisingly, Utah had the highest percentage of coupon usage for males. Even more surprising, all age groups, regardless of their location had equal usage. For example, all age groups of men in Utah had 75% usage rate. I even doubled checked my work with ChatGPT.

<img width="593" height="193" alt="right above conclusion" src="https://github.com/user-attachments/assets/f0217a38-4bf0-437f-81f5-e72632e4e5cd" />

## Conclusion
I found this project to be very enjoyable. I like working with SQL a lot and its always nice to keep the skills fresh in my mind. 

What I can take away from this project is to always double check you dataset. The cleaning you will do in the beginning will set the tone for the rest of the project! 

Thank you so much for reading and I hope everyone has a great day! 
