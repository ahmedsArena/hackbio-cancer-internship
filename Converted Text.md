<!--StartFragment-->

**The curse of dimensionality and cancer informatics:**

Dimensions in machine learning refer to factors on which a model is being trained. A popular opinion says that; more factors lead to a more accurate model. But, that is not the case if we add dimensions above a certain threshold it may lead to complications  For example: We are training a model to identify a ball and we give the model three factors 

1. Sphere ( YES )  

2. Playable ( YES ), 

3. Eatable( NO ). 

To this point, a model can identify any ball it comes across. But, if we add more factors for example. 

1. Sphere ( YES ) 

2. Playable ( YES ) 

3. Eatable ( YES ) 

4. Red ( YES ) 

Now the model has an increased dimension i.e factor but it will fail to detect any ball that is not red. 


# **Dealing with cancer data:**

 When it comes to cancer data, researchers are mostly using single-cell RNA sequencing data to check for specific biomarkers. So, For example, a researcher has 30 samples and sequenced of 10,000 cells per sample, 300,000 cells in total, from 300,000 cells he is checking for gene expression of more than 20,000 genes in these cells. Now, in order to get any meaningful data a researcher has to analyze 20,000 dimensions from 300,000 samples. 

This tells us why dimensionality is a curse. 


## **How to solve this?:**

To solve this we use dimension reduction. We combine relevant dimensions to form new dimensions to reduce complexity by using different algorithms such as PCA ( principal component analysis) , SVD ( singular value decomposition ) etc . In the case of cancer, we categorize cells into sub-cells i.e. epithelial cells, endothelial cells, lung cells, brain cells, etc.  This will reduce the complexity of the data and make it easy to analyze different data sets. 

\



### **Applications:**

1. **Precision medicine:** 

As discussed previously the curse of dimensionality cancer limits progress in precision medicine research when a large amount of data is available in the form of single-cell RNA seq and or microarray.  We can avoid this by developing newer algorithms that can reduce dimensions. 

2. **Drug discovery :** 

It can sabotage the process when testing for antibody therapies in in-silico models.

3. **Clinical data for building new models :**

Development of ML models can be affected due to this curse of dimensionality when researchers have fewer samples but multiple genes, this may lead to imbalance and production of non-useful models.  

\


By using right statistical methods, utilising and developing effective reduction techniques we can overcome this curse of dimensionality.

**References:**

1. **Altman, N., & Krzywinski, M. (2018). The curse(s) of dimensionality.** [****https://doi.org/10.1038/s41592-018-0019-x****](https://doi.org/10.1038/s41592-018-0019-x) ****

2. **Bhinder, B., Gilvary, C., Madhukar, N. S., & Elemento, O. (2021). Artificial Intelligence in Cancer Research and Precision Medicine. _Cancer Discovery_, _11_(4), 900.** [****https://doi.org/10.1158/2159-8290.CD-21-0090****](https://doi.org/10.1158/2159-8290.CD-21-0090) ****

\


<!--EndFragment-->
