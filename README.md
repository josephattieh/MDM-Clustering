- Joseph Attieh
- Ayoub Chouak

# MDM-Clustering
_Submitted for the Methods of Data Mining course_

## Overview
The task is to cluster two data sets as well as possible, comparing at least two different clustering methods on both data sets, evaluate the goodness of clusterings with normalized mutual information, and submit optimal clusterings, program code and the project report.

## Datasets
The first data set is reminiscent to typical gene expression data (“Gene data”)
and the second one to mass spectrometry data (“MS data”), but they have
been artificially generated.
The data format is the following: The first line is a header listing column
labels and then begins the data matrix, where samples are on rows and
features on columns. The first two columns are special: the first is sample
identifier and the second class label. The rest are features that should be
used in clustering.
In the Gene data, there are five classes and in the MS data, three classes.
The classes are used only in the evaluation of the clustering with normalized mutual information. Note that the optimal number of clusters is not
necessarily the same as the number of classes
