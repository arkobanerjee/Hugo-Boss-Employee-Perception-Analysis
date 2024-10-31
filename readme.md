# Hugo Boss Employee Perception Analysis

## Project Overview

This project aims to evaluate the external employee perception of Hugo Boss by gathering comprehensive review data from Kununu and Glassdoor. By analyzing employee reviews and ratings, we aim to identify trends, patterns, and insights into how Hugo Boss employees perceive the company over time. The project leverages multiple data processing, statistical, and machine learning techniques to provide a well-rounded view of employee sentiment.

## Data Collection

The data for this analysis was sourced from two major review platforms:

- **Kununu**: A popular platform for employee reviews, with a focus on European companies.
- **Glassdoor**: A well-known platform for global employee reviews and salary insights.

The data gathered from these platforms includes employee ratings on different metrics, reviews describing work experiences, and other related feedback. The goal was to create a unified dataset that could provide a representative view of employee sentiment.

## Data Processing

### Text Analysis

- **LLMs for Categorization**: To enhance data quality, we leveraged Large Language Models (LLMs) for text analysis. This was particularly useful for categorizing employee reviews based on department and seniority level.
- **Department and Seniority Mapping**: Using keywords and LLMs, we categorized departments accurately. Seniority levels were straightforward for Kununu, whereas for Glassdoor, the categorization was more challenging. We used GPT-4 models to help determine the appropriate seniority group for job positions.

### Data Cleaning & Structuring

- Text processing methods were used to clean reviews, remove irrelevant content, and create structured datasets.
- Ratings and review dates were organized for chronological analysis to facilitate trend studies.

## Analysis Conducted

### Statistical Testing

- **Significance Testing**: We used statistical tests such as ANOVA to determine whether there were significant differences in employee ratings across different years or departments. This helped to identify whether observed changes in sentiment were statistically meaningful.
- **Linear Regression**: We applied linear regression models to assess the trends over time, specifically looking at how different scores evolved year-over-year.

### Trend Analysis

- **Trend Identification**: By performing year-wise trend analysis, we evaluated whether employee satisfaction metrics, such as work-life balance, were improving or deteriorating over time.
- **Sector-wise Analysis**: Our analysis stratified data by different business units (e.g., Retail vs. Corporate) to identify trends unique to different parts of Hugo Boss.
