# Viewer Retention in OTT Platforms  
### Diagnosing Episode-Level Engagement & Drop-off Patterns

This project analyzes episode-level viewer engagement data from an OTT streaming platform to understand **why viewers drop off during early episodes of a series** and what content or product-level actions can improve retention.

The analysis was conducted as part of the **Winter Consulting Capstone Project 2025** organized by the Consulting & Analytics Club, IIT Guwahati.

---

## Problem Statement

OTT platforms often observe strong viewership at launch but significant drop-off during Season 1.  
This project aims to answer:

- Where does viewer drop-off occur most frequently?
- Which episode-level factors contribute most to drop-off risk?
- What data-backed actions can reduce drop-off without compromising creative quality?

---

## Dataset Overview

The dataset contains **episode-level data** including:

- Episode attributes (duration, pacing, dialog density, cognitive load, genre)
- Viewer behavior metrics (completion %, engagement patterns)
- Target variables related to drop-off and retention

Primary target variable:
- `drop_off_probability`

---

## Approach

The analysis follows a structured data analytics workflow:

1. **Data Understanding & Cleaning**
   - Column categorization and relevance assessment
   - Identification of target and redundant variables

2. **Exploratory Data Analysis**
   - Drop-off trends across episodes
   - Impact of episode duration and pacing
   - Genre-wise engagement patterns

3. **Segmentation Analysis**
   - Duration × dialog density
   - Pacing × cognitive load
   - Comparison of drop-off probabilities across segments

4. **Insight Generation**
   - Identification of high-risk episode patterns
   - Detection of content “sweet spots” for retention

5. **Recommendations & Prioritization**
   - Data-driven, feasible product and content actions
   - Impact vs effort prioritization
   - Risk identification and mitigation

---

## Key Insights

- Viewer drop-off increases significantly after early episodes, especially for **long, high cognitive load content**.
- **Faster-paced episodes** show higher continuation rates across genres.
- Episodes with **moderate duration (≈100–110 mins)** and **lower dialog density** exhibit lower drop-off probabilities.

---

## Recommended Actions

- Promote low cognitive load and fast-paced content in platform recommendations.
- Introduce fast-forward options (2x/3x) to support varying viewer pacing preferences.
- Optimize future episode durations toward identified retention sweet spots.

---

## Success Metric

Primary metric to evaluate impact:
- **Episode 3 continuation rate**

Supporting metric:
- Average completion percentage of early episodes

---

## Tools Used

- **PostgreSQL (pgAdmin 4)** – Data querying and aggregation  
- **Microsoft Excel** – Data cleaning and preprocessing  
- **Tableau** – Visualization and dashboarding  

---

## Author

**Aditya Chakraborty**  
B.Tech, Ocean Engineering and Naval Architecture 
IIT Kharagpur (2024–2028)

---

## Notes

- This project intentionally avoids Python and ML models to focus on **core data analytics skills** using industry-standard BI tools.
- All recommendations are grounded in observed data patterns and practical implementation constraints.
