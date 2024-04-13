# Neuroblastoma_prognosis

This repo is for the LMP1210H S LEC0101 course final project. For the project, I trained L1-regularized logistic regression (L1-LR) and random forest (RF) models using RNA-seq data, sex, and age-of-onset of primary Neuroblastoma tumours to predict patient Treatment-related Survival (TS) and Overall Survival (OS). This could potentially help reduce irradiation in patients who do not need as much intensive as high-risk patients, and, thus, reduce life-long treatment-caused side effects.

# Folder structure
## rawData
This folder contains downloaded data for analyses. 

-  Files with names starting with GSE49711 were the datasets eventually used.
-  download.sh contains code and note for data download process

## analysis
This folder contains the code for all analyses

- Kmeans_clustering.ipynb is for K-means clustering, visualization, and evaluation. Because unsupervised clustering didn't perform well. I did not include the analysis and results in the final report.
- classLabelPred_meta-RNA_final.ipynb contains all the code used to preprocess data, generate the L1-LR & RF models, and select model for Treatment-related Survival (TS).
- death-vs-noProgression_meta-RNA_final.ipynb contains all the code used to preprocess data, generate the L1-LR & RF models, and select model for Overall Survival (OS).
- plot_metric_comparsion.ipynb contains code to compare model performance and plot the figures for the comparison. 
- Archived folder contains other codes not included in the final report.
