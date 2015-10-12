# NetApp

Brian McKean from NetApp presented to the class a data analysis problem he'd
like to get some help on.

# Overview

Listen to his presentation carefully. Write down the answers to the following
questions to show your team's understanding of the basics of the problem.

## What is the problem?

How is the systems expected to report the data? In daily, weekly, monthly, eyarly period? Other?
## Why is the problem importnat?
Determining the correct ASUP timing so the customer doesn't have any interruptions in service

## What dataset has been made available?
netapp.csv 

## What specific questions are being raised?
What is considered a "good" and "bad" delta time?

# Q/A session

We will run a Q/A session. Before the session, compile a list of questions you
want to ask. Then, teams will take turn to ask Brian follow up questions.
Each team gets to ask one question each time. Write down the questions your team
wanted to ask and the answers you received. If another team happens to ask the
same question, simply write down the answer you heard.

## How is the information being reported from the system?
Statistics are supposed to be sent every 24 hours. Pull of statistcs should reset base time and statistics. Data should report pevious data form the previous 24 hour period. 
## What's the threshold for what's considered good data and bad data?

Most of the day. Don't want to miss periods of high usage. Small delta times are bad, large delta times are bad. 

## Do the number of writes affect the delta times?  

Drive wear is not proportional to the wear of the drives. 

# Approach

Based on the information you've obtained during the Q/A session, come up with
plan how your team will tackle this problem.

## How should the dataset be imported into Tableau?

CSV file

## How should the work be distributed among the team members?

Team members can group up and tackle the larger issues

## What types of charts or visualizations to use to support the answer?

Box and whisker plot, bar chart, pie chart
## What questions may be too complex for Tableau and may require custom scripts to be written?

Serial numbers since there are all different serial numbers, may be too much data to visualize the complete data set
