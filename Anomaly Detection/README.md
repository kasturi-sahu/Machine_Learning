# Anomaly Detection
Anomaly detection is a technique used to identify unusualpatternsthat do not conform to expected  behaviour,  called outliers. This overview will cover several methods of detecting anomalies, as well as how to build a detector in Python using a Simple Moving Average (SMA)or low-pass filter.

# What are Anomalies
Anomalies can be broadly categorized as:

![Type](https://github.com/kasturi-sahu/Anomaly_Detection/blob/main/type.png "Type")

**Point anomalies**
A singleinstanceof data is anomalous if it'stoo far off from the rest. 

Business use case: Detecting credit card fraud based on "amount spent."

![Point](https://github.com/kasturi-sahu/Anomaly_Detection/blob/main/Point%20anomaly.PNG "Point")

**Contextual  anomalies**
The  abnormality  is contextspecific.  This  type  of  anomaly  is common in time-series data. 

Business use case: Spending $100 on food every day during the holiday season is normal, but maybeodd otherwise.

![contextual](https://github.com/kasturi-sahu/Anomaly_Detection/blob/main/Contextual.PNG "contextual")

**Collective  anomalies**
A  set  of  data  instances collectively helps  in  detecting  anomalies. 

Business use case: Someone is trying to copy data froma remotemachine to a local host unexpectedly, an anomaly that would be flagged as a potential cyber-attack. 

![Collective](https://github.com/kasturi-sahu/Anomaly_Detection/blob/main/collective.PNG "Collective")

# Anomalies Detection Techniques 

![technique](https://github.com/kasturi-sahu/Anomaly_Detection/blob/main/technique.PNG "technique")

**1. Simple Statistical Methods**
The simplest approach to identifying datairregularitiesis to flagthe data points that deviatefrom  common  statistical  properties  of  distribution,  including  mean,  median,  mode,  and quantiles
**2. Machine Learning-based Techniques**
- Density-Based Anomaly Detection

KNN  is  a  simple,  non-parametric lazylearning  technique  used  to classify data based on similarities by usingdistance metrics such as Euclidean, Manhattan, Minkowski, or Hamming distance.
- Clustering-Based Anomaly Detection

K-means is  a  widely  used  clustering algorithm. It creates 'k' similar clusters of data points. Data instances that fall outside of these groups could potentially be marked as anomalies.
- Support Vector Machine-Based Anomaly Detection

An SVM is typically associated with supervised learning, but there are extensions (One-Class SVM, for instance)  that  can  be  used  to  identify  anomalies  as  an  unsupervised  problem  (in  which training data are not labelled).

# Notes

![](https://github.com/kasturi-sahu/Anomaly_Detection/blob/main/1.jpeg)

![](https://github.com/kasturi-sahu/Anomaly_Detection/blob/main/2.jpeg)

![](https://github.com/kasturi-sahu/Anomaly_Detection/blob/main/3.jpeg)

![](https://github.com/kasturi-sahu/Anomaly_Detection/blob/main/4.jpeg)
