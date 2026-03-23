# YouTube Analytics Dashboard using Power BI

## Overview

This project analyzes global YouTube statistics using Power BI to uncover insights related to content performance, audience engagement, and channel growth. The dashboard provides a comprehensive view of key metrics such as uploads, views, subscribers, and rankings.

## Problem Statement

The objective of this project is to identify trends and patterns in YouTube data that can help content creators and marketers improve their strategies and maximize audience engagement.

## Dataset

The dataset includes global YouTube statistics with the following attributes:

* Video views
* Subscribers
* Uploads
* Channel type
* Category
* Ranking metrics

A cleaned dataset is used to ensure accuracy and consistency.

## Data Preparation

The dataset was processed using the following steps:

1. Removed null and missing values
2. Eliminated duplicate records
3. Converted numeric columns into proper format
4. Removed special characters such as commas
5. Standardized column formats
6. Validated data types

## Dashboard Features

The Power BI dashboard includes:

* KPI Cards (Maximum Uploads, Minimum View Rank, Average Views, Total Uploads)
* Line Chart showing channels with uploads greater than 200K
* Radar Chart for channel type vs rank
* Packed Bubble Chart for category-wise subscribers
* Table showing views per subscriber
* Decomposition Tree for rank-wise category analysis

## DAX Calculations

* Viewed by Subscriber = Views / Subscribers
* Total Uploads = SUM(Uploads)
* Average Views (Last 30 Days)

## Key Insights

* Entertainment and Music categories dominate in subscribers and rankings
* News channels have the highest upload frequency
* High uploads do not always result in high engagement
* Engagement varies across different content categories
* Subscriber count alone is not a strong indicator of performance

## Recommendations

* Focus on high-performing categories such as Entertainment and Music
* Maintain balance between content quality and quantity
* Improve engagement through interactive content
* Analyze audience behavior for better content strategy

## Project Files

* Global YouTube Statistics.csv → Raw dataset
* youtube_powerbi_analysis.pptx → Presentation with insights
* youtube report.pdf → Exported report
* CLEANED DATASET README.md → Dataset documentation

## Tools Used

* Microsoft Power BI
* DAX
* Power Query
* Microsoft PowerPoint

## Conclusion

This project demonstrates how data analytics and visualization can be used to derive meaningful insights from YouTube data and support data-driven decision-making.

## Author

Developed as part of a Data Analytics project.
