## Forecasting Prediction Markets through Social Sentiment Analysis
### By Carter Alemania and Hieuson Dang

Description:
This project explores how social sentiment and/or news influences movements in prediction markets. Specifically we will analyze the sentiment extracted from social media/news and price changes on prediction platforms like Polymarket and how they may correlate with one another. We aim to determine whether or not changes in public sentiment can serve as an indicator for market movements. With this information we will learn more about how sentiment shapes market behaviour and improve forecasting accuracy. Through a combination of text-based sentiment analysis and changing market data, we hope to be able to determine whether the correlation between sentiment and market prices indicate a possible causal relationship.


Data Collection:

Author 1: Collects and prepocesses social media/news data that is related to the predicted market topics. This could include scraping tweets using relevant hashtags/keywords, cleaning it, and then running a sentiment analysis.

Author 2: Collects Polymarket data through public API, cleaning and formatting it to show market changes that align with the social media/news posts for modeling.

Model Plans:

Author 1: Implement sentiment and feature extraction models with classical sentiment scoring and/or LLM that serve as input features for the prediction models.

Author 2: Develop predictive models that takes the sentiment and connects it Polymarket price movements. Could start with linear regression and expand into non-linear models like Random Forest, XGBoost, and maybe NN to capture complex relationships.

Project Timeline:

[Nov 10] Collect data and make sure to pipeline + match dates from twitter to polymarket + make it scalable.

[Nov 25] Conduct exploratory data analysis, taking the sentimentscores and intial features to begin model development

[Dec 1] Build up and train predictive models, prepare visualizations and results for presentation

[Dec 11] Incorporate any feedback and changes needed before final project submission
