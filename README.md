# NPS Survey Semantic Analysis

## Overview
This repository contains a detailed semantic analysis of a Net Promoter Score (NPS) survey. The survey comprises three main components: the NPS score (ranging from 0 to 10), reasons for the given scores, and suggestions for improvements.

## Methodology
The analysis involves the following steps:
1. **Data Preprocessing**: Cleaning and tokenizing the text data from 'Reason' and 'Improvement' columns.
2. **Topic Modeling**: Using Gibbs Sampling Dirichlet Mixture Model (GSDMM) to identify prevalent topics within the survey responses.
3. **Coherence Scoring**: Evaluating the quality of the identified topics.
4. **Visualization**: Generating word clouds and bar charts for visual representation of the results.

## Tools Used
- **Python Libraries**: Pandas for data manipulation, NLTK for text processing, Gensim for topic modeling, and Matplotlib for visualization.
- **Data**: Analysis conducted on `Score_Alldata.csv`.

## Analysis and Results
The survey responses are categorized based on the NPS score into three categories: '0-6', '7-8', and '9-10'. Each category is analyzed separately for both 'Reason' and 'Improvement' columns.

### Reason Column Analysis
- **Objective**: To understand the primary reasons behind the scores given by customers.
- **Process**: Applying GSDMM to the preprocessed data from the 'Reason' column.
- **Results**:
  - **Score Category: 0-6**
    - Top Words: 'signal', 'poor', 'good', 'network', 'service'
    - Coherence Score: 0.4059
    - ![Word Cloud for Score Category 0-6](link-to-wordcloud-reason-0-6.jpg)
    - ![Bar Chart for Score Category 0-6](link-to-barchart-reason-0-6.jpg)
  - (Continue with other score categories)

### Improvement Column Analysis
- **Objective**: To identify areas of improvement as suggested by customers.
- **Process**: Similar analysis is performed on the 'Improvement' column.
- **Results**:
  - **Score Category: 0-6**
    - Top Words: 'improve', 'better', 'signal', 'coverage', 'service'
    - Coherence Score: 0.5326
    - ![Word Cloud for Score Category 0-6 Improvement](link-to-wordcloud-improvement-0-6.jpg)
    - ![Bar Chart for Score Category 0-6 Improvement](link-to-barchart-improvement-0-6.jpg)
  - (Continue with other score categories)

## Conclusion
This semantic analysis of the NPS survey provides valuable insights into customer sentiments and perceptions, highlighting key areas for improvement and understanding customer satisfaction drivers.

(Note: Replace the link placeholders with actual URLs to your word clouds and bar charts to visually support your findings.)
