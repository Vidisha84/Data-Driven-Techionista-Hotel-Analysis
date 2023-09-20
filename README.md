# Data-Driven-Techionista-Hotel-Analysis
## Overview
This repository contains a detailed analysis of hotel reviews from Techionista Holidays, dated from 2015 to 2017, focusing on various aspects such as nationalities, traveler types, and hotel locations. This project is dedicated to analyzing 515,000 records related to holiday trends.This dataset contains 515,000 customer reviews
and scoring of 1493 luxury hotels across Europe.


![Overview](https://github.com/Vidisha84/Data-Driven-Techionista-Hotel-Analysis/blob/main/1.jpg)

## Objective

The main goal is to create a comprehensive dashboard that provides insights into different types of travelers and their feedback. This information can be used to improve Techionista's Holidays website, catering to user needs more effectively.

## Dataset
1. Hotel_Address: Address of hotel.
2. Review_Date: Date when reviewer posted the corresponding review.
3. Average_Score: Average score of the hotel, calculated based on the latest comment in the last year.
4.Hotel_Name: Name of hotel
5.Reviewer_Nationality: Nationality of reviewer
6.Negative_Review: Negative review the reviewer gave to the hotel. If the reviewer does not give the negative review, then it should be:'No Negative'
7.Review_Total_Negative_Word_Counts: Total number of words in the negative review.
8.Positive_Review: Positive review the reviewer gave to the hotel. If the reviewer does not give the positive review, then it should be: 'No Positive'
9.Review_Total_Positive_Word_Counts: Total number of words in the positive review.
10.Reviewer_Score: Score the reviewer has given to the hotel, based on his/her experience
11.Total_Number_of_Reviews_Reviewer_Has_Given: Number of Reviews the reviewer has given in the past.
12.Total_Number_of_Reviews: Total number of valid reviews the hotel has.
13.Tags: Tags reviewers used in their review.
14. days_since_review: Duration between the review date and scrape date 
15.Additional_Number_of_Scoring: There are also some guests who just made a scoring on the service rather than a review. This number
indicates how many of those valid scores a hotel has that don't include a review
16.lat: Latitude of the hotel
17.lng: Longtitude of the hotel

## Transforming and Cleaning the Data

.Checked and removed the errors in the dataset.
.Checked Null values and Changed it to Unknown'.
.Some rows were empty filled it with 'Unknown'.
.Gave clear names to the headers.
.Formated the columns correctly.
.Split the contents of one column into multiple columns by using delimiters.

## Features

1. **Interactive Dashboard:** Provides filtering options by country, city, hotel, date, type of trip, traveler type, and nationality.
2. **Visualizations:** Includes maps, word clouds, charts, etc., displaying various insights.
3. **Pages:**
   - **Trip and Travelers Insights:** Analysis related to trips and travelers.
   - **Review and Reviewer Analysis:** Exploration of reviews and reviewers.
   - **Positive and Negative Comments:** Detailed analysis of comments.
     
## Steps

1. **Data Preprocessing**: Clean and organize the extensive dataset provided by Techionista Holidays.
2. **Filtering and Analysis**: Implement filtering options for various attributes such as countries, cities, and hotels.
3. **Visualization Development**: Create interactive visualizations to depict the data effectively.
4. **Insights and Analytics**: Generate insights through positive and negative scores, word clouds, etc.

### Trip and Travelers Insights

![Trip and Travelers Insights](https://github.com/Vidisha84/Data-Driven-Techionista-Hotel-Analysis/blob/main/2.jpg)

### Review and Reviewer Analysis

![Review and Reviewer Analysis](https://github.com/Vidisha84/Data-Driven-Techionista-Hotel-Analysis/blob/main/3.jpg)
