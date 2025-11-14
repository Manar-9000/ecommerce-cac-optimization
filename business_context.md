# E-Commerce Customer Acquisition Optimization - Business Context

## Industry Overview

The e-commerce sector in Brazil is the largest and one of the fastest growing digital markets in latin America. This massive market size presents a strong growth opportunity for RetailCo. However, this competivtive enviornment is sophisticated and highly saturated, with big internation competiters like Amazon for exmaple. This competion combined with rising digital advertising costs, is the main driver behind the current callenge of increasing Customer Acquisition Cost (CAC). Brazilan consumers are highly price-senstive and expecet a smooth, trustworthy expericne, often reffering to loacal payments methods such as PIx and Onstallment plans. Any stragegy to reduce CAC must be aligned with delivering value and improving the customer expericne in this competitve market, mobile-first landscape. 

## Business Problem

RetailCo faces a critical challenge of increasing Customer Aquisition Costs (CAC) across its marketing porfolio, resulting in uncertain profitability and ineffiecent resourcess allocation. 

The current spending does not provide a clear visibility into which aquision channels yeild the highest value customers. There is a risk that the cost to aquire a customer is approching or exceeding that customer Life Value (LTV), threatinig the company's growth stragey. 

The goal of this analysis is to model and compare the LTV and aquesition metrics of different customer segments to find the most efficient aquisition strategies, and providing actionable recommendationts lower CAC and to improve the iveral LTV:CAC ratio. 

## Stakeholder Concerns

The main motuvatuon for this anaylsis is the CMO's concern regarding the long-term fincial health and scaliability of the RetailCo. The company need clarirty on marketing and investment efficiency to ensure that current growth is sustainable and profitable.

1. Financial Viabiloity and LTV:CAC
The company central concern is return on investment (ROI) from marketng spend. The CMO needs assurance that RetailCo is operating at or above industry benchmark for Customer Lifetime Value (LTV) to Customer Acquisition Cost (CAC) ratio (Ideally 3:1 for e-commerce)

2. Performance Visibilityy and Budget Allocation
Stakeholders need transparacy regarding the performance of each acquisition channel. The analysis must provide proof points for channels where the LTV:CAC ratio is approaching 1:1 or less, as this signals a threat to profitability. The goal is to identify sources that are currently inefficient, requiring spending cuts or optimization.

- optimaztion: Which sources deliver highest LTV customers, justufying increased budget allocation? 
- De-risking: Which sources deliver customers that result in the lowest LTV:CAC ratio, requiring spending cuts?

3. Actionable and ROI Recommendations?

The final deliverable can not be a summary of data, it must be a prioritized list of actionable sytragies. The CMO needs concrete recommendations backed by data. The recommendations should focuse on twoi main levers for profitability: reducing CAC and increasing LTV, showing the stimated cost savings or revenue gain for each proposal. 



## Success Metrics

The success for this analysis will be measured by the ability to provide data-backed insights that drive the LTV:CAC ratio toward the ideal benchmark of 3:1. The follwoung Key Performance Indicators below (KPIs) will be calculated and segmented by customer group and inferred channel. 

1. Core profitability Metrics:
- Customer Lifetime Value (LTV): The estimated total revenue a customer generates over time.

- LTV:CAC Ratio: The ideal healthy metric, Calculated by dividjng LTV by an assumed/benchmarked CAC. The analysis must show how to improve this ratio.

- Customer Payback Period: the time (in months) it takes for a customer's revenue contrinution to equal the CAC. The shorter the period the more improvment of cash flow. 

2. Value and Retention Metrics:

- Average Order Value (AOV): The average amount spend per order. Imprivng the AVO helps increase LTV without incuring new aquisition costs. 

- Repeat Purchase Rate (RPR)/ Customer retention rate (CRR): The percentage of customer who retunr to make a second purchase. A high RPR is the foundation of high LTV. 

- Purchase Frequency: the average number of purchases a custommer makes over a defined period. 


3. Transaction Efficiency Metrics:

- Cart Abandoment Rate: The percentage of initiated orders that were never completed. This pnpoints friction oin the checkout process, which is critical in Brazilian market. 

- Fulfillment Speed (Time-to-Delivery): The time taken from purchase to final delivery. 


## Constraints

Any data analysis is limited by the quality and availability of data. Given the use of public Brazillianm E-commerce dataset by Olist, the following constraints limit the scope and precision of final analysis and must be communicated to stakeholders:

1. Absence of True Aquisition Cost Data:

- The database is a transaction record and does not contain acual marketing costs, ad spending, or campaign budget data. A true, direct calculation of Customer Aquisition Cost (CAC) is impossible. Instead, this analysis must rely on industry benchmarks or assumee cost proxies based on identified aquisition channel. This limits the precision of the LTV:CAC ratio.

2. Inferred Acquisition Channels:

- The Olist dataset uses broad categories for the customer;s source such as "search", "social media". It is impossible to distinguish performance between highly specfic sources. The recommendations regaerding channel efficiency will be liited to a broad channel types.

3. Time Scope Limitation:
 
- The data is between a fixed period (late 2016 to mid 2018). Customer lifetime value (LTV) must be calculated using a projected model, as customer relationship length is capped by the dataset's end date. 

4. Limited Product Context:
The product data is high level such as "health_beauty", "bed_bath_table" and lacks specific details suc as brand, margin, or seasonality. The product specific profitability anaylsis which is importnat for LTV will be limited to category averages. 

