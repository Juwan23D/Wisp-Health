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

* Claim Amount: Total currency value of claims submitted by customers, helps understand cost implifications of certain coverages.
* Avg Claim Amount: average currency value of all claims submitted.

# Insights

### Marketing

* Despite receiving the fewest impressions, the 'Health for All' and 'Benefit Updates' categories had the highest click-through rates at 25% and 22% indicating strong audience interest and potential for greater impact.

* Golden Years Security had the highest cost-per-click at $0.68, yet it delivered the lowest click-through rate (1.41%) and one of the lowest impression counts, highlighting a costly and underperforming category.

* The Family Coverage category generated over 1.1 million impressions; however, data on clicks and cost is missing. To ensure accurate performance evaluation, it may be helpful to meet with the engineering team to investigate the cause of the missing data and recover any lost metrics.

* There appears to be an inverse relationship between impressions and CTR. For example, the 'Health for All' campaign achieved a 25% CTR with only 170,000 impressions, while 'Tailored Health Plans' had a significantly lower CTR of 7% despite reaching nearly 1.4 million impressions. This trend could point to factors such as overly broad targeting, audience saturation, or creative fatigue affecting engagement.





