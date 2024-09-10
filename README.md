# Introduction
In the past decade, single-cell RNAseq technology transformed our understanding of health and disease [1]. It provides a higher resolution of cellular differences and a better understanding of each individual cell in our body or diseases. In order to better understand the analysis procedure and the power of single-cell RNAseq, I read the protocol and followed the procedure to analyze single-cell RNAseq raw data [2]. 

# Procedure. 
I first downloaded the raw 3K PBMC scRNAseq data from [2]. Then I used scvi-tools to predict and separate doublet and singlet [3]. 

Then, I got ribosomal and mitochondrial genes and filtered out the data with high level of mitochondrial gene expression. Because it could be an indicator of pool sample quality, apoptotic cells or lysed cells.

Finally, I used PCA and UMAP to cluster cells into different groups. Based on the gene expression pattern on those groups, I can identify several groups, including NK cell, CD4+ T cell and CD8+ T cell. 

![image](https://github.com/user-attachments/assets/892544c7-68a3-4667-b02a-b3945d7d0496)


# Reference
[1] https://www.nature.com/articles/nprot.2017.149  
[2] https://satijalab.org/seurat/articles/pbmc3k_tutorial.html
[3] https://www.nature.com/articles/s41587-021-01206-w
[4] https://kb.10xgenomics.com/hc/en-us/articles/360001086611-Why-do-I-see-a-high-level-of-mitochondrial-gene-expression
