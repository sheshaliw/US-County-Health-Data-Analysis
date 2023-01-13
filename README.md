# US-County-Health-Data-Analysis
[Clustering &amp; Classification] Investigated County data to locate clusters of with similar health outcomes and behaviors using K-means Clustering and developed a predictive model to recognize key factors that influence both these health outcomes, and other major factors for premature deaths via Linear Regression and Decision Trees.

Overview : 
On https://www.countyhealthrankings.org/ , the University of Wisconsin’s Population Health Institute has published rankings of all 3142 counties in the US by their health outcomes and behaviors. In this assignment, you will apply clustering and classification techniques to the data from 2021 to determine if there are interesting groupings of counties with similar health outcomes and behaviors, and develop a predictive model to see which factors influence health outcomes. Individuals and governments can use such a model to improve public health outcomes.

Tasks
The data file for you to analyze is in the assignment in Canvas and also available at
https://www.countyhealthrankings.org/sites/default/files/media/document/analytic_data2021 .csv . Documentation of the measures in the data file is in https://www.countyhealthrankings.org/sites/default/files/media/document/2021%20Analyti% 20Documentation.pdf . Use only the columns with the words “rawvalue” (e.g. v001_rawvalue) for your features; you don’t need to analyze the numerators, denominators, confidence intervals r for this assignment.

Also predictive features include only the health factors (e.g. smoking) and not the outcome variables (e.g. premature death, poor or fair health, poor mental health or low birthweight) - otherwise that is data leakage. It is OK to leave out features that are not things that could reasonably be changed by public policy; you should just explain what they are doing and note their assumptions.


The remainder of https://www.countyhealthrankings.org/ is worth exploring to obtain more context about how this data is collected and used to improve public health. You should turn in a Jupyter notebook with code and results including visualizations to answer the following questions (20 points total for the assignment):

1) What steps did you use for exploratory data analysis and subsequent data preparation on this data set? This should address summary statistics and handling of missing data and outliers 
2) Are there any noteworthy groupings of counties that have similar health outcomes and behaviors? You should use an unsupervised learning technique like clustering and show how you decided on the number of clusters. 
3) What are the five most important factors predicting premature death as shown by this data? In this data set, premature death is defined as the number of years of potential life lost before age 75 per 100,000 population. Develop two models (using different
supervised learning approaches) to answer this question.
4) Which of the two models do you believe is more accurate and how can you tell? Where would you focus public health efforts to reduce premature deaths in Allegheny County?

Hints/Suggestions:
1. Describe how you have chosen to handle outliers and missing values
2. Include visualizations such as histograms and boxplots where appropriate in describing
the results of EDA
3. Describe how the findings from EDA influence your choice of data preparation and
choice of modeling techniques
4. For the supervised learning models, consider how you will select the features and
measure accuracy of the resulting models. How can you avoid overfitting?

 
   
