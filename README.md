# CryptoClustrering

Before You Begin: 

Create a new repository for this project called CryptoClustering. Do not add this homework to an existing repository.

Clone the new repository to your computer.

Push your changes to GitHub.



Cluster Analysis with k-Means:

Create an elbow plot to identify the best number of clusters. Use a for-loop to determine the inertia for each k between 1 through 11. Determine, if possible, where the elbow of the plot is, and at which value of k it appears.

#Coding the elbow method algorithm to find the best value for k. Use a range from 1 to 11.

To visually identify the optimal value for k, plot a line chart of all the inertia values computed with the different values of k

#Using hvPlot, create a scatter plot by setting x="PC1" and y="PC2". Colour the graph points with the labels that you found by using K-means. Then add the crypto name to the hover_cols parameter to identify the cryptocurrency that each data point represents.

 #Composite plot by using hvPlot and the plus sign (+) operator to compare the elbow curve that you created from the original data with the one that you created from the PCA data.
 
 
 
 #References:

  1.If you need a refresher on how to create these plots, review that module. You can also check Composing PlotsLinks to an external site. in the hvPlot documentation.
 
 2.Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.
