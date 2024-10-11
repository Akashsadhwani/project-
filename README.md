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

# Data Analysis trends 

Trend Analysis: Growth and Decline in App Installs and Reviews Over Time
1. App Install Trend (Yearly Growth)

From the dashboard, you can observe the following installation trends across major years:

    2015: Dominates the install landscape with 68% of the total installs, indicating a massive spike in app installations during that year.
    2016: Shows another significant chunk, contributing to 20M installs, reflecting sustained growth.
    2017-2018: Installs drastically reduce, with 9M installs in 2018 and even fewer in previous years (2017 accounts for only 7% of installs).

Interpretation:

    Growth Spike: The year 2015 marks the peak for app installs, followed by a sustained high in 2016. This suggests that these years saw a large influx of new users into the Play Store or high-profile app launches.
    Decline in Recent Years: From 2017 to 2018, there's a notable decline, possibly due to market saturation or users migrating to other platforms.

2. Review and Rating Trend (Yearly Growth)

The bar graph for ratings and reviews highlights the following trend:

    2018: The highest activity for ratings (7.3K) and reviews (1.9K).
    2017: Has a noticeable drop in reviews and ratings compared to 2018, but still maintains a moderate count (~800 ratings and 400 reviews).
    Before 2016: Extremely low numbers, suggesting minimal app ratings and reviews.

    2. Review and Rating Trend (Yearly Growth)

The bar graph for ratings and reviews highlights the following trend:

    2018: The highest activity for ratings (7.3K) and reviews (1.9K).
    2017: Has a noticeable drop in reviews and ratings compared to 2018, but still maintains a moderate count (~800 ratings and 400 reviews).
    Before 2016: Extremely low numbers, suggesting minimal app ratings and reviews.

Interpretation:

    Growth in User Engagement: There’s a clear peak in 2018 for both reviews and ratings, indicating users became more active in leaving feedback. This could correspond to app improvements, user experience focus, or increased marketing strategies by app developers.
    Decline in Older Years: The earlier years (before 2016) show limited user interaction through reviews, possibly due to fewer apps or less active user bases.

    3. Category-Based Growth in Reviews

The "Count of Reviews by Category" graph provides a detailed breakdown of reviews across major categories. The highest reviewed categories are:

    Family and Games: Leading in review counts.
    Tools and Medical: Follow closely with substantial user engagement.
    Business and Productivity: Also show noticeable activity, but at a lower level compared to Family and Games.

Interpretation:

    Growth in Family & Game Apps: Apps categorized under Family and Games seem to have garnered increasing user engagement, likely driven by the wide range of popular mobile games and family-oriented apps that attract mass market users.
    Tools and Medical: These categories indicate a steady growth in user engagement, possibly reflecting the demand for utility and healthcare-related apps.

Visualizing Trend Analysis

    Year-over-Year Installs:
        A line graph showing total installs per year from 2015 to 2018 would vividly show the growth spike in 2015 and 2016 and the gradual decline in 2017-2018.

    Year-over-Year Ratings and Reviews:
        Use a dual-axis line chart for ratings and reviews over time. This would highlight the sharp increase in 2018 for both metrics.

    Reviews by Category Over Time:
        A stacked bar graph showing the number of reviews for top categories (Family, Games, Tools) over different years would provide insight into how user engagement evolved in specific app segments.

These visualizations would make it easier to pinpoint key growth years and areas of decline, providing actionable insights for app developers or businesses.

#  Correlation Analysis: App Cost (Free vs Paid) and Rating/Reviews
  
   Key Observations from the Correlation:
   

    Higher Engagement with Free Apps:
        Users are more likely to download, rate, and review free apps, likely because of lower risk and barriers to entry. In the Tools category, where there are high numbers of free apps, this engagement trend is particularly clear, with 834 reviews for free apps.

    Paid Apps Have Fewer Ratings and Reviews:
        Paid apps tend to have fewer reviews and ratings across the board. For example, in Entertainment, free apps have 380 reviews, while paid apps only have 192. This might be due to users being selective about purchasing apps, leading to fewer installs and lower engagement.

    Entertainment and Medical Categories:
        Entertainment and Medical are categories where paid apps still manage to hold ground. These categories often offer premium content or specialized features that justify a price, leading to a higher chance of users providing feedback, even if the total number of reviews is lower compared to free apps.

    Higher Review Counts in Free Apps Could Affect Overall Ratings:
        Since free apps have a higher number of users and reviews, their average rating could be more reflective of mass-market appeal or dissatisfaction. Paid apps, on the other hand, may have more positive reviews but in smaller numbers, as users tend to leave feedback only if they are significantly impressed or dissatisfied.

Conclusions from the Correlation:

    Free apps are more frequently rated and reviewed, which may be due to their wider accessibility and greater user base.
    Paid apps generally have fewer reviews but often in categories where specialized features are valued (e.g., Entertainment and Medical).
    The quality of feedback for paid apps might skew higher, as users paying for a service tend to leave more thoughtful reviews, while free apps attract a broader, potentially less discerning user base.

This correlation highlights that while quantity of reviews is higher for free apps, paid apps may offer more reliable or targeted insights through their reviews due to their smaller but potentially more invested audience.






/** this analysis are prepared on the present data number or points .Informatin is provide in might be not correct in some aspect or under a scrutiny but on the basis of the data I presetent a report which of my knowledge. 

I am still learning and eager to do learn more of ways to analys the data and present more furnish perfect report presetation project **/

