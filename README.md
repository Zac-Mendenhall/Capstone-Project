# Capstone-Project
Individual work for Capstone project

# Swire Coca-Cola Case Competition – Customer Segmentation (Individual Work)

## Project Overview
This portfolio presents my individual work on the Swire Coca-Cola case competition, where the goal was to improve customer targeting and strategies.

In my analysis, I focused on unsupervised learning using K-means clustering to uncover natural customer segments based on fulfillment and ordering patterns. The insights generated are intended to help the sales team prioritize outreach and allocate resources more effectively.

---

## Business Value
Understanding customer segments helps optimize marketing and sales strategies by:
- Identifying top-performing or underperforming accounts
- Pinpointing small/medium customers with growth potential
- Highlighting unusual fulfillment behaviors

---

## My Role and Contributions
- Cleaned and aggregated transactional data for each customer (cases and gallons).
- Calculated key performance metrics such as:
  - Fulfillment rate (delivered / ordered)
  - Returns (cases and gallons)
- Performed K-means clustering:
  - Initially with 4 clusters, then changed to 5 and then removing outliers.
- Visualized and interpreted cluster results to define customer types.
- Created separate datasets for gallons focused vs. cases focused segments.

---

## Key Findings
- **Cluster 3** contained the majority of customers, interpreted as typical small/medium buyers—ideal targets for growth support.
- **Cluster 1** showed abnormal behavior (e.g., fulfillment rates over 40x), likely data anomalies.
- Segmentation highlighted clear distinctions between elite, corporate, and everyday buyers.
- Gallons and cases fulfillment data revealed discrepancies in how certain customer types are served.

---

## Talking Points for Interviews
- How I used clustering to segment customers and drive strategic insights.
- Why fulfillment rate (not just volume) can be more informative in B2B contexts.
- The value of removing data anomalies when fitting unsupervised models.
- Creating simple but actionable deliverables from complex data.

---

## Files in This Repo
- `Modeling_Individual_Final.Rmd`: My original R Markdown notebook with all code and analysis.
- `Modeling_Individual_Final.html`: Rendered, formatted report for easy viewing.

---

## Note
No data is included in this repo, in compliance with an NDA that was signed in order to work on this project.
