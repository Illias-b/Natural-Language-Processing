# NPS Survey Semantic Analysis

## Overview
This repository contains a semantic analysis of a Net Promoter Score (NPS) survey, focusing on survey scores, reasons for the scores, and suggestions for improvements.

## Methodology
The analysis involves data preprocessing, topic modeling using Gibbs Sampling Dirichlet Mixture Model (GSDMM), coherence scoring, and visualization.

## Tools Used
- Python Libraries: Pandas, NLTK, Gensim, Matplotlib
- Data: Analysis conducted on `Score_Alldata.csv`.

## Code Description
The code for this project is divided into several key parts, each responsible for a stage in the analysis process:
1. **Data Preprocessing**: Cleaning and tokenizing text data.
2. **Topic Modeling**: Applying GSDMM for identifying topics within survey responses.
3. **Visualization**: Generating word clouds and bar charts to visualize the findings.

The main script `nps_analysis.py` contains the full code used for this analysis. Additional utility scripts may be included for specific tasks like data cleaning or visualization.

## Analysis and Results
### Reason Column Analysis
- Objective: To understand the primary reasons behind customer scores.
- Results for Score Category '0-6': 
  - Top Words: 'signal', 'poor', 'good', ...
  - Coherence Score: 0.4059
  - ![Word Cloud for Score Category 0-6](link-to-wordcloud-reason-0-6.jpg)
  - ![Bar Chart for Score Category 0-6](link-to-barchart-reason-0-6.jpg)
- (Continue with other score categories)

### Improvement Column Analysis
- Objective: To identify areas for improvement.
- Results for Score Category '0-6': 
  - Top Words: 'improve', 'better', 'signal', ...
  - Coherence Score: 0.5326
  - ![Word Cloud for Score Category 0-6 Improvement](link-to-wordcloud-improvement-0-6.jpg)
  - ![Bar Chart for Score Category 0-6 Improvement](link-to-barchart-improvement-0-6.jpg)
- (Continue with other score categories)

## Conclusion
This analysis provides insights into customer sentiments, highlighting key areas for improvement and understanding customer satisfaction drivers.

(Note: Replace the link placeholders with actual URLs to your visualizations. The code files mentioned should be uploaded to the repository.)
