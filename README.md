# Wales_Clustering

Assessment Requirements / Tasks (include all guidance notes)
This assignment will use employment data of Wales from the StatsWales data source.  This dataset provides workplace employment estimates, or estimates of total jobs, for Wales and its NUTS2 areas, along with comparable UK data disaggregated by industry section.
For this assignment students will undertake a data analysis and machine learning approach to reveal the workplace employment landscape of Wales.  
1.	Data processing
1.1.	Download the dataset for the period 2009 – 2018 and create a dataframe that concatenates Wales (total)employment value only.

1.2.	Check for any null value or outlier. If found replace that with mean value.
1.3.	Change the name of the industries as bellow
The final dataframe should look like following.
Industry	2018	2017	2016	2015	2014	2013	2012	2011	2010	2009
Agriculture										
Production										
Construction										
Retail										
ICT										
Finance										
Real_Estate										
Professional_Service										
Public_Adminstration										
Other_Service										

2.	Data analysis
For each question provide graph/chart along with your own interpretation (~ 50 words)
2.1.	Which industry employed highest and lowest workers over the period?
2.2.	Which industry has the highest and lowest overall growth over the period?
	
2.3.	Which years are the best and worst performing year in relation to number of employment. (highest and lowest employment)

3.	Visual analysis
Create a dynamic scatter/bubble plot showing the change of workforce number over the period using Plotly express. 

4.	Correlation 
4.1.	Taking average employment number for each industry over the period, show and identify the highest and lowest correlated industries.
4.2.	Make a year wise correlation for each industry.  Does the aforementioned industries are also correlated over the each year? Explain your answer

5.	Clustering (k means&hierarchical)
5.1.	Using the best and worst performing year column’s employment data (2.3) undertake a K means clustering analysis (K=2 & 3) and identify industries cluster together.  Write your own interpretation(~100 words).

5.2.	Using the same dataset (best & worst performing) create a hierarchical cluster.  Compare the cluster with k means clusters. 

6.	Discussion
Provide a brief discussion (~ 300 words) on employment landscape of Wales based on the employment data analysis results. 
