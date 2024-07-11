Project overview:
This project analyzes U-Food's marketing data to generate insights for improved marketing activities. Using Python (Pandas, Seaborn, Matplotlib), we examine customer behavior, spending, and campaign responsiveness across demographics.

Key Features:
The project uses data which includes diverse marketing and sales details essential for our analysis. 
Data description Marketing_Dictionary_Table -
![image](https://github.com/krishna-moukthika/Food-Marketing-Data-Analysis/assets/17616215/26b83b56-cdaf-4299-a6a1-dccb47fe817e)


Questions to be answered:
- How to Improve Purchases at Campaigns? 
- Which Customer Segment Should We Target? 

Analysis Highlights
We are trying to gather statistical data or find some type of correlations between certain segments and how much money they have been spending on specific campaigns.

Firstly, let's look at the age factor: 
From the following chart, we can conclude: 
The core audience for accepting campaigns right now is between 31-70 years old. Those aged 23-30 and 71 and up accept at higher rates.

![image](https://github.com/krishna-moukthika/Food-Marketing-Data-Analysis/assets/17616215/7699b3e8-5489-4c7f-857b-2ff2b2f4f24f)

![image](https://github.com/krishna-moukthika/Food-Marketing-Data-Analysis/assets/17616215/58462582-b5c1-4215-b27a-9d8812152963)


Looking at the relationship between having children and participating in campaigns: We can find that fewer kids = more likely to accept campaigns, and spend less money.

![image](https://github.com/krishna-moukthika/Food-Marketing-Data-Analysis/assets/17616215/7b2d6273-6e7e-43dd-b793-5f01fdb92388)


The level of education does not have a significant impact on participation in campaigns.

![image](https://github.com/krishna-moukthika/Food-Marketing-Data-Analysis/assets/17616215/1c19fa41-b0e1-4c8a-90dd-e979e98ef284)


We analyzed marital status and found that married and single individuals are spending more money than widowed and divorced individuals. We should focus on this segment.

![image](https://github.com/krishna-moukthika/Food-Marketing-Data-Analysis/assets/17616215/57f28f4b-4cd3-4a8e-af44-3c159d212de3)


After analyzed customer portrait we can take a look at purchasing channels:

Regarding people's purchasing channels, we can focus more on web purchases and store purchases.

![image](https://github.com/krishna-moukthika/Food-Marketing-Data-Analysis/assets/17616215/831c0219-7532-47fe-b99e-9e218178e7d1)


For the number of purchases made by people who accepted the campaigns,after performing regression analysis on the above three methods, we found:

All have a positive correlation: the more money spent, the more store purchases made.

From this, we can infer future directions: boost the higher percentage of catalog customers, or focus on in-store/web because they have more traffic.

![image](https://github.com/krishna-moukthika/Food-Marketing-Data-Analysis/assets/17616215/cdacd522-10a0-43e0-9e55-83cd60609cf5)
![image](https://github.com/krishna-moukthika/Food-Marketing-Data-Analysis/assets/17616215/b63ee253-9ec8-4f51-a2ff-4988176d8998)
![image](https://github.com/krishna-moukthika/Food-Marketing-Data-Analysis/assets/17616215/e54cc1a8-9a67-41a1-bfd0-57d5c28c53e1)


Conclusions from Data Exploration:
Age: 
Group 31-70:
- Spending more money
- Accepting fewer campaigns
Group 23-30, 71-85:
- Spending less money

Catalogue Users:
- More likely to accept campaigns.
- Spend more in person.

Recommended split: 40% catalog, 30% store, 30% web.
Focus on People with Fewer or No Kids 

Education:
- No significant impact; don't target any specific group for campaigns.

Marital Status:
- Married, single, and together individuals spend more money.
- Widowed and divorced individuals spend less.

Marketing Strategy:
Maintaining Sales Growth:
- Focus on middle-aged people, high earners, with no kids.
- Target different platforms with the split mentioned above (40% catalog, 30% store, 30% web).
Attracting New Users:
- Focus on individuals aged 21-30 and those 70 and up, as they accept campaigns at a higher rate.
