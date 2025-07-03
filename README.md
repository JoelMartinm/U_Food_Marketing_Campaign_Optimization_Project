# UFood Marketing Campaign Optimization Project

---

## Introduction

This project is a comprehensive analysis of customer behavior and marketing campaign effectiveness at UFood, Brazil's leading food delivery company. With a user base of several hundred thousand and nearly a million customers served annually, UFood is a significant player in the Brazilian food tech market. Despite strong revenues and a healthy bottom line in recent years, the company is currently facing stagnant profit growth. To reverse this trend, the marketing department is under pressure to optimize campaign performance and spending.

In this study, we leverage Python's data analytics capabilities (primarily through Pandas, Seaborn, and Matplotlib) to dissect customer data and campaign interaction information. Our primary objectives are to evaluate which segments of customers are most responsive to marketing efforts, uncover spending patterns across demographic groups, and propose practical, data-driven strategies to improve campaign success.

## Project Overview

This analysis focuses on understanding the effectiveness of past marketing campaigns by exploring customer characteristics, purchase behavior, and campaign responses. The dataset contains over 2,200 records and 39 variables, capturing details such as income, age, education level, marital status, number of children, purchase channels (web, catalog, store), and responses to five different campaigns.

We begin with data cleaning to remove duplicates and construct useful new features, including total children, total campaign acceptances, and consolidated marital and education statuses. This step ensures that our insights are drawn from a clean, well-structured dataset.

We then perform exploratory data analysis to answer key business questions:

* How do customer demographics impact campaign acceptance?
* What kind of customers are more likely to respond positively to campaigns?
* How does purchase behavior vary across different demographic groups?
* What are the most effective marketing channels?

Through careful correlation analysis and visual exploration, we present targeted insights that can help optimize future marketing efforts.


## Demographic Insights

One of the most compelling findings emerged from the age-based segmentation. The majority of UFood customers fall within the 31 to 70 age range, and this group also represents the highest total spending. Despite this, they are not the most campaign-responsive group. Younger customers aged 23 to 30 and older individuals aged 71 to 80 are more likely to accept marketing campaigns, although they spend less overall. This suggests a dual-targeting strategy: focus on middle-aged customers to maintain revenue and target younger and older users to boost campaign engagement.

Age Group Distribution
![download](https://github.com/user-attachments/assets/ee114b04-c6c4-41d9-93cc-0199e0e2a6ce)


Campaign Acceptance by Age Group
![download](https://github.com/user-attachments/assets/50489088-caa7-409c-951f-391b78a0e60f)

One of the most compelling findings emerged from the age-based segmentation. The majority of UFood customers fall within the 31 to 70 age range, and this group also represents the highest total spending. Despite this, they are not the most campaign-responsive group. Younger customers aged 23 to 30 and older individuals aged 71 to 80 are more likely to accept marketing campaigns, although they spend less overall. This suggests a dual-targeting strategy: focus on middle-aged customers to maintain revenue and target younger and older users to boost campaign engagement.

Spending vs Number of Children

Acceptance vs Number of Children
![download](https://github.com/user-attachments/assets/3ef08bd6-06dc-47a7-93c0-f0b380850930)

Education level, interestingly, did not show a meaningful correlation with either spending or campaign acceptance. This suggests that UFood does not need to tailor campaigns based on education—simplifying segmentation strategies.

Acceptance vs Education
![download](https://github.com/user-attachments/assets/ef30f072-0161-4ea1-bfe2-9c47d9aa0f91)

In terms of marital status, married, single, and cohabiting individuals spend more money and represent a more financially valuable segment. Widowed and divorced individuals tend to spend less and are less likely to engage with campaigns. However, widowed individuals did show a higher-than-average campaign acceptance rate, hinting at potential in emotionally resonant campaigns.

![Marital Status Count](https://github.com/user-attachments/assets/e59cd9fb-e671-41ec-8b9f-b04e07ce3164)
![Spending by Marital Status](https://github.com/user-attachments/assets/7f0bf755-c2b3-4064-a32f-ff2101d51520)
![Acceptance by Marital Status](https://github.com/user-attachments/assets/aabbf63c-1d85-4cbc-a058-e72f00187a21)


---

## Purchase Channel Behavior

Analyzing the types of purchases revealed that store purchases were the most common, followed by web and then catalog purchases. However, campaign-responsive customers were more likely to have used catalogs, suggesting that this channel may serve as a valuable touchpoint for conversion.

![Purchase Channel Distribution](https://github.com/user-attachments/assets/2c160d8c-30de-428c-afac-f8ec1411f5b8)


Joint regression plots showed that spending is positively correlated across all three channels. The more someone spends, the more they tend to purchase across stores, the web, and the catalog. This supports a multichannel approach to marketing, where each platform is nurtured to serve both discovery and conversion.

![MntTotal vs Web Purchases](https://github.com/user-attachments/assets/e22df67d-6159-4138-967b-70532a1e6969)
![MntTotal vs Catalog Purchases](https://github.com/user-attachments/assets/5815afbc-3633-4329-9d43-51f511f63194)
![MntTotal vs Store Purchases](https://github.com/user-attachments/assets/c0c1be8c-ff03-4b64-a1e5-ba0a4fd31abc)


---

Based on this, we propose a split strategy for marketing distribution: 40% catalog, 30% store, and 30% web. This mix capitalizes on the high responsiveness of catalog users and the volume and accessibility of store and online shoppers.


## Statistical Correlations and Predictive Patterns

Pearson correlation analysis highlighted several interesting patterns. There is a strong correlation between total spending and campaign acceptance, particularly in categories like wine and meat products. Higher income also correlates with campaign acceptance, though not as strongly.

![Correlation Heatmap](https://github.com/user-attachments/assets/83708a2b-1c3f-4c0f-84ce-58923e8fb2e1)


Features like the number of catalog and web purchases, along with spending on gold and regular products, all positively impact campaign acceptance. Negative correlations were observed with the number of children and recent inactivity (recency), reinforcing earlier insights.

Interestingly, the education status had only a minor correlation with campaign behavior, reaffirming the decision not to use this dimension for segmentation.

---

## Key Recommendations

The findings from this analysis point toward several strategic recommendations for the marketing department:

### 1. Dual Audience Targeting

* Maintain a consistent focus on customers aged 31–70, as they contribute the most to revenue.
* Launch targeted, high-engagement campaigns for users aged 23–30 and 71–80 to increase conversion.

### 2. Optimize by Family Status

* Target households with fewer or no children. These individuals are more responsive to campaigns and tend to spend more.

### 3. Reallocate Campaign Resources

* Use a 40/30/30 split for catalog/store/web campaigns.
* Leverage the catalog for campaign conversion while using the web and store for scale.

### 4. Ignore Education Level

* Avoid education-based segmentation, as it does not affect campaign responsiveness or purchasing behavior.

### 5. Focus on Relationship-Based Segments

* Concentrate on single, married, and together segments, which have higher spending profiles.
* Consider testing emotionally driven campaigns for widowed individuals.

---

## Conclusion

This project provides a data-driven foundation to optimize UFood's marketing campaigns. By analyzing customer data across various dimensions, we identified which segments are most profitable and most likely to respond to marketing efforts. Implementing the insights from this report can help UFood increase engagement, improve conversion rates, and ultimately grow its bottom line.

The campaign's success at UFood does not solely depend on age or income but is a multifactorial result of behavioral patterns, purchasing habits, and family dynamics. With refined targeting and channel strategies, UFood is well-positioned to scale its marketing success in a competitive food delivery landscape.

---
