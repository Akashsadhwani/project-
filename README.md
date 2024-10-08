# Play store applications 

 # Introduction

The CSV file contains data about various applications, likely from the Google Play Store. Here’s a summary that can be used for presentation purposes:
Dataset Overview:

    Total Entries: 10,840
    Columns: 16

Key Columns:

    App: The name of the application.
    Category: The category under which the app is listed (e.g., ART_AND_DESIGN, GAME, etc.).
    Rating: Average user rating of the app.
    Reviews: Number of user reviews.
    Size: The size of the application in kilobytes.
    Installs: Total installations.
    Type: Indicates whether the app is free or paid.
    Price: The price of the app (if it's a paid app).
    Content Rating: Age suitability (e.g., Everyone, Teen).
    Genres: The genre(s) of the app.
    Current Ver: The current version of the app.
    Android Ver: The minimum Android version required to run the app.
    Date Columns: Includes day, month, and year, possibly indicating when the data was collected.

# source of the dataset

The dataset is download from a websiter (https://www.kaggle.com/). The primary dataset used for the analysis is the [google_cleaned (2).xlsx](https://github.com/user-attachments/files/17327013/google_cleaned.2.xlsx) containes detailed information about the application available in the Play Store.

# Example of Applications:

    Photo Editor & Candy Camera & Grid & ScrapBook:
        Category: Art & Design
        Rating: 4.1
        Installs: 10,000
        Price: Free
        Content Rating: Everyone

    Sketch - Draw & Paint:
        Category: Art & Design
        Rating: 4.5
        Installs: 50,000,000
        Price: Free
        Content Rating: Teen

# Tools 

>  Excel , Power query for cleaning 
>  Mysql for data analysis
>  PowerBi for visualization

# Data cleaning/preparation

 1 data loading and inspecting
 2 Handling missing values 
 3 data cleaning and formatting 

# Exploratary data analysis on 

 1 No of apps paid and non paid ?.

 2 No of apps get installed in paricular year in number ?.
 
 3 Rating of genres and content rating ?.
 
 4 Rating of genres and content by everyone , adults , under18  and unrated ?.
 
 5 Scatter plot realtion analysis of piad or free application with review on application ?


 # result of the EDA 
 
In this project and preseted through report, charts,graphs ect.

1 from 10.84k ( 92.62 percentage of applications were free or 10040 applications were free and 800 were paid which is 7.38 percent from 100 percent)

2 max installation were recorded in 2018 
 which is 80 million or 68 percent approx.
 min was in 2012 281040 which is 0.24 percent of total instals.

 3 rating on the application regarding their year were seen from 2013 which were 110 in number or min 
 which is presented in date
and 
 max rating were seen in 2018 as 7349 review and rating mention in data .

 4 tools , entertainment, education were  the top categories on the basis of reviews by everyone .

 5 free appication had less reviews as comparied to the paid one it might be because it free availability or because of the fact the money is involved people are more to give it a review on the bais of thier satisfaction .

 # Insights for Presentation:

    Popular Categories: Art & Design appears prominently in the dataset.
    High Install Counts: Some apps have over 50 million installs, showing their popularity.
    Free vs Paid: Most apps are free, with pricing data available for paid ones.
    Content Ratings: Helps determine the target audience of the apps.

# Data Analysis 

here are some of the code/ feature working with :

select count(app) as installs from morality.'google_cleaned (2)';







/** this analysis are prepared on the present data number or points .Informatin is provide in might be not correct in some aspect or under a scrutiny but on the basis of the data I presetent a report which of my knowledge. 

I am still learning and eager to do learn more of ways to analys the data and present more furnish perfect report presetation project **/

