
# UFood Marketing Campaign Optimization Project


---

## Introduction

This project is a comprehensive analysis of customer behavior and marketing campaign effectiveness at UFood, Brazil's leading food delivery company. With a user base of several hundred thousand and nearly a million customers served annually, UFood is a significant player in the Brazilian food tech market. Despite strong revenues and a healthy bottom line in recent years, the company is currently facing stagnant profit growth. To reverse this trend, the marketing department is under pressure to optimize campaign performance and spending.

In this study, we leverage Python's data analytics capabilities (primarily through Pandas, Seaborn, and Matplotlib) to dissect customer data and campaign interaction information. Our primary objectives are to evaluate which segments of customers are most responsive to marketing efforts, uncover spending patterns across demographic groups, and propose practical, data-driven strategies to improve campaign success.

## Project Overview

This analysis focuses on understanding the effectiveness of past marketing campaigns by exploring customer characteristics, purchase behavior, and campaign responses...
]# Project Overview

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

![Age Group Distribution](https://postimg.cc/your-link-here)
![Campaign Acceptance by Age Group](https://postimg.cc/your-link-here)

One of the most compelling findings emerged from the age-based segmentation. The majority of UFood customers fall within the 31 to 70 age range, and this group also represents the highest total spending. Despite this, they are not the most campaign-responsive group. Younger customers aged 23 to 30 and older individuals aged 71 to 80 are more likely to accept marketing campaigns, although they spend less overall. This suggests a dual-targeting strategy: focus on middle-aged customers to maintain revenue and target younger and older users to boost campaign engagement.

![Spending vs Number of Children](https://postimg.cc/your-link-here)
![Acceptance vs Number of Children](https://postimg.cc/your-link-here)

Education level, interestingly, did not show a meaningful correlation with either spending or campaign acceptance. This suggests that UFood does not need to tailor campaigns based on education—simplifying segmentation strategies.

![Acceptance vs Education](https://postimg.cc/your-link-here)

In terms of marital status, married, single, and cohabiting individuals spend more money and represent a more financially valuable segment. Widowed and divorced individuals tend to spend less and are less likely to engage with campaigns. However, widowed individuals did show a higher-than-average campaign acceptance rate, hinting at potential in emotionally resonant campaigns.

![Marital Status Count](https://postimg.cc/your-link-here)
![Spending by Marital Status](https://postimg.cc/your-link-here)
![Acceptance by Marital Status](https://postimg.cc/your-link-here)

---

## Purchase Channel Behavior

Analyzing the types of purchases revealed that store purchases were the most common, followed by web and then catalog purchases. However, campaign-responsive customers were more likely to have used catalogs, suggesting that this channel may serve as a valuable touchpoint for conversion.

![Purchase Channel Distribution](https://postimg.cc/your-link-here)

Joint regression plots showed that spending is positively correlated across all three channels. The more someone spends, the more they tend to purchase across stores, the web, and the catalog. This supports a multichannel approach to marketing, where each platform is nurtured to serve both discovery and conversion.

![MntTotal vs Web Purchases](https://postimg.cc/your-link-here)
![MntTotal vs Catalog Purchases](https://postimg.cc/your-link-here)
![MntTotal vs Store Purchases](https://postimg.cc/your-link-here)

---

Based on this, we propose a split strategy for marketing distribution: 40% catalog, 30% store, and 30% web. This mix capitalizes on the high responsiveness of catalog users and the volume and accessibility of store and online shoppers.


## Statistical Correlations and Predictive Patterns

Pearson correlation analysis highlighted several interesting patterns. There is a strong correlation between total spending and campaign acceptance, particularly in categories like wine and meat products. Higher income also correlates with campaign acceptance, though not as strongly.

![Correlation Heatmap](https://postimg.cc/your-link-here)

Features like the number of catalog and web purchases, along with spending on gold and regular products, all positively impact campaign acceptance. Negative correlations were observed with the number of children and recent inactivity (recency), reinforcing earlier insights.

Interestingly, the education_Status had only a minor correlation with campaign behavior, reaffirming the decision not to use this dimension for segmentation.

---

## Key Recommendations

1. **Dual Audience Targeting**  
2. **Optimize by Family Status**  
3. **Reallocate Campaign Resources**  
4. **Ignore Education Level**  
5. **Focus on Relationship-Based Segments**  

---

## Conclusion

This project provides a data-driven foundation to optimize UFood's marketing campaigns. By analyzing customer data across various dimensions, we identified which segments are most profitable and most likely to respond to marketing efforts. Implementing the insights from this report can help UFood increase engagement, improve conversion rates, and ultimately grow its bottom line.

The campaign's success at UFood does not solely depend on age or income but is a multifactorial result of behavioral patterns, purchasing habits, and family dynamics. With refined targeting and channel strategies, UFood is well-positioned to scale its marketing success in a competitive food delivery landscape.

---
