# Semantic Analysis of Survey Data

## Overview
This repository contains the analysis of survey data focused on semantic analysis. The objective is to understand the sentiments and topics prevalent in the survey responses, particularly focusing on "disconnect-reconnect" events in customer experiences.

## Methodology
The analysis involves the following steps:
1. Data Preprocessing: Cleaning and tokenizing the text data.
2. Topic Modeling: Using the GSDMM (Gibbs Sampling Dirichlet Mixture Model) to identify topics within the survey responses.
3. Coherence Scoring: Evaluating the quality of the topics identified.

## Tools Used
- Python Libraries: Pandas, NLTK, Gensim, Matplotlib
- Data: The dataset used is `Score_Alldata.csv`.

## Analysis
The analysis is divided into two main parts based on the survey questions - 'Reason' and 'Improvement'.

### Reason Column Analysis
- Objective: To analyze the main reasons for customers' scores.
- Process: The text data from the 'Reason' column is preprocessed and analyzed using GSDMM for topic modeling.

#### Results for Score Category: 0-6
- Top Words: 'signal', 'poor', 'good', 'network', 'service'
- Coherence Score: 0.4059
- ![Word Cloud for Score Category 0-6](link-to-wordcloud-0-6.jpg)
- ![Bar Chart for Score Category 0-6](link-to-barchart-0-6.jpg)

(Continue with other score categories)

### Improvement Column Analysis
- Objective: To identify areas for improvement based on customer feedback.
- Process: Similar to the 'Reason' column, the 'Improvement' column data is processed and analyzed.

#### Results for Score Category: 0-6
- Top Words: 'improve', 'better', 'signal', 'coverage', 'service'
- Coherence Score: 0.5326
- ![Word Cloud for Score Category 0-6](link-to-wordcloud-improvement-0-6.jpg)
- ![Bar Chart for Score Category 0-6](link-to-barchart-improvement-0-6.jpg)

(Continue with other score categories)

## Conclusion
The analysis provides insights into customer sentiment and highlights key areas for improvement. This information can be instrumental in enhancing customer service and addressing specific concerns.

(Note: Replace the link placeholders with actual URLs to your word clouds and bar charts. This will visually complement your findings.)
