<h1>Bank Marketing Classifier Performance Evaluation</h1>

**Data Overview:** The dataset used in this project is sourced from the UCI Machine Learning repository and originates from a Portuguese banking institution. It comprises results from several direct marketing campaigns. The dataset includes information from 17 telephone marketing campaigns conducted between May 2008 and November 2010, with a total of 79,354 contacts made to persuade clients to subscribe to a bank term deposit. The success rate observed was 0.08.

**Business Objective:** The main objective of this project is to predict whether an individual will subscribe to a bank term deposit. This will help in better allocation and targeting of marketing resources towards clients who are more likely to subscribe.

**Data Problem:** The task involves fitting and tuning various classification models to categorize individuals as subscribers or non-subscribers. Models with high accuracy and recall will be utilized to predict the subscription status of new clients. Additionally, regression models will be fitted to identify the most important features that distinguish between the two groups, helping to profile subscribing clients and optimize resource allocation.

**Findings:** The five most important features for predicting a client's subscription status are the number of employees, the number of days since the most recent contact, marital status, loan status, and education. Key insights include:
- A lower number of employees is associated with higher subscription rates (5099 employees had the highest subscription count).
- Clients contacted 3-6 days ago are more likely to subscribe.
- Subscribers tend to be married or single, while divorced individuals are less likely to subscribe.
- Subscribers usually do not have a personal loan, whereas non-subscribers are more likely to have an unknown or positive loan status.
- The highest proportion of subscribers have education levels of university degree, high school, or professional course, while those with basic education levels (9y, 6y, 4y) have the lowest subscription rates.
