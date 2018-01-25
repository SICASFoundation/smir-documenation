---
title: BRATS 2015
taxonomy:
    category: docs
---



## Ranking Table

- Cases: Total number of datasets to be segmented
- Segmentations: User submitted segmentations (can differ from cases)
- Label: Regions in the segmentation. 

### Calculations

1. **Metrics**: We calculate metrics results for each label of submitted segmentations. These are displayed on the evaluation page of each user.
2. **Metric Average**: Average of the metric.
3. **Metric Rank**: We assign a rank for this average  (comparing to other users)
4. **Label Rank**:  Average of the metric ranks.
5. **Final Rank**: Average of the label ranks.
6. The Table is sorted descending by user Rank


#### Example table for a single label

| User  | Metric 1                      | Metric 2                      | Overall             |
| ----- | ---------------------------- | ---------------------------- | ------------------- |
| User1 | 1.1 (1)                      | 0.9 (2)                      | 1 (1.5)             |
| User2 | 3.1 (3)                      | 0.92 (1)                     | 2 (2)               |
| User3 | 1.4 (2)                      | 0.85 (3)                     | 3 (2.5)             |
| user  | Metric Average (Metric Rank) | Metric Average (Metric Rank) | Final Rank (Rank Average) |

### Testing Metrics

1. Dice, 
2. Positive Predictive Value (Specificity), 
3. Sensitivity, 
4. Kappa

### Training Metrics

1. Dice, 
2. Positive Predictive Value (Specificity), 
3. Sensitivity, 
4. Kappa