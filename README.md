# Pizza Hut Customer Insights Project 🍕📊

## Overview
This project involves the collection, analysis, and visualization of customer reviews for **Pizza Hut** to extract valuable insights. The main goal is to understand customer sentiment, identify key issues, and make actionable recommendations for improving customer experience. The project uses **Python** for data collection and preprocessing, and **Tableau** for creating a detailed dashboard with multiple tabs showcasing various analyses.

## Project Structure

```
Pizza Hut Customer Insights Project
│
├── All Datasets and Codebase/
│   ├── Common_words_analysis.csv                # Clustering analysis of common words in reviews
│   ├── Data_Preprocessing-Copy1.ipynb           # Jupyter Notebook for data preprocessing
│   ├── Key_words_analysis.csv                   # Keyword analysis results
│   ├── MoM_review_increase.csv                  # Month-over-month review increase calculations
│   ├── PizzHut_Reviews.twbx                     # Tableau Workbook for the dashboard
│   ├── Pizza_Hut_Recipe_Scrapped_Data.csv       # Scraped customer review data (raw)
│   ├── Pizza_Hut_Recipe_Scrapped_Data_with_date.csv  # Scraped data with date information
│   ├── sentiments_with_dates.csv                # Sentiment analysis results with dates
│   ├── sentiments_with_dates_updated.csv        # Updated sentiment analysis with further preprocessing
│
├── Dashboards Images/
│   ├── D11.png                                  # Sentiment Analysis tab image 1
│   ├── D12.png                                  # Sentiment Analysis tab image 2
│   ├── D13.png                                  # Sentiment Analysis tab image 3
│   ├── D21.png                                  # Keywords Analysis tab image 1
│   ├── D22.png                                  # Keywords Analysis tab image 2
│   ├── D31.png                                  # Common Words Analysis tab image 1
│   ├── D32.png                                  # Common Words Analysis tab image 2
│
├── Report/
│   └── sm_doc.docx                              # Full project report with in-depth analysis
│
└── README.md                                    # Project documentation
```

## Files and Directories

- **All Datasets and Codebase/**: This directory contains the datasets and code used for sentiment and keyword analysis, along with the clustering of common words from customer reviews.
  - **Pizza_Hut_Recipe_Scrapped_Data.csv**: Raw data scraped from Trustpilot.
  - **sentiments_with_dates.csv**: Processed dataset with sentiment labels (positive, neutral, negative).
  - **Data_Preprocessing-Copy1.ipynb**: Jupyter Notebook with all preprocessing and analysis steps, including web scraping and sentiment analysis using Python libraries such as **Pandas**, **TextBlob**, and **nltk**.
  - **PizzHut_Reviews.twbx**: Tableau workbook used to create the dashboard.
  
- **Dashboards Images/**: Screenshots from the **Pizza Hut Customer Insights Dashboard**, showcasing sentiment analysis, keyword analysis, and common word clusters.

- **Report/**: Full project report in Word format, detailing the methodology, results, visualizations, and actionable recommendations for Pizza Hut.

## Tableau Dashboard

You can explore the full **Pizza Hut Customer Insights Dashboard** here: [**Pizza Hut Dashboard**](https://public.tableau.com/views/PizzaHutCustomerInsightsDashboardSentimentandClusteringAnalysis/SentimentAnalysis?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

The dashboard includes:
1. **Sentiment Analysis**: Tracks customer sentiment (positive, neutral, and negative) over time, highlighting trends and key periods of customer feedback.
2. **Keywords Analysis**: Examines the frequency of specific keywords in reviews and their associated sentiment.
3. **Common Words Analysis**: Hierarchical clustering of common terms to reveal thematic clusters related to customer experiences like service, quality, and online orders.

## Key Features

- **Web Scraping**: Reviews were collected from Trustpilot using Data Miner.
- **Sentiment Analysis**: Python's TextBlob was used to classify reviews into positive, neutral, or negative categories.
- **Keyword and Common Words Analysis**: Frequent terms in reviews were identified and analyzed using word embeddings and clustering techniques.
- **Tableau Visualizations**: Interactive visualizations were created in Tableau to help Pizza Hut easily understand customer feedback and make informed decisions.

## How Pizza Hut Can Use This Data

The insights generated from this project can help Pizza Hut:
- **Improve Customer Service**: Identify pain points in service and address them to enhance customer satisfaction.
- **Optimize Product Offerings**: Based on feedback about food quality and delivery times, Pizza Hut can adjust operations to better meet customer expectations.
- **Track Performance Over Time**: The month-over-month sentiment analysis enables tracking of customer satisfaction trends and prompt resolution of recurring issues.
- **Refine Online Services**: Customer feedback about online ordering issues can be used to improve the digital experience.

## Tools Used

- **Python**: For data collection (web scraping), preprocessing, sentiment analysis, keyword analysis, and clustering.
- **Tableau**: For creating the interactive dashboard.
- **Pandas**, **nltk**, **TextBlob**: Libraries used in data manipulation and natural language processing.
