# Project Description
The task for this project is to build features for Steam users and classify the users into different groups so that we can recommend games to their potential players. The work can be divided into several parts: 
1. Collect Steam user and game datasets; 
2. Extract features for users; 
3. Apply stuitable unsupervised classification algorithms; 
4. Analyze group behaviros and recommend games.

# Data Collection
Three datasets were used in this project:
1. User activity dataset: https://www.kaggle.com/tamber/steam-video-games
2. Game basic information: https://www.kaggle.com/nikdavis/steam-store-games?select=steam.csv
3. Game tag/genre information: https://www.kaggle.com/nikdavis/steam-store-games?select=steamspy_tag_data.csv

All datasets collect data from web scraping Steam game stores and public Steam user profiles. Some datasets uses the Steamspy API, a third-part API that also scrapes data from Steam.

# Insights
1. K-Means and Hierarchical Clustering algorithms were applied.
2. Clustering results were visualized in t-SNE plots.
3. The most popular game generes for each group of users were identified and analyzed.
4. An example of recommending games for target users were introduced.

Detailed coding, analysis and visualizations can be found in the jupyter notebook file, 'Final_Project.ipynb'.

# Reference
- Chiu, J. (2017, May 16). Steam - What's your Game? NYC Data Science Academy. https://nycdatascience.com/blog/student-works/web-scraping/steam-whats-game/.
- Liang, Y. (2020, June 23). Steam Recommendation Systems. https://towardsdatascience.com/steam-recommendation-systems-4358917288eb.
- Zhong, R. (2020, April 27). Steam Game Market Data Analysis. Medium. https://medium.com/@ruochenzhong/steam-game-market-data-analysis-5c97ffe2dd6f.



