
# Coupon Acceptance Analysis

This project explores customer behavior in response to different types of coupons, focusing on identifying which characteristics are associated with higher acceptance rates. The dataset contains information about drivers, their trips, passenger type, age, gender, occupation, income, and visit frequency to various locations such as bars, coffee houses, and restaurants. The main goal is to determine patterns in coupon acceptance and understand which passengers are more likely to use specific coupons.

The analysis begins by filtering the dataset for a specific coupon type, such as Bar or Coffee House, and converting categorical visit frequencies to numeric values for easier comparison. Age and income are also converted to numeric values to allow grouping and statistical analysis. Acceptance rates are computed overall and for subgroups, such as frequent versus infrequent visitors, younger versus older drivers, and passengers traveling alone versus with children.

For Bar coupons, frequent bar-goers, younger adults, and drivers traveling without children show higher acceptance rates. For Coffee House coupons, similar patterns emerge: those who visit coffee shops more often, are under 35, and travel alone or with friends are more likely to accept the coupon. Income and occupation can also influence acceptance, especially when the coupon aligns with the driver’s lifestyle.

These observations suggest that coupon acceptance is driven by both personal habits and situational factors like passenger type. The methodology can be applied to any coupon type to identify responsive customer segments. Future work could include predictive modeling to estimate the likelihood of coupon acceptance and visualizations to summarize patterns across multiple features. Overall, this analysis provides insights into targeting coupons effectively to maximize engagement.

