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
3. Clustering results were visualized in t-SNE plots.
4. The most popular game generes for each group of users were identified and analyzed.
5. An example of recommending games for target users were introduced.
Detailed coding, analysis and visualizations can be found in the jupyter notebook file, 'Final_Project.ipynb'.

## K-Means:
Parameter K (number of clusters) for K-Means algorithm was selected through "Elbow Plot" and average sihouette score: 
![image](https://user-images.githubusercontent.com/47155713/134284761-129629f9-1497-4155-8ab0-96da367afc24.png)
![image](https://user-images.githubusercontent.com/47155713/134284797-3e0d3f2f-3340-4531-87fe-e61d64cd61ee.png)

T-sne plot showing the clustering results with k = 4:
![image](https://user-images.githubusercontent.com/47155713/134284954-4bf69649-4131-4225-9b2c-2903f8cf84d9.png)

## Hierarchical:
Number of clusters and linkage were chosen by comparing sihouette score:
![image](https://user-images.githubusercontent.com/47155713/134285067-bc72fa1b-660f-4af0-948e-0ce5b484ce05.png)

T-sne plot showing the clustering results with num_clusters = 4 at ward linkage:
![image](https://user-images.githubusercontent.com/47155713/134285161-669c02df-ff4e-4699-abe5-cfe63979c689.png)



# Reference
- Chiu, J. (2017, May 16). Steam - What's your Game? NYC Data Science Academy. https://nycdatascience.com/blog/student-works/web-scraping/steam-whats-game/.
- Liang, Y. (2020, June 23). Steam Recommendation Systems. https://towardsdatascience.com/steam-recommendation-systems-4358917288eb.
- Zhong, R. (2020, April 27). Steam Game Market Data Analysis. Medium. https://medium.com/@ruochenzhong/steam-game-market-data-analysis-5c97ffe2dd6f.



