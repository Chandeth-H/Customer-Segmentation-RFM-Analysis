# Customer-Segmentation-RFM-Analysis

## Understanding RFM Analysis

RFM Analysis is essential for effective customer segmentation, focusing on three critical dimensions: Recency, Frequency, and Monetary Value.

1. Recency: This metric assesses the time since a customer's last purchase. If a customer bought something recently, it shows they are active and more likely to respond to our messages and offers.

2. Frequency: This measures how often a customer makes purchases over a specified period. Customers who buy regularly are usually more loyal and satisfied. On the other hand, those who don’t buy often might need some encouragement to shop again.

3. Monetary: This evaluates the total amount a customer has spent on purchases. By looking at this, we can find our most valuable customers who help bring in revenue. Customers who spend less might need special offers to get them to buy more.

## Project Overview

This project conducts an RFM (Recency, Frequency, Monetary) analysis on a transactional dataset from a UK-based online retail company. The dataset includes all transactions occurring between December 1, 2010, and December 9, 2011, primarily focusing on unique all-occasion gifts. Many customers in this dataset are wholesalers.

## Data Source

The dataset used for this analysis is available on Kaggle.

https://www.kaggle.com/code/yugagrawal95/rfm-analysis/input

![image](https://github.com/user-attachments/assets/afd0bf50-c19f-4469-928e-bcf37c744353)


## Analysis & Insight

### Sales Trend

![image](https://github.com/user-attachments/assets/41feab06-949d-4009-8e5c-57fbae5e88c8)

This line graph shows a fluctuating trend in total sales over the months from December 2010 to December 2011. Sales start at around 500,000 in December 2010, indicating a moderate beginning. There are several ups and downs throughout the months, with notable peaks and troughs. For instance, sales dip around mid-2011, suggesting a possible seasonal variation or other market influences. A significant spike occurs in November 2011, where total sales peak at just under 1,000,000. This could point to a successful marketing campaign, product launch, or seasonal demand. In December 2011, due to lack of data, we can't determine the trend of this whole month.


### RFM Insight

![image](https://github.com/user-attachments/assets/3bf538cd-13aa-4675-b13f-8ddbb50dee40)



1. Recency:
- Champions: This segment shows the lowest recency (5.4 days), indicating they have interacted very recently and are highly engaged customers.
- Hibernating and At Risk: These segments have significantly higher recency values (215.9 and 153.5 days, respectively), suggesting that these customers haven't engaged with the brand for a long time and may need reactivation efforts.

2. Frequency:
- Champions exhibit the highest frequency (12.2 purchases on average), showing they are frequent buyers, which is ideal for business.
- Can't Lose customers also show high frequency (8.5 purchases), indicating they are valuable to the business and should be nurtured.
- The New Customers segment has the lowest frequency (1 purchase), highlighting the potential for increased engagement and retention strategies.

3. Monetary:
- Champions lead in monetary value, with an average spend of $6,139.73, indicating they contribute significantly to revenue.
- Can't Lose customers also have high monetary value ($2,841.44), suggesting they are high-value customers worth focusing on.
- In contrast, Promising customers have the lowest average spend ($264.76), indicating they may need more incentives to increase their purchase value.

### Segment Analysis

1. About to Sleep
- Recency Mean: 52.43 (indicates customers haven't purchased in a while)
- Frequency Mean: 1.0 (low frequency of purchases)
- Monetary Mean: $1,431.07 (moderate spending)
- Count: 324
- Insight: This segment is at risk of becoming inactive. Targeted re-engagement strategies could help revitalize interest.

2. At Risk
- Recency Mean: 153.45 (customers haven't purchased recently)
- Frequency Mean: 1.0 (low purchase frequency)
- Monetary Mean: $1,036.47 (decent spending)
- Count: 532
- Insight: These customers are at a critical point. Immediate action is needed to prevent churn, such as personalized offers or targeted marketing campaigns.

3. Can't Lose
- Recency Mean: 30.51 (recently engaged customers)
- Frequency Mean: 2.0 (low frequency but engaged)
- Monetary Mean: $2,247.51 (high spending)
- Count: 59
- Insight: This segment represents high-value customers who should be nurtured with loyalty programs and personalized communication to maintain engagement.

4. Champions
- Recency Mean: 5.39 (very recent purchases)
- Frequency Mean: 12.0 (high purchase frequency)
- Monetary Mean: $2,677.56 (highest spending)
- Count: 577
- Insight: These customers are the most valuable. Strategies should focus on retention and loyalty rewards to keep them engaged.

5. Hibernating
- Recency Mean: 112.29 (significant time since last purchase)
- Frequency Mean: 1.0 (low frequency)
- Monetary Mean: $271.65 (low spending)
- Count: 170
- Insight: This segment may need reactivation strategies to encourage spending again.

6. Loyal Customers
- Recency Mean: 32.71 (recent purchases)
- Frequency Mean: 6.0 (moderate frequency)
- Monetary Mean: $2,646.68 (high spending)
- Count: 742
- Insight: These customers are loyal and should be rewarded with exclusive offers to reinforce their loyalty.

7. Need Attention
- Recency Mean: 61.61 (some time since last purchase)
- Frequency Mean: 2.0 (moderate frequency)
- Monetary Mean: $1,142.80 (decent spending)
- Count: 324
- Insight: This segment needs targeted marketing efforts to boost engagement and spending.

8. New Customers
- Recency Mean: 12.61 (recently acquired customers)
- Frequency Mean: 1.0 (low frequency)
- Monetary Mean: $213.19 (low spending)
- Count: 86
- Insight: Focus on onboarding these customers effectively to encourage repeat purchases.

9. Potential Loyalists
- Recency Mean: 16.35 (recent purchases)
- Frequency Mean: 1.0 (low frequency)
- Monetary Mean: $213.19 (low spending)
- Count: 86
- Insight: This segment has potential. Implementing loyalty programs could help convert them into loyal customers.

10. Promising
- Recency Mean: 22.83 (recently engaged)
- Frequency Mean: 1.0 (low frequency)
- Monetary Mean: $213.19 (low spending)
- Count: 86
- Insight: This segment needs encouragement to increase spending and frequency of purchases.

## Conclusion

The RFM analysis identifies key customer segments, allowing for tailored marketing strategies that enhance customer engagement, retention, and revenue growth. By focusing efforts on high-value segments like Champions and Can't Lose, while developing strategies for lower-value segments, the business can optimize its customer relationships and overall performance.




