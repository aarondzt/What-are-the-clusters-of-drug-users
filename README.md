## Clustering on demography, personality, and drug use: What patterns are associated with hard drug use (e.g. heroin, crack, etc.)?

## Contents
* [Data source](https://archive.ics.uci.edu/ml/datasets/Drug+consumption+%28quantified%29)
* [Data files](Data)
* [Code/report](Drugs.ipynb)

### Abstract
Understanding the personality traits that are predictive of illegal drug usage is important for public health and guidence of policy-making. In Fehrman et al., the authors collect survey data on demographic factors, personality traits, and drug usage, and then run several machine learning models to analyze the traits that are predictive of the usage of individual and clusters of drugs. In a previous project, I attempted to classify users vs. non-users of illegal drugs based on demography and personality. Here, I attempt to use PCA and clustering to examine the inherent structure of the data, with an emphasis on finding patterns associated with hard drug use (e.g. use of drugs such as heroin and crack that are known to be associated with negative life outcomes). I used PCA to reduce the dimensionality of the personality and drug use features. The first PC of personality was associated with conscientiousness, and the second with introversion. The first PC of drug use differentiated users from non-users, and the second differentiated users of hard drugs with users of psychdelic drugs (e.g. ecstasy, mushrooms, LSD). Then, I used K-means clustering to identify meaningful and informative clusters. Using the elbow method with distortion as a metric to guide my clustering decisions, I settled on k = 3, as this divided the observations into three groups: (a) non-users, (b) hard drug users, and (c) psychdelic drug users. I visualized these clusters against educational attainment and conscientiousness and found that hard drug users exhibit lower education and conscientiousness, psychedelic drug users exhibit average education and conscientiousness, and non-users exhibit higher education and conscientiousness. As far as public policy goes, this analysis suggests that increasing the quality of education and student retention might be an effective solution to deter the use of hard drugs (this would probably also raise conscientiousness). However, this would have to be proven with causal experiments.

## Project Info
<pre>
Contributors : <a href=https://github.com/aarondzt>Aaron Tan</a>
</pre>

<pre>
Languages    : Python
Tools/IDE    : Anaconda
Libraries    : numpy, pandas, matplotlib, seaborn, sklearn
</pre>

<pre>
Date published     : 11.25.2020
</pre>
