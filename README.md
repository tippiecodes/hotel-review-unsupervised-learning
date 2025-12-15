# Hotel Review Unsupervised Learning Analysis

This project applies unsupervised learning techniques to a large-scale hotel review dataset to uncover customer preferences and identify customer profiles associated with higher satisfaction ratings.

The analysis focuses on two main techniques:
- Association Rule Mining to discover relationships between review keywords
- K-means Clustering to segment customers based on travel characteristics and ratings

---

## Dataset Overview
- Over 52,000 hotel reviews
- 63 variables including customer attributes, star ratings, and keyword indicators extracted from text reviews
- Keyword features represent the presence of specific terms (e.g. cleanliness, comfort, staff service)

---

## Methods Used

### Association Rule Mining
- Transformed keyword indicators into transactional data
- Generated association rules using support and confidence thresholds
- Filtered for rules with a minimum of three itemsets
- Analysed top rules to understand what guests value most in hotel stays

Key insights highlighted the importance of room cleanliness, comfort, size, and staff friendliness in shaping guest satisfaction.

### K-means Clustering
- Performed customer segmentation using travel type, region, travel cluster, and star ratings
- Evaluated different cluster sizes and tuning parameters
- Identified customer groups with the highest average ratings

Couples emerged as the segment with the highest overall satisfaction, while business travellers showed comparatively lower ratings, indicating areas for service improvement.

---

## Key Outcomes
- Clear identification of hotel attributes most strongly linked to positive reviews
- Actionable customer segments based on travel behaviour and satisfaction levels
- Practical recommendations for hotel operators to improve guest experience and target high-value customer groups

---

## Tools & Technologies
- KNIME (data preparation and association rule mining)
- SAS Viya (k-means clustering and visual evaluation)
- Excel (data inspection)

---

## Files
- `Assignment_Report.pdf`: Full analysis and findings
- `hotelDataset.xlsx`: Original dataset used for modelling
