📊Visualization Project: Dashboard Development📈

Google Looker Studio Dashboard: https://lookerstudio.google.com/s/ske7dRqPsI4

We have created a dashboard for Amazon’s Chargebacks department, aimed at reducing their chargebacks for authenticated transactions by 5%. The data used for this project has been randomly generated with Python.

## **KPIs:**

1.	**Total Chargebacks:** The total sum of received chargebacks. This helps us get an overall view of the situation.
2.	**Ratio of Authenticated Transactions:** The percentage of transactions that have been authenticated out of the total. This percentage is directly related to the department’s goal.
3. **Total Chargeback Amount:** Indicates the total value sum of chargebacks for authenticated transactions. This provides insight into the overall value of the chargebacks.
4.	**Average Chargeback Amount:** The average value of chargebacks for authenticated transactions. Similar to the previous KPI, but from the perspective of individual transactions.
5.	**% Caused by Missing Products:** The percentage of total chargebacks generated for this reason. We consider this KPI very relevant, as Amazon can exert greater control over chargebacks caused by missing products.

## **Visualizations:**

Three pie charts, one stacked bar chart, and two time series charts have been created. One of them is a combined chart that contains information about the total chargebacks and the average monthly value of transactions and chargebacks for each month.

## **Segmentation:**

The chosen filters allow data visualization by country, payment type, customer type, and chargeback status. As we only have data for one year, we have not included a date segmentation. However, it would be interesting to add this filter with more years.

Here's a preview of the dashboard. If you want to interact with it, remember you've access through the link at the top

![Dashboard](Chargeback_Dashboard_with_LookerStudio/Captura_Dashboard.jpg)

