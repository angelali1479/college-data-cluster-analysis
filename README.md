# Comparing Colleges Based on Various Metrics
## Background
Studies have shown that colleges play a major role in intergenerational income mobility rate. There are many other factors that contribute to the mobility rate (such as parental income and accessibility of the college), but I believe it is also important to focus on specific college variables that may impact mobility rate as well ([Fordham Institute](https://fordhaminstitute.org/national/commentary/how-college-affects-upward-mobility)).

I specifically looked into variables such as instructional expenditures per student, median earnings of students, percentage of certain majors, and mobility rate to see how colleges would be grouped together. This would be useful to see if these clusters and cluster anchors show that certain variables can be grouped together in a way that relates variables together. Then, we can extrapolate the results to see if making changes for specific variables can help improve the mobility rate of colleges.

## Business Question
**How are different colleges grouped based on instructional expenditures per student, median earnings of students 10 years after entry, percentage stem majors, and percentage social science majors? How can we use this data to help colleges improve their mobility rate?**

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
Cluster 3 has the highest mobility rate out of all the clusters, with its median earnings of students 10 years after entry being the second highest out of all the clusters. This cluster's instructional expenditures per student is almost average, with only about 0.04 standard deviations above the average, while its percentage stem major and percentage social science major are both below average.

**Cluster 4:**
Cluster 4 has the highest instructional expenditure per student by far compared to the other clusters, with more than 6 standard deviations above the average. This cluster also has the highest median earnings 10 years after entry out of all the other clusters and the remaining variables are also all above average. However, its mobility rate is lower than that of cluster 3.

**Cluster 5:**
Cluster 5's instructional expenditures per student, percentage stem majors, and mobility rate are all slightly below average. Percentage social science majors and median earnings of students 10 year after entry are above average for this cluster.

**Overall Observations:**
Out of all the clusters, cluster 4 is the only that is above average for all the variables. The only 2 variables that seem to follow a trend is mobility rate and instructional expenditures per student; if the instructional expenditures per student were above average for that cluster, its mobility rate were also above average (and vice versa).


![alt text](https://github.com/angelali1479/college-data-cluster-analysis/blob/main/miniproj3graph.png)

On this visual, I consolidated all 5 clusters' cluster variables together onto one graph so that it would be easier to compare the cluster variables visually. The 5 clusters are listed in order in the legend on the graph as the college name. The 5 cluster variables are listed on the x-axis with the following legend:
- 1 = instructional expenditures per student
- 2 = median earnings of students 10 years after entry
- 3 = percentage stem majors
- 4 = percentage social science majors
- 5 = mobility rate
We can see in the visual above that there appear to be two obvious outliers, instructional expenditures per student for Columbia University and percentage stem majors for New England Institute of Technology.

## Conclusions
