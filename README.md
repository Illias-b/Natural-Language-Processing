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

1. **Data Preprocessing**: Cleaning and tokenising text data. This step is crucial as it prepares the raw survey text, removing any noise and irrelevant information. Tokenisation is particularly important because it breaks down the text into individual elements or 'tokens'. This makes the data more manageable and enables the model to more effectively analyze and understand the language patterns and sentiments in the responses.

2. **Topic Modeling**: Applying GSDMM for identifying topics within survey responses. We chose GSDMM specifically because it excels in analysing short texts, less than 50 words which is typical in surveys. This model helps in accurately extracting themes and sentiments from concise responses, providing a deeper understanding of the underlying topics in the survey data.

3. **Visualization**: Generating word clouds and bar charts to visualize the findings. These visualizations are essential for intuitively presenting the results. For instance, the word cloud below illustrates the most frequently mentioned terms in one of the survey categories, providing a quick visual representation of key themes.

![Example Word Cloud](https://github.com/Illias-b/Semantic-Analysis/assets/33836566/fe87d39e-482a-403d-9c56-945eee8eb874)


Each of these steps plays a vital role in transforming raw survey data into meaningful insights, enabling us to understand customer opinions and preferences better.

[View the Jupyter Notebook](https://github.com/Illias-b/NPS-Survey-Code.git)

## Overall Summary and Suggestions

Based on our analysis, we've uncovered key insights into what drives customer satisfaction and areas for improvement:

- Customers frequently mention signal quality and network services, especially in lower scores, indicating a major area of concern.
- Positive notes in higher scores revolve around good service and value for money, suggesting these are strong points.
- Improvement suggestions are mainly focused on enhancing signal coverage, service quality, and internet speed.

### Next Steps
1. **Improve Network Services**: Prioritize upgrading signal strength and network coverage.
2. **Maintain High-Quality Customer Service**: Continue investing in customer service to keep satisfaction levels high.
3. **Communicate Proactively**: Inform customers about improvements being made in response to their feedback.
4. **Deepen Analysis**: Conduct a more detailed analysis of feedback for specific insights.
5. **Customer Engagement**: Reach out to respondents for more in-depth feedback, especially those who gave lower scores.
6. **Regular Monitoring**: Continuously analyze customer feedback to track changes in sentiments and effectiveness of implemented improvements.

By addressing these areas, we aim to enhance overall customer satisfaction and loyalty.
