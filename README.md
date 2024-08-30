# Week-1
**Financial news and stock price**
This project focuses on the detailed analysis of a large corpus of financial news data to discover correlations between news sentiment and stock market movements. This challenge is designed to refine your skills in Data Engineering (DE), Financial Analytics (FA), and Machine Learning Engineering (MLE).

Nova Financial Solutions aims to enhance its predictive analytics capabilities to significantly boost its financial forecasting accuracy and operational efficiency through advanced data analysis. As a Data Analyst at Nova Financial Solutions,  your primary task is to conduct a rigorous analysis of the financial news dataset. The focus of your analysis should be two-fold:

Sentiment Analysis: Perform sentiment analysis on the ‘headline’ text to quantify the tone and sentiment expressed in financial news. This will involve using natural language processing (NLP) techniques to derive sentiment scores, which can be associated with the respective 'Stock Symbol' to understand the emotional context surrounding stock-related news.

Correlation Analysis: Establish statistical correlations between the sentiment derived from news articles and the corresponding stock price movements. This involves tracking stock price changes around the date the article was published and analyzing the impact of news sentiment on stock performance. This analysis should consider the publication date and potentially the time the article was published if such data can be inferred or is available.

Your recommendations should leverage insights from this sentiment analysis to suggest investment strategies. These strategies should utilize the relationship between news sentiment and stock price fluctuations to predict future movements. The final report should provide clear, actionable insights based on your analysis, offering innovative strategies to use news sentiment as a predictive tool for stock market trends.


Financial News and Stock Price Integration Dataset

FNSPID (Financial News and Stock Price Integration Dataset), is a comprehensive financial dataset designed to enhance stock market predictions by combining quantitative and qualitative data.

The structure of the data is as follows

headline: Article release headline, the title of the news article, which often includes key financial actions like stocks hitting highs, price target changes, or company earnings.
url: The direct link to the full news article.
publisher: Author/creator of article.
date: The publication date and time, including timezone information(UTC-4 timezone).
stock: Stock ticker symbol (unique series of letters assigned to a publicly traded company). For example (AAPL: Apple)

Task-1:
1. Set up a Python environment.
2. Create a GitHub repository to host all the code.
3. Create a new branch named task-1 for day 1 analysis.
4. Conduct Exploratory Data Analysis (EDA) which includes:
    Descriptive Statistics
    Text Analysis (Sentiment Analysis and Topic Modeling)
    Time Series Analysis
    Publisher Analysis

Task-2:
1. Merge the relevant changes from task-1 into the main branch.
2. Create a new branch named task-2 for ongoing development.
3. Load and preprocess the data.
4. Define date ranges and retrieve stock market data.

