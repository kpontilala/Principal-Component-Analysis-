# Principal-Component-Analysis-
Utilization of PCA component on the breast cancer dataset in sklearn datasets.

### Project Overview
As a Data analyst at the Anderson Cancer Center, you are tasked with developing a model to address the growing number of referrals at the center. This model's first step is to identify essential variables for securing donor funding. After consulting with your team, Principal Component Analysis (PCA) has been chosen as the most suitable technique for this task. 

### Project Description
You will perform the following tasks:
<li>PCA Implementation:</li> Utilize PCA to demonstrate how essential variables can be acquired from the cancer dataset available from sklearn.datasets.
<li>Dimensionality Reduction:</li> Reduce the dataset into 2 PCA components for the project.
<li>Implement logistic regression for prediction.</li>

### PROJECT STEPS
<li>Importing necessary libraries and modules</li>
<li>Load the breast cancer dataset from sklearn</li>
<li>normalize the dataset to bring all the figures to within same range</li>
<li>implement pca on the normalized dataset</li>
<li>first we do the pca with the whole components and calculate the explained variance and cummulative explained variance</li>
<li>This shows the normal of variance captured by each components and the visualized cumulative variance, shows how importance of adding more components</li>
<li>The PCA component is reduced to 2, as instructed in this project</li>
<li>The explained variance of the 2 principal components are visualized to show the distinct seperation of the dataset target class, this shows that both principal components was successful in seperating the classes</li>
<li>Logistic regressrion model was trained nad tested using the 2 principal components of the dataset and the models accuracy was 99%</li>
