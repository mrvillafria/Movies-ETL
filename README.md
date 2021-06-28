# ETL - Extract, Transform, Load

## Overview of Project
For this week's project, we are using the Extract, Transform, Load (ETL) process to create data pipelines. The ETL process moves data from a source to a destination, transforms and cleans the data, and loads the finished data. We'll be using Python and Pandas to analyze the data and perform data wrangling. To store our data, we will be using Postgres SQL. 

### Purpose
The purpose of this week's project was to help Britta, a member of the Amazing Prime video team, create datasets for a hackathon. The hackathon is asking the participants to help predict movie popularity. Amazing Prime's goal is to try to predict if low budget movies will become popular so they can buy the streaming rights at a lower price. The two data sources are movies released since 1990 from Wikipedia and Move Land rating data from Kaggle. The Wikipedia data is stored as a JSON and the Movie Land data is stored as CSVs. We transformed the data from the two data sources into one clean data set and then loaded our data into a SQL table. 