# Netflix Content Strategy Analytics: A Business Intelligence Solution

## Overview

This project analyzes Netflix's content strategy using a combination of descriptive and predictive analytics. The goal is to uncover trends, audience preferences, and content performance factors that inform strategic content creation and business decisions. Built with Power BI, Python, and Azure Machine Learning, this solution delivers actionable insights to optimize Netflix’s platform and maintain competitive advantage in the streaming industry.

## Group Members
- Abdullahi Ayuub
- Abdullah Aljaberi
- Isaiah Giebel
- Alex Cole
(Group Name: Netflix Analytics Crew)

## Business Intelligence Problem

In a highly competitive streaming market, Netflix must refine its content strategy to align with evolving audience preferences and outperform rivals like Amazon Prime, Hulu, and Disney+. Key questions addressed include:
- Which genres perform best?
- How does release year impact content success?
- Are movies or TV shows more engaging?
- What is the effect of content duration on viewer satisfaction?

Answering these questions helps Netflix allocate production resources effectively, maximize ROI, and boost subscriber retention.

## Types of Analytics Used

- **Descriptive Analytics**: Summarizing historical viewer engagement trends, genre popularity, and content performance using Power BI visualizations (heatmaps, scatter plots, line charts).
- **Predictive Analytics**: Forecasting future content success using Azure Machine Learning and Python regression/classification models integrated into Power BI.

## Datasets Analyzed

- Netflix Shows Dataset (Kaggle)
- User Engagement Metrics (TimeSpentMinutes, Likes, Comments)
- Financial Metrics (Ad Spend, Marketing Spend, ARPU)
- Subscriber Additions Dataset
- Streaming Time Dataset
- Content Spending Dataset

Data preprocessing included consolidation, cleaning, transformation, and reduction, ensuring a reliable and structured star-schema data model implemented in Power BI.

## Data Model and Architecture

- **Fact Table**: Metrics like Time Spent Watching, Likes, Comments, Streaming Time, and Ad Spending.
- **Dimension Tables**: Content attributes (Genre, Content Type, Release Year, Duration), User Engagement, Financial Metrics, and Time Dimension.
- **Architecture**: 
  - Data Warehouse (structured raw data)
  - Business Analytics (descriptive and predictive analysis)
  - Performance Strategy Layer (Power BI dashboards for stakeholders)

## Key Findings

- **Genre Insights**: Dramas and Comedies consistently achieve higher engagement.
- **Content Duration**: Viewer preferences vary by content length; shorter formats appeal to certain segments.
- **Content Type**: Both TV shows and movies offer value, but engagement patterns differ.
- **Release Trends**: Newer content (recent years) aligns with higher engagement and subscriber growth.
- **Predictive Models**: Forecast content success likelihood based on genre, type, and duration.

## Technologies Used

- Power BI
- Python (for data preprocessing and advanced visualizations)
- Azure Machine Learning (predictive modeling)

## How to View

1. Download the `.pbix` file from this repository.
2. Open it using [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Explore interactive dashboards and predictive analytics reports.

## Conclusion

This project delivers a scalable, data-driven framework that empowers Netflix to refine its content strategy based on viewer engagement patterns, content performance, and predictive forecasts. Leveraging Power BI, Python, and Azure Machine Learning, the analysis ensures that Netflix remains at the forefront of the digital entertainment industry.

---

