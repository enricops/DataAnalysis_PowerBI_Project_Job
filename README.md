# Data Jobs Dashboard w/ Power BI

<a href="YOUR_POWER_BI_DASHBOARD_LINK" target="_blank">
  <img src="Assets\Data Jobs Dashboard Overview.gif" alt="Data Jobs Dashboard Overview">
</a>


## Introduction

This dashboard was developed to help **Job Seekers, Career Transitioners, and Professionals Exploring the Data Industry** better understand the data job market.

Information about job opportunities, salary expectations, and employment trends is often scattered across multiple platforms, making it difficult to gain a comprehensive understanding of the market.

Using a real-world dataset of 2024 data job postings, this project provides an interactive dashboard to explore employment trends, salary comparisons, job distributions, and other important aspects of the data job market.

This project is based on the learning materials and project framework provided by Luke Barousse, with independent modifications to the dashboard design, visual presentation, and selected analytical approaches.

### Dashboard File

You can find the Power BI dashboard file here: [`Data_Jobs_Dashboard.pbix`](Data_Jobs_Dashboard.pbix).

## Skills Showcased

This project demonstrates practical Power BI skills through data visualization, statistical analysis, and interactive dashboard development.

- **🧮 Statistical Analysis & Aggregation:** Applied Average and Median calculations to analyze salary information from different perspectives, including yearly and hourly compensation.

- **📐 DAX & Quick Measures:** Utilized Power BI Quick Measures to generate DAX expressions for a custom Salary Star Rating indicator, converting median yearly salary into a visual five-star rating based on predefined salary thresholds.

- **📊 Data Visualization:** Implemented various visualization types, including Line Charts, Scatter Charts, Horizontal Bar Charts, Gauge Charts, Donut Charts, and Treemaps to explore job market trends and compensation patterns.

- **🗺️ Geospatial Analysis:** Used Map Charts to visualize the global distribution of data-related job opportunities.

- **🔢 KPI Indicators & Tables:** Utilized Cards and Gauge Charts to highlight key metrics, alongside Tables with Data Bars and Sparklines to provide more detailed comparisons.

- **🎨 Dashboard Design & Customization:** Independently modified the original dashboard's visual presentation, including layout, color scheme, chart arrangements, and overall reporting experience.

- **🖱️ Interactive Reporting:**
  - **Slicers:** Enabled dynamic filtering by Job Title.
  - **Date Range Slider:** Allowed users to explore job posting trends across different periods.
  - **Drill-Through:** Enabled navigation from the overall market overview to detailed job-specific analysis.

---

## Dashboard Overview

This report consists of two interactive pages, providing both a high-level overview of the data job market and a more detailed analysis of individual job titles.

### Page 1: Data Jobs Market Overview

![Data Jobs Dashboard Page 1](./Assets/Data%20Jobs%20Dashboard%20Page%201.gif)

The first page provides a comprehensive overview of the data job market through several key performance indicators and visualizations.

Key information includes:

- **Job Count:** Displays the overall number of job postings.
- **Salary Star Rating:** Converts median yearly salary into a five-star visual indicator using predefined salary thresholds.
- **Average Yearly & Hourly Salary:** Highlights average compensation across the dataset.
- **Job Posting Trends:** Tracks changes in job posting volumes throughout 2024.
- **Yearly vs. Hourly Salary Comparison:** Uses average salary measures to compare compensation across different data-related job titles.
- **Job Count by Title:** Identifies job titles with the highest number of postings.
- **Job Statistics:** Provides detailed comparisons of job counts, average yearly salaries, hourly salaries, and job posting trends.

**Analytical Modification:**

One of the modifications in this dashboard is the use of Average Salary instead of Median Salary for the primary yearly and hourly salary KPIs, as well as the salary comparisons in the Scatter Chart and Job Stats table.

Additionally, a custom Salary Star Rating was implemented using a Quick Measure-generated DAX expression. It maps median yearly salary values within a predefined range of $75,000 to $150,000 into a five-star visual indicator.

### Page 2: Job Title Drill-Through Analysis

![Data Jobs Dashboard Page 2](./Assets/Data%20Jobs%20Dashboard%20Page%202.gif)

The second page provides a more detailed analysis of an individual job title through the drill-through functionality.

Users can explore several aspects of a selected position, including:

- **Salary Analysis:** Yearly and hourly salary indicators.
- **Work Flexibility:** Percentage of job postings mentioning work-from-home opportunities.
- **Educational Requirements:** Percentage of postings that do not mention degree requirements.
- **Employee Benefits:** Percentage of postings mentioning health insurance.
- **Global Job Distribution:** A geographical visualization of job opportunities worldwide.
- **Hiring Platforms:** A comparison of platforms based on the number of job postings.
- **Job Types:** A breakdown of employment types, including full-time and contractor positions.

This page allows users to move beyond general market statistics and examine specific characteristics of individual job opportunities.

---

## Conclusion

This project demonstrates how Power BI can transform raw job posting data into an interactive dashboard that provides meaningful insights into the data job market.

By combining statistical measures, salary comparisons, trend analysis, and geographical visualizations, the dashboard offers different perspectives on employment opportunities and compensation across data-related professions.

Beyond following the original project's core structure, this version incorporates independent modifications to its visual design and analytical approach, including the use of Average Salary for primary compensation metrics and a custom salary rating indicator.

Through this project, I strengthened my practical understanding of statistical analysis, data visualization, DAX Quick Measures, and interactive dashboard development using Power BI Desktop.

---

## Credits & Acknowledgements

This project was developed as part of my Power BI learning journey, using educational resources and the original project framework provided by **Luke Barousse**.

- **Original Course:** [Power BI for Data Analytics – Luke Barousse](https://www.lukebarousse.com/powerbi)
- **GitHub Repository:** [PowerBI_Data_Analytics_Course](https://github.com/lukebarousse/PowerBI_Data_Analytics_Course)
- **Dataset:** 2024 Data Job Postings

The original project structure, learning materials, and dataset are credited to their respective creator. Dashboard design and selected analytical approaches have been independently modified for this portfolio project.