# Free to Play SLG Mobile Game Data Analysis and ML Pay Prediciton

This project and it's dataset was designed for a ML competition. Goal is to predicte 45 day sales of the game using train dataset. Due to confidentiality, I can't share the dataset and the game's name.

## DATA Description

Column Names (only about those with confusion)
- xxxx_add_value = items purchased
- xxxx_reduce_value = items used
- PVP = people vs peple
- PVE = people vs environment
- pay_price = amount users paid within 7 days
- prediciton_pay_price = amount users paid within 45 days


### Analysis Framework

Note: Analysis is not based on conventional AARRR model or PRAPA model due to limitation of the dataset given.
- 1.New User Analysis
    - 1.1 Registration metrics by Month/Weekday/Day
    - 1.2 New user conversion Rate
    - 1.3 New user active analysis
- 2.Revenue Analysis
    - 2.1 Key Metrics: APPU/ARPPU
    - 2.2 Pay frequency per day
    - 2.3 Pay conversion rate vs. Building stronghold level
- 3.Content Analysis
    - 3.1 Paid user vs unpaid user under PVP & PVE mode
    - 3.2 Resource and Acceleration Item Usage
    - 3.3 Whales vs Others
- 4.Conclusion and Recommendation

### Machine Learning Framework
    User Classification updated using K-means clustering. 
    Prediction TBC

## Acknowledgments

* Inspiration: Ths analysis methodology was inspired by a book written in Chinese 《The Art of Game Data Analysis》/《游戏数据分析艺术》 and other public articles about this competition. 


