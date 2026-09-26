# Power BI Internship Project – Netflix Content Analysis

This repository contains my Power BI internship project, built around a Netflix dataset. The internship required completing any 4 of 6 available tasks; this project covers data import and cleaning, data validation, data modeling, dashboard creation, global content analysis, and content growth and trend analysis.

## Objectives

The goal of this project was to take a raw Netflix dataset and turn it into something usable — cleaning and validating the data, building a proper data model, and then developing a set of interactive dashboards that answer real questions about the content library: how it's split between movies and TV shows, where the content comes from, and how the catalog has grown over time.

## Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- GitHub
- Netflix dataset (show_id, type, title, director, country, date_added, release_year, rating, duration, listed_in)

## Project Files

**Power BI file**
- `Netflix_Content_Overview_dashboard_final_one.pbix` — the complete project file

**Task 1 – Data Preparation & Validation**
- `01 task 1_data_import_cleaning.png` — data import and cleaning in Power Query
- `02 task 1_Model_view.png` — the data model
- `03 task 1_data_validation.png` — validation checks after cleaning

**Task 2 – Netflix Content Dashboard**
- `04 task 2_final_dashboard.png` — final content overview dashboard

**Task 3 – Global Content Insights**
- `05 task 3_global_content_insight.png` — global content analysis dashboard

**Task 4 – Content Growth & Trends**
- `06 task 4_content_growth_and_trend_analysis.png` — content growth and trend analysis

## Tasks Completed

**Task 1 – Data Preparation**
Imported the raw dataset into Power BI and cleaned it up in Power Query — handled duplicates, filled in blank fields (director values that were missing got labeled "Not Given"), fixed data types, and built out the model. Ran a validation pass afterward to confirm the row counts and key fields were intact.

**Task 2 – Netflix Content Overview**
Built the main dashboard summarizing the content library: total titles, the split between movies and TV shows, and a rating slicer covering all 14 rating categories in the dataset. Out of 8,789 titles, about 70% are movies and 30% are TV shows.

**Task 3 – Global Content Insights**
Analyzed how content is distributed across countries — a ranked table, a map visualization, and a bar chart, with a slicer so you can filter down to any individual country. The US and India have the largest share of titles by a fair margin.

**Task 4 – Content Growth & Trend Analysis**
Looked at how the content library has grown by release year, using a time-series chart along with measures for overall growth and year-over-year change, to see which periods saw the most (and least) content added.

## Skills Demonstrated

Data cleaning and transformation, data validation, data modeling, DAX measures, interactive dashboard design, and version control through GitHub.

## Conclusion

This project walks through the full process of turning a raw dataset into a working Power BI solution — cleaning and modeling the data, then building dashboards that surface real insights about Netflix's content library, its global reach, and how it's changed over time.

---

Completed as part of the Auspify Technologies Power BI Internship Program.
