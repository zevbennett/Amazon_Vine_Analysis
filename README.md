# Amazon_Vine_Analysis

### Purpose 
The goal of this analysis is to determine whether or not the amazon Vine program produces a higher percentage of 5-star reviews than the regular reviews in the category of musical instrument sales. 

### Methods
Use spark to extract and transform the data set from amazon's S3 buckets. Then load it into an RDS using postgreSQL. Finally, some of this transformed data was exported as a CSV file and analyzed locally using Pandas.

---

### Results

- There are **34 5-Star ratings** in the Paid Vine Reviews. 
    **42.37%** of the reivews are 5-Star

- There are **7678 5-Star ratings** in the **unpaid** Vine   Reviews. 
**43.04%** of the reivews are 5-Star

---
### Analysis 

The number of 5-star reviews produced by the vine program was negligible when compared to the total number of reviews. Moreover, the percentage of 5-star reviews produced was 1% lower than the total percentage of 5-star reviews. 

### Summary

The vine program has nearly the same number of 5-star reviews as the total population of reviews. Therfore, we can conclude that there is little to no bias in the Vine program. 

### Additional Analyis
It would be good to analyze the vine program across all categories of products to get a better picture of it relavtive bias. 