# Airbnb_SentimentAnalysis_NLP_2023
This repository contains the code files and report for the project "Unleashing the Power of Large Language Models: GPT-3.5 and BERT versus Traditional Models for Sentiment Analysis
in Airbnb Review" developed as a final project in the course Natural Language Processing and Text Analytics at the Copenhagen Business School.

## Description
* **Project**: This project developed and compares two LLM models (BERT and GPT-3.5) with traditional models (Logistic Regression and Naïve Bayes)
for binary sentiment analysis based on scraped Airbnb review comments.Results show that GPT-3.5 has the highest macro F1 score of about 0.906.

* **Course**: The course taught students about the phenomena of text analytics and Natural Language Processing, including fundamental concepts, techniques and methods of Natural Language Processing. Students learned to analyze and apply different text analytics techniques for big/business datasets in organizational contexts, and understand the linkages between business intelligence and text analytics and the potential benefits for organizations. The course also covered the application areas, trends, and challenges in text analysis, and students were required to exhibit deeper knowledge and understanding of the topics as part of a project, with the report reflecting critical awareness of methodological choices and written to accepted academic standards.
  
## Authors
Konstantin Kleffke, Linda Schombach, Julius Wirbel and Yile Huang

## Folder Structure

The folders are structured as follows:

```bash
.
├── Code
│   ├── 1_Script_Preprocessing_JoinDatasets.ipynb
│   ├── 2_Script_Preprocessing.ipynb
│   ├── 3_Additional_Preprocessing.ipynb
│   ├── 4_Topic_Modeling.ipynb
│   ├── 5_Top2Vec.ipynb
│   ├── 6_Naive_Bayes.ipynb
│   ├── 7_Logistic_Regression.ipynb
│   ├── 8_BERT.ipynb
│   └── 9_GPT-3.5_evaluation.ipynb
├── README.md
└── Report.pdf
```

## Data

* The data was scraped from Apify. To ensure the usage of a dataset that is up-to-date and best suitable for the present research question, datasets were scraped via Apify. Apify is a website providing a variety of ready-made actors for web scraping. By defining location, price range, and other needed variables, several datasets were scraped sequentially using the Airbnb Scraper. Due to the limited capacity of returning datapoints, it was required to request data in several iterations. It was scraped based on a selection of cities and by different price ranges. Location was limited to Europe. The seven cities with the largest average monthly profit were selected as they were considered to have sufficient datapoints: London, Paris, Munich, Dublin, Milan, Copenhagen and Oslo. Overall, the dataset prior pre-processing holds 16,106 Airbnb’s and 1,077,494 reviews.
