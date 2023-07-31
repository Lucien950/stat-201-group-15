# STAT 201 Group 15 
<hr>  

**Group Members**: Rhiannon Charles, Fumiya Inaba, Edwin Zheng, Shaurya Veer Anand  

## On the Impact of EGFR Mutation and Age at Diagnosis on Glioma Grade  
This dataset is taken from the UCI Machine Learning Repository, linked [here](http://archive.ics.uci.edu/dataset/759/glioma+grading+clinical+and+mutation+features+dataset). It is also available from this [repository link](https://raw.githubusercontent.com/Lucien950/stat-201-group-15/main/TCGA_InfoWithGrade.csv) for direct import into an R environment. This is also the link used in the Jupyter notebook.

## The Project  
In Canada, cancer is currently the leading cause of death annually with 2 in 5 people expected to be diagnosed once in their lifetime (Canadian Cancer Statistics, 2021). With that, gliomas are the most common malignant tumors in adults (Carrano, 2021). However, there exists certain genetic mutations that can increase the risk of cancer and enhance the progression of cancer in individuals such as the epidermal growth factor receptor (EGFR) (Xu, 2017). While EGFR mutations are known to increase risk of cancer, it is more commonly associated with lung cancer, therefore, it can be useful for clinical treatments and therapies to investigate whether a mutation in the EGFR gene impacts the severity of glioma tumors (Liu, 2020). Additionally, to better improve testing and clinical treatment it could be useful to investigate whether the average age of diagnosis changes between those with the more severe glioblastoma and those with low grade glioma. Thus, our two research questions are as follows:

1. Do the proportion of patients with the EGFR mutation differ between those with glioblastoma (GBM) and low grade glioma (LGG)?
2. Is there a significant difference in the average age of diagnosis for individuals with glioblastoma (GBM) and low grade glioma (LGG)?

The dataset we will be using is the Glioma Grading Clinical and Mutation Features Dataset from the UCI Machine Learning Repository. The dataset contains 24 attributes however for our analysis we are only concerned with 3 of them.

For the first question we will be looking at Grade and EGFR:

8) EGFR: Gene responsible for the production of the epidermal growth factor receptor (EGFR) (0 = not mutated, 1 = mutated)
24) Grade: Glioma class information (1 = glioblastoma (GBM), 0 = low grade glioma (LGG))

For the second question we will be looking at Gender and Age_at_diagnosis:

2) Age_at_diagnosis: age of individual at time of diagnosis in years
24) Grade: Glioma class information (1 = glioblastoma (GBM), 0 = low grade glioma (LGG))