# Unsupervised Algorithms
## k-Means
### k-means cost function:

![image](https://github.com/user-attachments/assets/c95d2cf0-3f5f-4daf-aba8-e53957796b5d)

### Selecting the optimum number of cluster

The WCSS value decreases when we increase the number of clusters.

If there is only one cluster, the WCSS is large. On the other hand, when we incease the number of centroids to be equal to the number of data points, then the WCSS value is zero as each data point is the centroid of itself and its distance to centroid is zero.


![image](https://github.com/user-attachments/assets/c7460b68-bb23-49e7-b8d2-3c4eeb2b08ad)

Elbow methos is a way to find the optimum number of clusters:

The following curve shows that at some point after cluster number 3, the WCSS value is not decreasing anymore. We do not want to add more cluster when there is no considerable change in WCSS values. 

![image](https://github.com/user-attachments/assets/920050da-7c39-41b0-bc3e-fcf22de1c2c3)

### Evaluating K-Means performance

We calculate it by CH-index. It is the ratio of scatter matrix between the clusters (Sb) and with the cluster (Sw). 

![image](https://github.com/user-attachments/assets/a3398f71-ed9f-4954-8702-07a2a721c2c3)


The higher the CH, the better the proformance. 

![image](https://github.com/user-attachments/assets/0fc2f24e-322f-4250-8cd8-b380af372d93)



