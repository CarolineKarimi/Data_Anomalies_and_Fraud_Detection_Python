# Data_Anomalies_and_Fraud_Detection_Python

Detecting anomalies or fraudulent data is crucial in many fields.
However, it can be a challenging task, especially when dealing with newly collected data. 
In this scenario, traditional methods such as regression analysis or hypothesis testing may not be effective since they assume that data follow a certain distribution
or pattern.

However there are several methods that can be used detect anomalies or fraudulent data in newly collected data including:
* 3 Sigma rule - based on the assumption that data points within three standard deviations (σ) of the mean are considered normal, while data points outside this range are considered outliers. In other words, any data point that is more than three standard deviations from the mean is considered an anomaly.
* Heat Maps - graphical representations of data that use color-coding to indicate the strength of a relationship between two variables. They are often used to visualize correlations between variables in large datasets.
* Isolation Forest - works by randomly selecting a feature and then randomly selecting a split value between the maximum and minimum values of the selected feature. This process is repeated until all data points are isolated in their own tree branch. Anomalies are data points that require fewer splits to be isolated.

## Use case
The inlcuded dataseta has records entered by enumerators in a survey. The intention is to conduct the above checks to find out if any enumerator stands out with significantly higher fradulent records.The code can be edited to suit other specific needs
