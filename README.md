# U_Food_Marketing_Campaign_Optimization_Project


<h2>Introduction</h2>

This project is a comprehensive analysis of customer behavior and marketing campaign effectiveness at UFood, Brazil's leading food delivery company. With a user base of several hundred thousand and nearly a million customers served annually, UFood is a significant player in the Brazilian food tech market. Despite strong revenues and a healthy bottom line in recent years, the company is currently facing stagnant profit growth. To reverse this trend, the marketing department is under pressure to optimize campaign performance and spending.

In this study, we leverage Python's data analytics capabilities (primarily through Pandas, Seaborn, and Matplotlib) to dissect customer data and campaign interaction information. Our primary objectives are to evaluate which segments of customers are most responsive to marketing efforts, uncover spending patterns across demographic groups, and propose practical, data-driven strategies to improve campaign success.

Project Overview

This analysis focuses on understanding the effectiveness of past marketing campaigns by exploring customer characteristics, purchase behavior, and campaign responses. The dataset contains over 2,200 records and 39 variables, capturing details such as income, age, education level, marital status, number of children, purchase channels (web, catalog, store), and responses to five different campaigns.

We begin with data cleaning to remove duplicates and construct useful new features, including total children, total campaign acceptances, and consolidated marital and education statuses. This step ensures that our insights are drawn from a clean, well-structured dataset.

We then perform exploratory data analysis to answer key business questions:

How do customer demographics impact campaign acceptance?

What kind of customers are more likely to respond positively to campaigns?

How does purchase behavior vary across different demographic groups?

What are the most effective marketing channels?

Through careful correlation analysis and visual exploration, we present targeted insights that can help optimize future marketing efforts.

Demographic Insights

One of the most compelling findings emerged from the age-based segmentation. The majority of UFood customers fall within the 31 to 70 age range, and this group also represents the highest total spending. Despite this, they are not the most campaign-responsive group. Younger customers aged 23 to 30 and older individuals aged 71 to 80 are more likely to accept marketing campaigns, although they spend less overall. This suggests a dual-targeting strategy: focus on middle-aged customers to maintain revenue and target younger and older users to boost campaign engagement.

Include Plot: Age group distribution (bar chart) and campaign acceptance by age group (point plot)

A further demographic dimension explored was the influence of children in a household. Regression analysis showed a clear inverse relationship: as the number of children increases, both total spending and campaign acceptance decrease. Customers with no or one child tend to spend more and are more receptive to marketing efforts, making them a prime target audience.

Include Plot: Regression plots for Total_Children vs. MntTotal and Total_Children vs. Accepted_Campaigns

Education level, interestingly, did not show a meaningful correlation with either spending or campaign acceptance. This suggests that UFood does not need to tailor campaigns based on education—simplifying segmentation strategies.

Include Plot: Regression plots for education_Status vs. MntTotal and education_Status vs. Accepted_Campaigns

In terms of marital status, married, single, and cohabiting individuals spend more money and represent a more financially valuable segment. Widowed and divorced individuals tend to spend less and are less likely to engage with campaigns. However, widowed individuals did show a higher-than-average campaign acceptance rate, hinting at potential in emotionally resonant campaigns.

Include Plot: Countplot of marital_Status_str and bar plot of MntTotal by marital status, with additional bar chart showing campaign acceptance percentage by marital status

Purchase Channel Behavior

Analyzing the types of purchases revealed that store purchases were the most common, followed by web and then catalog purchases. However, campaign-responsive customers were more likely to have used catalogs, suggesting that this channel may serve as a valuable touchpoint for conversion.

Include Plot: Bar chart of total purchases by type (web, catalog, store), both for all users and for users who accepted campaigns

Joint regression plots showed that spending is positively correlated across all three channels. The more someone spends, the more they tend to purchase across store, web, and catalog. This supports a multichannel approach to marketing, where each platform is nurtured to serve both discovery and conversion.

Include Plot: Jointplots with regression overlays of MntTotal vs. each of NumWebPurchases, NumCatalogPurchases, and NumStorePurchases

Based on this, we propose a split strategy for marketing distribution: 40% catalog, 30% store, and 30% web. This mix capitalizes on the high responsiveness of catalog users and the volume and accessibility of store and online shoppers.

Statistical Correlations and Predictive Patterns

Pearson correlation analysis highlighted several interesting patterns. There is a strong correlation between total spending and campaign acceptance, particularly in categories like wine and meat products. Higher income also correlates with campaign acceptance, though not as strongly.

Include Plot: Heatmap of top correlated features with Accepted_Campaigns

Features like the number of catalog and web purchases, along with spending on gold and regular products, all positively impact campaign acceptance. Negative correlations were observed with the number of children and recent inactivity (recency), reinforcing earlier insights.

Interestingly, the education_Status had only a minor correlation with campaign behavior, reaffirming the decision to not use this dimension for segmentation.

Key Recommendations

The findings from this analysis point toward several strategic recommendations for the marketing department:

Dual Audience Targeting:

Maintain a consistent focus on customers aged 31–70, as they contribute the most to revenue.

Launch targeted, high-engagement campaigns for users aged 23–30 and 71–80 to increase conversion.

Optimize by Family Status:

Target households with fewer or no children. These individuals are more responsive to campaigns and tend to spend more.

Reallocate Campaign Resources:

Use a 40/30/30 split for catalog/store/web campaigns.

Leverage catalog for campaign conversion while using web and store for scale.

Ignore Education Level:

Avoid education-based segmentation, as it does not affect campaign responsiveness or purchasing behavior.

Focus on Relationship-Based Segments:

Concentrate on single, married, and together segments, which have higher spending profiles.

Consider testing emotionally driven campaigns for widowed individuals.

