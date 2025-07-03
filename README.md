# UFood Marketing Campaign Optimization Project

## Introduction
UFood is Brazil’s leading food delivery app, operating in over a thousand cities and serving nearly one million customers annually. With a strong presence in the retail food sector, offering specialty wines, rare meats, exotic fruits, fish, and sweets, UFood’s continued growth depends on its ability to engage and retain a diverse customer base across multiple channels, including physical stores, catalogs, and its website.

Despite solid revenues and a healthy bottom line over the past three years, UFood faces stagnating profit growth, putting strategic pressure on the marketing department to maximize the return on campaign spending. In this context, leveraging data analytics is critical for identifying actionable insights and business opportunities that can revitalize marketing effectiveness and secure UFood’s position as market leader.

In this open-scope analysis, we draw on a rich dataset of over 2,200 customer records and 39 features spanning demographics, family status, income, purchasing channels, and detailed responses to five marketing campaigns. Our objectives are to:

Uncover the key drivers of campaign engagement and customer value.

Propose actionable, behavior-based customer segments.

Visualize patterns and cause-and-effect relationships to support both technical and business decision-makers.

Provide data-driven recommendations to optimize campaign performance and resource allocation.

By integrating advanced Python analytics (Pandas, Seaborn, Matplotlib) with clear business reasoning, this project delivers insights and recommendations that support both marketing strategy and UFood’s long-term growth.



## Key Insights & Visualizations

### Age Group Distribution
![Age Group Distribution](https://github.com/user-attachments/assets/ee114b04-c6c4-41d9-93cc-0199e0e2a6ce)

 
Most UFood customers are aged 31–70, and this group accounts for the highest spending. However, the most campaign-responsive groups are customers aged 23–30 and 71–80, suggesting a dual-targeting strategy for both engagement and revenue.

---

### Campaign Acceptance by Age Group
![Campaign Acceptance by Age Group](https://github.com/user-attachments/assets/50489088-caa7-409c-951f-391b78a0e60f)


Younger and older age brackets show higher acceptance rates for campaigns despite spending less, presenting an opportunity to boost overall conversions through segmented outreach.

---

### Campaign Acceptance by Number of Children
![Acceptance vs Number of Children](https://github.com/user-attachments/assets/3ef08bd6-06dc-47a7-93c0-f0b380850930)

  
Households with fewer or no children are both higher spenders and more likely to accept marketing campaigns, making them prime targets for campaign allocation.

---

### Campaign Acceptance by Education Level
![Acceptance vs Education](https://github.com/user-attachments/assets/ef30f072-0161-4ea1-bfe2-9c47d9aa0f91)

 
Education level does not correlate with campaign acceptance or spending, simplifying segmentation strategies for future campaigns.

---

### Marital Status Segmentation

**Marital Status Distribution**  
![Marital Status Count](https://github.com/user-attachments/assets/e59cd9fb-e671-41ec-8b9f-b04e07ce3164)

**Spending by Marital Status**  
![Spending by Marital Status](https://github.com/user-attachments/assets/7f0bf755-c2b3-4064-a32f-ff2101d51520)

**Acceptance by Marital Status**  
![Acceptance by Marital Status](https://github.com/user-attachments/assets/aabbf63c-1d85-4cbc-a058-e72f00187a21)


Single, married, and cohabiting individuals are the highest spenders. Widowed individuals, while spending less, show high campaign acceptance and could benefit from emotionally tailored campaigns.

---

### Purchase Channel Behavior

**Purchase Channel Distribution**  
![Purchase Channel Distribution](https://github.com/user-attachments/assets/2c160d8c-30de-428c-afac-f8ec1411f5b8)

  
Store purchases dominate, but catalog users are most responsive to campaigns. A recommended marketing mix is 40% catalog, 30% store, and 30% web.

---

### Multi-Channel Spending Correlation

**Total Spend vs Web Purchases**  
![MntTotal vs Web Purchases](https://github.com/user-attachments/assets/e22df67d-6159-4138-967b-70532a1e6969)

**Total Spend vs Catalog Purchases**  
![MntTotal vs Catalog Purchases](https://github.com/user-attachments/assets/5815afbc-3633-4329-9d43-51f511f63194)

**Total Spend vs Store Purchases**  
![MntTotal vs Store Purchases](https://github.com/user-attachments/assets/c0c1be8c-ff03-4b64-a1e5-ba0a4fd31abc)

  
Spending is positively correlated across all purchase channels, supporting a coordinated multi-channel marketing strategy.

---

### Correlation Heatmap

![Correlation Heatmap](https://github.com/user-attachments/assets/83708a2b-1c3f-4c0f-84ce-58923e8fb2e1)

  
Total spending and campaign acceptance are strongly correlated with spending on wine and meat products. Households with fewer children and high catalog/web activity are more likely to accept campaigns.

---

## Strategic Recommendations

- **Dual Audience Targeting:** Maintain focus on ages 31–70 for revenue and increase engagement among ages 23–30 and 71–80.
- **Optimize by Family Status:** Prioritize customers with fewer or no children for campaigns.
- **Channel Reallocation:** Distribute campaigns as 40% catalog, 30% store, 30% web.
- **Simplify Segmentation:** Avoid education-based targeting.
- **Relationship-Based Messaging:** Focus on single, married, and together segments; test emotionally driven campaigns for widowed customers.

---

## Conclusion

With robust analytics and clear segmentation, UFood can drive higher campaign ROI, increased customer engagement, and sustainable profit growth. This project provides a data-driven blueprint for smarter marketing and stronger customer relationships in a highly competitive market.

---
