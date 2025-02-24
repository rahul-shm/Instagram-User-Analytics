# Instagram User Analytics: A SQL Case Study

## Repository Structure
This repository is organized into the following files:
- **Report**: Contains the final presentation/report summarizing the insights and findings.
- **Commands for creating Database**: Contains the commands for creating Database.

---

## Project Overview
As a data analyst working with the Instagram product team, the goal of this project is to analyze user engagement and interactions with the platform. By leveraging SQL, we extract valuable insights from the provided user database to help the product and marketing teams make data-driven decisions. The analysis also serves to provide investors with crucial metrics about platform activity and user behavior.

---

## Tasks and SQL Analysis

### A) Marketing Analysis

1. **Loyal User Reward**
   - **Objective**: Identify the five oldest users on Instagram to reward their loyalty.
   - **Approach**: Extract user details sorted by the earliest registration dates.
   - **SQL Query**: Provided in the `Solution` folder.
   - **Insights**: Highlight the oldest users based on their registration timestamps.

2. **Inactive User Engagement**
   - **Objective**: Identify users who have never posted a single photo.
   - **Approach**: Query users with zero photo uploads.
   - **SQL Query**: Provided in the `Solution` folder.
   - **Insights**: Determine inactive users for targeted engagement campaigns.

3. **Contest Winner Declaration**
   - **Objective**: Identify the user with the most likes on a single photo.
   - **Approach**: Query the photo with the maximum number of likes and retrieve the associated user details.
   - **SQL Query**: Provided in the `Solution` folder.
   - **Insights**: Identify the contest winner and their most-liked photo.

4. **Hashtag Research**
   - **Objective**: Suggest the top five most commonly used hashtags.
   - **Approach**: Count the occurrences of each hashtag and sort by frequency.
   - **SQL Query**: Provided in the `Solution` folder.
   - **Insights**: Highlight trending hashtags to inform marketing campaigns.

5. **Ad Campaign Launch**
   - **Objective**: Determine the best day of the week to launch ad campaigns based on user registration patterns.
   - **Approach**: Analyze registration timestamps to find the most popular day.
   - **SQL Query**: Provided in the `Solution` folder.
   - **Insights**: Recommend optimal days for ad scheduling.

---

### B) Investor Metrics

1. **User Engagement**
   - **Objective**: Calculate the average number of posts per user and provide the ratio of total photos to users.
   - **Approach**: Aggregate photo uploads and divide by the total user count.
   - **SQL Query**: Provided in the `Solution` folder.
   - **Insights**: Measure overall user engagement with the platform.

2. **Bots & Fake Accounts**
   - **Objective**: Identify users who have liked every single photo on the platform, indicating potential bot behavior.
   - **Approach**: Query users whose like counts match the total number of photos.
   - **SQL Query**: Provided in the `Solution` folder.
   - **Insights**: Highlight suspicious accounts for further investigation.

---

## Approach and Execution
1. **Database Setup**: The provided SQL file was imported into MySQL Workbench to set up the database.
2. **Query Writing**: SQL queries were written and tested for each task, ensuring efficiency and accuracy.
3. **Analysis**: Data retrieved from the queries was analyzed to derive actionable insights.
4. **Documentation**: Outputs and findings were documented and compiled into a report.

---

## Tech-Stack Used
- **MySQL Workbench**: Used for SQL query execution and database management.
- **SQL**: Primary tool for querying and analyzing data.
- **Microsoft PowerPoint / Word**: Used to create the final report.

---

## Insights and Learnings
- **Data-Driven Decision Making**: SQL allows for efficient extraction and analysis of key metrics.
- **Marketing Strategies**: Insights like popular hashtags and registration trends can drive successful campaigns.
- **User Behavior Analysis**: Identifying inactive users and potential bots supports platform optimization.

---

## Results and Impact
- **Optimized Marketing Strategies**: Insights into user behavior help design targeted campaigns and reward loyalty.
- **Investor Confidence**: Clear metrics on engagement and suspicious activity address investor concerns.
- **Enhanced Decision-Making**: Actionable insights guide future development and marketing efforts.

---

## Contributing
Contributions to improve this case study are welcome. If you have additional ideas or suggestions, feel free to open an issue or submit a pull request.
