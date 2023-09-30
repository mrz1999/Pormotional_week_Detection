# FATER-AWARD


This is the first step (out of 2) of the FATER AWARD challenge organized by FATER. 
We were asked to detect the promotional weeks applied by their customers (supermarkets) on their products for sale.  
We applied the anomaly detection and the SVM to accomplish this task.

We had a data-set with 31239 rows and 11 features (name of the customer, date (week), units sold in that week, price per units, volume (number of units 
for each standard unit (it can change among the products), price volume, etc.).

We did a nice preprocessing and then we applied a PCA for building an anomaly detector (GESD and IQR methods) just on the first component of the PCA. 
Then we used a cluster analysis as other anomaly detection techniques and eventually we built an SVM (semi supervised).

For further information see the code (it explaines everything). The code is written on R. 
