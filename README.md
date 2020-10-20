# Comparing Colleges Based on Various Metrics
## Background
Studies have shown that colleges play a major role in intergenerational income mobility rate. There are many other factors that contribute to the mobility rate (such as parental income and accessibility of the college), but I believe it is also important to focus on specific college variables that may impact mobility rate as well ([Fordham Institute](https://fordhaminstitute.org/national/commentary/how-college-affects-upward-mobility)).

I specifically looked into variables such as instructional expenditures per student, median earnings of students, percentage of certain majors, and mobility rate to see how colleges would be grouped together. This would be useful to see if these clusters and cluster anchors show that certain variables can be grouped together in a way that relates variables together. Then, we can extrapolate the results to see if making changes for specific variables can help improve the mobility rate of colleges.

## Business Question
How are different colleges grouped based on instructional expenditures per student, median earnings of students 10 years after entry, percentage stem majors, and percentage social science majors? How can we use this data to help colleges improve their mobility rate?

## Open Data
[Opportunity Insights Data Library](https://opportunityinsights.org/data/?geographic_level=0&topic=105&paper_id=0#resource-listing):

- [Preferred Estimates of Access and Mobility Rates by College](https://github.com/angelali1479/college-data-cluster-analysis/blob/main/mrc_table1.csv)

- [College Level Characteristics from the IPED Database and the College Scorecard](https://github.com/angelali1479/college-data-cluster-analysis/blob/main/mrc_table10.csv)

## Data Analysis

![alt text](https://github.com/angelali1479/college-data-cluster-analysis/blob/main/Screen%20Shot%202020-10-19%20at%208.12.04%20PM.png)

**Cluster 1:**
Compared to the other clusters, cluster 1 has the largest amount of standard deviations above the average for percentage stem major. Both instructional expenditures per student and median earnings of students 10 years after entry were only slightly above average while the mobility rate was the closest to average out of all the clusters. Cluster 1's only variable with a below average standard deviation is percentage social science. 
It would seem that the high percentage of stem majors does not have much of a relation to mobility rate, since mobility rate for this cluster is almost average.

**Cluster 2:**
Out of all the clusters, cluster 2 is the only one where all of its variables are below average, with percentage social science majors being the lowest below average at almost 1 entire standard deviation below average.

**Cluster 3:**
Cluster 3 has the highest mobility rate out of all the clusters, with its median earnings being the second highest out of all the clusters. This cluster's instructional expenditures per student is almost average, with only about 0.04 standard deviations above the average, while its percentage stem major and percentage social science major are both below average.

**Cluster 4:**
Cluster 4 has the highest instructional expenditure per student by far compared to the other clusters, with more than 6 standard deviations above the average. This cluster also has the highest median salary 10 years after entry out of all the other clusters and the remaining variables are also all above average. However, its mobility rate is lower than that of cluster 3.

**Cluster 5:**



![alt text](https://github.com/angelali1479/college-data-cluster-analysis/blob/main/miniproj3graph.png)


## Conclusions
