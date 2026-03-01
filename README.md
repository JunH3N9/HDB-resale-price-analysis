Intro

As a year long intern at HDB, I frequently get funny questions from relatives and friends. Do you work at the construction site? Can you help me get a BTO? Which BTO is the best to get?

While the first 2 are silly questions, I did start to think about that last question. What really determines if a BTO is the "best". By my definition, the "best" would be the one with the most return on investment (ROI). But what were the factors that determines the value of a BTO? How could I use those factors to predict the resale price? After further research, I found that there were publicly available data on HDB resale transactions on data.gov.sg.

I employed statistical and geospatial analysis to understand and find trends in the resale prices. I was also reminded of a module I took called "AI Tools & Techniques for Cybersecurity". There, I learnt the basics of training a machine learning model. Thus, I embarked on the journey to develop a machine learning model to predict the potential resale price of a HDB flat.

A once light hearted question has been made into a machine learning model that is able to provide insights into the current HDB resale market.

I hope this project will be as funny to you as it was to me!

Project objectives:

- Predict HDB resale prices with transaction data and machine learning
- Identify factors that influence property values
  
Features

- Data analysis: Statistical and geospatial exploration of HDB transactions
- Machine learning: Predictive models trained on historical data

Key Findings:

- Ridge regression model achieved 81.6% variance explanation (R²) in predicting resale prices
- Floor area is a strong price driver — each additional sqm adds ~$936 to resale value
- Proximity to schools had minimal impact, suggesting it is not a priority for buyers
- HDB prices exhibit heteroscedasticity — higher-priced flats are harder to predict accurately, reflecting real-world market complexity

Limitations:

- Dataset limited to 2017 onwards
- Interior factors (renovations etc) not accounted for
- ROI prediction not possible without original purchase price
