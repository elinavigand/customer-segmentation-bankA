# Customer Segmentation for Bank A

### Project Objective: 
Identify most useful customer segment based on their purchasing patterns and behaviors, to tailor marketing campaigns that boost engagement and retention.

### Team:
Elina Vigand, Tosin Aderanti, Anurag Chowdhury


## Step 1: Unveiling the Data

**Data Source:** Internally gathered credit card transaction data
**Data Size:** 8500 customers and 18 features across 6 months
**Feature types:**
- Customer_id (object),
- 17 numeric features (int64, float64)
**Missing values:**
- Credit Limit: 1 missing value
- Minimum Payments: 298 missing values
**Data Integrity:** No duplicates identified

## Step 2: Identifying Clusters

![Identifying optimal number of clusters](https://github.com/elinavigand/customer-segmentation-bankA/blob/main/images/Final-Clusters.png)

## Step 3: Cluster Insights

**Based on our analysis, the optimal number of clusters is 3:**
- Segment 1 "Yuppies": Young, upwardly mobile professionals with a high income and a propensity for spending.
- Segment 2 "Conservatives": Cautious spenders who mostly pay off balances in full. They have a preference for cash advances and have low credit utilization rate.
- Segment 3 "Core Base": Stable and reliable customers who form the foundation of the customer base.

## Step 4: Recommendations

The "Conservatives" segment is characterized by low purchase amounts, a preference for cash advances, and a low credit utilization rate. 

**Our strategy for the Conservatives segment is to:**

- Reduce credit limit to free up capital to redeploy it on growth or higher credit limits for the Yuppies
- As The Conservatives seem to be using the Credit Card as an ATM Debit Card which is a very expensive method to get access to Cash. So we recommend educating them about the benefits of using debit cards and encourage them to use debit cards for cash withdrawals instead of their credit cards.
- Cross-sell debit cards to offer them an alternative payment option that aligns with their preference for cash transactions.
Slide 12

The "Yuppies" segment is the most profitable segment for the Bank A. 
They spend the most and have the highest use of the credit limit. 

**To further enhance our relationship with this segment and drive their engagement, we propose implementing the following strategies:**

- Increase credit limit to expand their spending power and allow them to make larger purchases.
- Implement rewards programs and cashback benefits that align with their purchasing habits.
- Personalized marketing campaigns that resonate with their unique interests and preferences.

By implementing these strategies, we can effectively engage with the Yuppies segment, foster their loyalty, and drive their continued spending, ultimately maximizing their contribution to our company's growth and profitability.


## Getting started
1. Clone this repo (for help see this [tutorial](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)).
2. Raw Data is being kept [here](https://github.com/elinavigand/customer-segmentation-bankA/tree/main/data) within this repo.
3. Data processing/transformation scripts are being kept [here.](https://github.com/elinavigand/customer-segmentation-bankA/tree/main/notebooks)
4. Data presentation example for clients [here.](https://github.com/elinavigand/customer-segmentation-bankA/blob/main/CustomerSegmentation_BankA_PitchDeck.pdf)

## Contributing Members
Tosin Aderanti

Anurag Chowdhury

[Elina Vigand](https://github.com/elinavigand)

