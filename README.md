# Wisp-Health

Wisp Health is a medical insurance company serving thousands of customers across the United States. In 2019, the company launched a marketing campaign aimed at better understanding how to meet customer needs, focusing on categories such as wellness tips, plan affordability, and preventative care. As part of this effort, Wisp introduced four insurance plans, Bronze, Silver, Gold, and Platinum, each offering different premium levels and claim coverage rates.

Recently, Wisp hired a data team to analyze how these campaign categories impact customer signups and patient claims. The goal is to use these insights to guide the marketing team decisions about budget allocations for the upcoming year, with the overall objective of increasing sign ups and boosting brand awareness nationwide.

# Dataset
The dataset analyzed consisted of 3 tables, covering information about the customers, the campaign category that garnered the customers attention, and the claim that ended up being filed with Wisp Health:

![image](https://github.com/user-attachments/assets/06cdb1bc-e4d9-4e11-add0-4c89dd5638ba)

The  project was divided into 3 sections each with its own set of metrics that told the story of the data.

Marketing Metrics:

* Impressions: The number of times a campaign was seen, doesnt mean it was engaged, but does highlight visibility. 
* Click Through Rate (CTR): The percent of people who clicked Wisp's campaign, gauges what garners audience interest.
* Cost-Per Cick (CPC): The amount Wisp pays everytime the campaign is clicked, reflects efficiency of spending budget.

Signup Metrics:

* Signup Count: The total number of signups a campaign category gathered.
* Signup Rate: The percent of signups for a plan after customers viewed a campaging. 
* Cost Per Signup (CPS): The amount of money Wisp spends to acquire one signup.

Claim Metrics:

* Claim Amount: Total amount of claims payed out to customers, helps understand cost implifications of certain coverages.
* Avg Claim Amount: Average amount a single claim costs.

# Insights

### Marketing

* Despite receiving the fewest impressions, the 'Health for All' and 'Benefit Updates' categories had the highest click-through rates at 25% and 22% indicating strong audience interest and potential for greater impact.

* Golden Years Security had the highest cost-per-click at $0.68, yet it delivered the lowest click-through rate (1.41%) and one of the lowest impression counts, highlighting a costly and underperforming category.

* The Family Coverage category generated over 1.1 million impressions; however, data on clicks and cost is missing. To ensure accurate performance evaluation, it may be helpful to meet with the engineering team to investigate the cause of the missing data.

* Impressions and CTR show an inverse relationship, Health for All saw a 25% CTR with 170K impressions, while Tailored Health Plans had just 7% with 1.4M. This may indicate broad targeting, audience saturation, or creative fatigue.

### Signups

* The Health for All campaign had the highest signup rate at 2.08%,a 316% increase compared to the other categories, and the second-highest total signups (3,545). Despite lower volume, its rate was over 4x that of Coverage Matters (0.50%), suggesting its, creative strategy may offer valuable insights for other campaigns.

* Signups spiked in 2020, with Coverage Matters rising from 41 in February to 168 in April, likely driven by the onset of COVID-19 as consumers sought insurance amid growing health concerns.

* Higher cost per signup often aligns with lower signup rates. Benefit Updates had a 0.02% signup rate at $47.81 CPS, while Health for All reached a 2.08% at just $1.23 CPS. This suggests that more money is being spent to acquire fewer customers in certain categories, pointing to potential inefficiencies in current marketing practices.

### Claims

* Compare Health Coverage saw a 592% surge in claim amounts from $25K in July 2020 to $173K by July 2022, likely due to pandemic driven factors. In 2023, claims dropped 61% as conditions normalized, highlighting the need for sustainable growth strategies and improved demand forecasting.

* Compare Health Coverage' had the most money paid out in claims ($3.9 million) and the highest cost per claim ($410). This means it's one of the most expensive categories for the company and could be putting a strain on resources.

# Recommendations

* Our smallest campaign, Health for All, delivered the highest engagement with a 25% CTR and just $1 per signup, making it the most cost effective. We should increase its funding and use it as a benchmark for A/B testing to identify strategies that boost CTR and signup rates across other campaigns.

* More campaign experimentation will help identify marketing expansion challenges like budget allocation, acquisition vs retention, and competition that may not be visible at smaller scales. Through careful testing, we can pinpoint which campaigns can sustain strong performance as they grow and avoid overspending on those that fail to scale effectively.

* Golden Years Security is a costly and underperforming campaign, with a CPC of $0.68 and a signup cost of $176.73, alongside a 1.41% CTR and 0.01% signup rate. Wisp should either discontinue, pause, or restructure this campaign by overhauling its marketing measures to improve its efficiency, or reallocate its funds to more successful campaigns like Health for All.

* The Compare Health Coverage campaign is expensive, with $3.9M in total claims and $410 per claim. To improve cost efficiency, we should revise coverage options to reduce unnecessary claims and refine forecasting models to account for unpredictable events, enabling fund reallocation from underperforming to higher performing campaigns.

* Missing click and cost data for Family Coverage hinders our ability to accurately evaluate performance. We need to have a meeting with the engineering team to locate the missing data and see if any future gaps are preventable.

# Dashboard

**[Wisp Campaign Dashboard](https://public.tableau.com/views/RowHealth2/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

![](https://github.com/Juwan23D/Wisp-Health/blob/main/Dashboard%201.png)











