# Amazon Vine Analysis

## Overview
The purpose of this analysis is to examine the counts and distributions of paid and unpaid Amazon reviews in the Automotive category in order to detect bias.

## Results

![Analysis Results](https://github.com/noble190/Amazon_Vine_Analysis/blob/main/img/ReviewAnalysis.png)

<b>Total Reviews:</b> There is a total of 82 paid reviews, and 24,742 unpaid reviews. There are significantly fewer paid reviews than unpaid reviews.

<b> Total 5-Star Reviews:</b> There is a total of 33 paid 5-star reivews, and 12,807 unpaid 5-star reviews. This distribution is consistent with the the distribution of total reviews.

<b> Percentage of 5-Star Reviews:</b> Out of all paid reviews, 40.24% were 5-star. Out of all unpaid reviews, 51.76% were 5-star. 


## Summary
At a glance, it would appear that unpaid reviews are more likely to be 5-star, suggesting a positivity bias in unpaid reviews. 
However, there is a significant discrepancy in sample sizes between review classes, with only 82 paid reviews. I would suggest that given the likely variance stemming from such a small sample size, the ~10% difference is largely immaterial. Given this dataset, it would be impossible to definitively prove positivity bias in either review class.

In the future, it may be worthwhile to re-examine the filter on the % of helpful reviews across paid and unpaid review classes. It's possible that there is no significant positivity bias in either class when filtering for largely helpful reviews (>= 50%), but this may not be the case if all reviews are considered. 
Additionally, we may examine the distribution of helpful reviews across our two review classes, which may reveal additional dimension of bias.
