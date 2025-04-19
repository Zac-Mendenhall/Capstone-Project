# Capstone-Project
Individual work for Capstone project

# Swire Coca-Cola Case Competition – Customer Segmentation (Individual Work)

## Business Problem
Regional beverage bottler Swire Coca-Cola (SCCU) relies on two business models: 1)
“Red Truck”, which features high-volume customers serviced personally by Swire,
and 2) “White Truck” or “Alternate Route to Market”, which entails smaller customers
serviced by a third-party distributor.
Swire’s current segmenting strategy has led to misallocation of resources, inflated
expenses, and missed opportunities from clients with high-growth potential. Swire
aims to better algin their customers with the business proposition of these models by
identifying customer characteristics and ordering behavior that better determines
the right business model for the long-term relationship.

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

## Individual Key Findings
- **Cluster 3** contained the majority of customers, interpreted as typical small/medium buyers—ideal targets for growth support.
- **Cluster 1** showed abnormal behavior (e.g., fulfillment rates over 40x), likely data anomalies.
- Segmentation highlighted clear distinctions between elite, corporate, and everyday buyers.
- Gallons and cases fulfillment data revealed discrepancies in how certain customer types are served.

---

## Group Solution Summary
Our team proposed replacing Swire’s one-size-fits-all 400-gallon annual volume threshold with a behavior-based segmentation strategy. Rather than evaluating customers solely on annual volume, we incorporated metrics such as average order size, order frequency, and fulfillment behavior.
By blending customer transaction data with market context, we were able to segment customers into actionable groups. This approach better identifies high-potential customers—especially those with strong fulfillment behavior but low total volume—and enables the sales team to allocate resources more effectively.
This strategy increases efficiency and scalability while uncovering previously overlooked growth opportunities.

---

## Difficulties
The main challenge we faced was a lack of long-term historical data. With only two years of transactions available, identifying consistent behavioral trends was more difficult. To address this, we developed models that could scale with additional internal data, allowing Swire to continuously improve segmentation over time.

---

## What I Learned
The biggest takeaway for me in this project was learning how to collaborate on a large, code-based problem as part of a group. In my current work, I typically work independently and rely on my own judgment to solve problems. Collaborating with my team to develop solutions was great practice for future projects and a valuable reminder to always listen to others, you never know what insights you might gain from their perspective.

---

## Files in This Repo
- `Modeling_Individual_Final.Rmd`: My original R Markdown notebook with all code and analysis.
- `Modeling_Individual_Final.html`: Rendered, formatted report for easy viewing.

---

## Note
No data is included in this repo, in compliance with an NDA that was signed in order to work on this project.
