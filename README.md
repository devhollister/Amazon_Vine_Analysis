# Amazon Vine Analysis

## Overview

The Amazon Vine program is a "service that allows manufacturers and publishers receive reviews for their products" whereby companies "pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review." The following analysis examines the star ratings given by Vine and non-Vine members as part of reviews for musical instruments to determine whether there is bias towards positive reviews among Vine members. 

## Results

The original dataset contained a total of 904,765 reviews of musical instruments. The first ten entries in this dataset are shown below: 

![](images/overview_table.png)

This dataset was refined by excluding reviews with less than 20 total votes and those with less than 50% helpful votes (hopeful votes/total votes). From here the reviews were broken down into Vine members and non-Vine members. There were a total of 60 reviews by Vine members at this point in the analysis, with 34 of those giving 5-stars (56.67%). The first ten reviews by Vine members are shown below: 

![](images/paid_table.png)

There were 14,477 reviews by non-Vine members, and 8,212 of those reviews were 5-star reviews (56.72%). The first ten reviews by non-Vine memners are shown below:

![](images/unpaid_table.png)

## Summary
