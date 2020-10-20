# Comparing Colleges Based on Various Metrics
## Background
Studies have shown that colleges play a major role in intergenerational income mobility rate. There are many other factors that contribute to the mobility rate (such as parental income and accessibility of the college), but I believe it is also important to focus on specific college variables that may impact mobility rate as well ([Fordham Institute](https://fordhaminstitute.org/national/commentary/how-college-affects-upward-mobility)).

I specifically looked into variables such as instructional expenditures per student, median earnings of students, percentage of certain majors, and mobility rate to see how colleges would be grouped together. This would be useful to see if these clusters and cluster anchors show that certain variables can be grouped together in a way that relates variables together. Then, we can extrapolate the results to see if making changes for specific variables can help improve the mobility rate of colleges.

## Business Question
**How are different colleges grouped based on instructional expenditures per student, median earnings of students 10 years after entry, percentage STEM majors, and percentage social science majors? How can we use this data to help colleges improve their mobility rate?**

## Open Data
[Opportunity Insights Data Library](https://opportunityinsights.org/data/?geographic_level=0&topic=105&paper_id=0#resource-listing):

- [Preferred Estimates of Access and Mobility Rates by College](https://github.com/angelali1479/college-data-cluster-analysis/blob/main/mrc_table1.csv)

- [College Level Characteristics from the IPED Database and the College Scorecard](https://github.com/angelali1479/college-data-cluster-analysis/blob/main/mrc_table10.csv)

## Data Analysis

![alt text](https://github.com/angelali1479/college-data-cluster-analysis/blob/main/Screen%20Shot%202020-10-19%20at%208.12.04%20PM.png)

**Cluster 1:**
Compared to the other clusters, cluster 1 has the largest amount of standard deviations above the average for percentage STEM major. Both instructional expenditures per student and median earnings of students 10 years after entry were only slightly above average while the mobility rate was the closest to average out of all the clusters. Cluster 1's only variable with a below average standard deviation is percentage social science. 
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
- 3 = percentage STEM majors
- 4 = percentage social science majors
- 5 = mobility rate


We can see in the visual above that there appear to be two obvious outliers, instructional expenditures per student for Columbia University and percentage stem majors for New England Institute of Technology. None of the colleges had a cluster variable far below average and were all less than one standard deviation below average. I had initially hypothesized based on the research article described in the background section that instructional expenditures per student and brand name of the school would have the closest relation to mobility rate, but we can see from this graph that that is not necessarily true. Although Columbia has the highest instructional expenditurees per student by far, we can see that D'Youville College had a higher mobility rate despite having close to average instructional expenditures per student. The othere outlier, percentage STEM majors for New England Institute of Technology, is likely caused by the fact that the college specializes in STEM.

## Conclusions

This analysis can help further explore which ways policy can be implemented in order to help intergenerational income mobility. Throughout the years, many have suggested universal free college tuition, but the reality is that such a policy is seen as too radical by many people, particularly those that actually make the decisions to have such a thing. It is better to start with smaller, more easily implemented strategies that are college or region specific. 

As stated in a research article about colleges' roles in mobility, it would seem that the largest impact on mobility is accessibility and reputation. While brand name colleges like the Ivy League (like Columbia which is shown in the visual above) have a high mobility rate, the lack of accessibility causes many low income students to not have an opportunity to attend it; however, it is the selectivity of the school that allows it to have a high mobility rate. On the other hand, larger public schools have a higher accessibility rate but lower mobility rate. Overall, high accessibility generally correlates with low mobility and vice versa, so the goal is to find a happy medium somehow.

Originally, I believed that higher instructional expenditures per student would mean a higher mobility rate, but we can see in the data above that in fact the cluster with the highest mobility rate in the table actually had almost the average amount of instructional expenditurees per student. This result is in agreement with the calculations done in the study, which states that colleges that spent around $6,500 per student actually had the highest mobility rates while Ivy League colleges  spent around $87,000 per student ([Mobility Report Cards](http://www.equality-of-opportunity.org/papers/coll_mrc_paper.pdf)). This goes to show that there are ways to increase mobility rates without actually needing to put more money into instructional fees. It is important to look at what those mid-level public universities are doing and be able to replicate their methods.

One possible reason that could be holding low income students back is the lack of resources throughout the college application process, during college, and after graduation. Many low income students do not have access to college application resources that could make the process easier for them, and later in college, also have many barriers. For example, they may need to work a part time job or take care of family while going to school full time, which may affect their perfomance and connection to the school. Furthermore, after graduation, low income students are also more likely to have debt to pay off, either in the form of student loans or other sources, which further causes their financial situation and mobility rate to deteriorate ([College for America](https://collegeforamerica.org/college-completion-low-income-students/)).

I believe there are a few ways in which colleges can help improve their mobility rate. One is to provide better academic support within the college, whether that be in the form of promoting their existing services better or creating more options for students to choose from since tutoring slots tend to fill up fairly quick. This would allow low income students who may be falling behind in their classes due to extenuating circumstances to have more support to help them succeed in college. Another method could be teaching financial literacy more commonly in colleges; this would help both normal and low income students to better manage their money during school and after they graduate which could potentially mitigate the effect of student loans on low income students post-graduation. A last method could be more programs that allow low income students to network and create connections. Oftentimes, students who come from wealthier families already have connections through their parents or family in some way, while low income students often do not. By helping low income students build more connections, they are better prepared to find a stable job after graduation and would help them to move up income levels.
