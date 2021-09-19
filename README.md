## Crowd Sensed Data Falsification Attack Using Outlier Detect by DBSCAN

Crowd Sensed also called mobile crowd sensing means our smartphone has lots of sensors say GPS which generates the locations say for weather report generator for that location where it responsible for collecting data for various purposes. 
So, some data may get changed due to noise. So, we predict those 
noisy data by doing lots of hyper-parameter tuning and data 
visualization for better selection of the parameter for DBSCAN 
algorithm.  

## How It Works
1. we had taken a correct crowd sensed dataset for temperature and falsified the dataset in terms of percentage(say 2%,4%, and so on 
of the total records).

2. For each percentage of falsified datasets we run our DBSCAN(Desity
Based Spatial Clustering of Applications with Noise) manually in increasing order
for each percentage of falsified dataset and run for three iterations.

3. We manually calculate the Average Accuracy, Average Recal, Average Precision,Average FPR, Average TPR for every iterations in each percentages of data falsified.

4. We finally plot the various graphs for visualizing the DBSCAN parameters w.r.t percentage of data falsification such as: 
   i) Average Accuracy vs percentage of data falsification(2%,4%,etc), 
   ii) Average Recall vs percentage of data falsification, 
   iii) Average Precision vs percentage of data falsification, 
   iv) finally ROC(Receiver Operating Characteristic Curve) which is Average FPR vs Average TPR for determining the best Parameter value for our model which has high    TPR and low FPR.

## My Role in Project
I had implemented the coding part and the report generation was done by my project partner.

## Chalenges  Faced
The major problem we faced was for manually calculating the FPR, TPR, Accuracy, Recall, Precision.

  
## Authors

- [@sukumarsarma](https://github.com/SukumarSarma)


## 🔗 Links

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/)


## 🛠 Skills
Python, Sklearn, Tensorflow, Data Visualization Tool, mySQL, Tableau, Excel, C/C++ 

  
## Hello i am Sukumar Sarm
I'm a Freshers and i love in the field of data science, Machine learning
and Data Analyst.
  