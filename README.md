# Indian_Standup_Comedy


## Overview
This project involves a comprehensive analysis of Indian Standup Comedian's data using SQL.
The goal is to extract valuable insights and answer the business question based on the dataset.
The following README.md provide a details account of the project's objective,business problem,
solution,findings,etc.

## Objective

- Comedian popularity and Engagement.
- Trend Analysis.
- Like-to-View and Comment-to-View ratio Analysis
- Content Performance.

## Dataset

The data for this project is sourced from the Kaggle dataset:
 
 **Dataset Link :** [Standup Dataset](https://www.kaggle.com/datasets/ravineesh/indian-standup-comedian)

 ## Schema

```sql


CREATE TABLE create table stand_up_comedians

(
 channel_name varchar(200), 
 video_id varchar(100), 
 video_type varchar(200), 
 video_title VARCHAR(400), 
 view_count INT,  
 like_count INT, 
 dislike_count INT, 
 favoriteCount INT, 
 commentCount INT, 
 publishedAt varchar(100)
) ;
```

