# FUTURE_DS_03 - Marketing Funnel & Conversion Performance Analysis

## Overview

This project was completed as part of the **Future Interns Data Science & Analytics Internship (Task 3)**.

The objective was to analyze a marketing funnel dataset to identify conversion performance, marketing channel effectiveness, lead generation trends, and business opportunities to improve customer conversion.

## Dataset

The project uses the Olist Marketing Funnel dataset consisting of:

* `olist_marketing_qualified_leads_dataset.csv`
* `olist_closed_deals_dataset.csv`

These datasets contain information about marketing qualified leads (MQLs), marketing channels, business segments, landing pages, first contact dates, and successfully closed deals.

## Tools Used

* Microsoft Power BI Desktop
* Power Query
* DAX Measures

## Dashboard Features

The dashboard includes:

* Total Marketing Qualified Leads
* Total Closed Deals
* Overall Conversion Rate
* Lead Distribution by Marketing Channel
* Lead Distribution by Landing Page
* Business Segment Performance
* Lead Generation Trend Over Time
* Marketing Channel Distribution (Pie Chart)

## DAX Measures

### Total Leads

```DAX
Total Leads =
COUNTROWS(olist_marketing_qualified_leads_dataset)
```

### Total Customers

```DAX
Total Customers =
COUNTROWS(olist_closed_deals_dataset)
```

### Conversion Rate

```DAX
Conversion Rate =
DIVIDE([Total Customers],[Total Leads],0)
```

## Key Findings

* Total Marketing Qualified Leads: Approximately 8,000
* Total Closed Deals: 842
* Overall Conversion Rate: 10.53%
* Organic Search generated the highest number of qualified leads.
* Paid Search was the second-best performing acquisition channel.
* Home Decor and Health & Beauty were the strongest business segments.
* Lead generation increased significantly during 2018.

## Business Recommendations

* Continue investing in Organic Search campaigns.
* Improve conversion strategies for Paid Search traffic.
* Optimize underperforming marketing channels.
* Prioritize high-performing business segments.
* Improve lead nurturing to increase the lead-to-customer conversion rate.

## Repository Structure

```
FUTURE_DS_03/
│
├── Dashboard.pbix
├── README.md
├── Report.pdf
├── screenshots/
└── dataset/
```

## Author

Naledi Papo

Future Interns Data Science & Analytics Internship
