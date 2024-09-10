# Introduction
In the past decade, In order to understand the 

# Methodology
I first downloaded the raw 3K PBMC scRNAseq data from [2] and used the scvi-tools to separate doublet and singlet [3]. Then, I used UMAP to cluster cells into different groups. Based on the gene expression pattern on those groups, I can separate 3K PBMC sample into several groups, including NK cell, CD4+ T cell and CD8+ T cell. 


![image](https://github.com/user-attachments/assets/892544c7-68a3-4667-b02a-b3945d7d0496)


# Reference
[1] https://www.nature.com/articles/nprot.2017.149  
[2] https://satijalab.org/seurat/articles/pbmc3k_tutorial.html
[3] https://www.nature.com/articles/s41587-021-01206-w
