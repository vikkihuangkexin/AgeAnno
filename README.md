# AgeAnno

![AgeAnno](https://user-images.githubusercontent.com/112677142/197329862-5871142d-4bbc-45a7-a674-901350000383.png)


Citation:  

Kexin Huang, Hoaran Gong, Jingjing Guan, Lingxiao Zhang, Changbao Hu, Weiling Zhao, Liyu Huang, Wei Zhang, Pora Kim, Xiaobo Zhou, AgeAnno: a knowledgebase of single-cell annotation of aging in human, Nucleic Acids Research, 2022;, gkac847, https://doi.org/10.1093/nar/gkac847

Webpage link:
https://relab.xidian.edu.cn/AgeAnno/#/



# Database introduction:

AgeAnno annotated 5 580 aging-related genes collected from six public resources based on 1 678 610 cells from 28 healthy tissue samples with ages ranging from 0 to 110 years.
For scRNA data, first, we performed differential gene expression analysis for aging-related genes (DEGs) in each cell type and identified tissue- and cell-type-specific DEGs between different age groups. 
Then, we annotated aging-related DEGs into three aging-related biological categories, including immune genes, telomere maintenance genes, and circadian genes. 
To better understand the potential mechanisms of aging-related genes, we performed enrichment analysis and transcriptomic variation analysis to determine aging effect on gene transcriptional noise; 
cell-cell communication analysis based on the coordinated ligand-receptor (L-R) expression; and transcript factor (TF) regulatory network analysis. 
To explore the immune microenvironment alteration in the aging context, we investigated the immune cell proportions between different age groups. 
For scATAC data, we identified differential accessible regions (DARs) between age groups, and provided detailed genetic annotation information such as enhancers, promoters and introns. 
Then, we performed motif/TF enrichment analysis, footprint analysis, and co-accessibility peak analysis to provide functional annotations for aging-related DARs. 
We also identified gene-drug or gene-chemical interactions and related diseases for aging genes. 


![image](https://user-images.githubusercontent.com/112677142/197329805-2ab5a0e2-f8e1-436a-b67b-affde3bb2ba1.png)

# Data legend:

~/scRNA/:

scRNAmarker: cell-type specific marker genes  
Aging-related DEG.txt: aging-related differential expressed genes  
gene_VariationCoefficient.txt: results of transcriptomic variation analysis  
Pathways.txt: aging-related GO pathways  
cell_cell_communication.txt: results of cell-cell interaction analysis  
TF regulon.txt: TF and target genes by using SCENIC  

~/scATAC/:

scATACmarker.txt: cell-type specific marker peaks  
Aging-related DAR.txt: aging-related differentially accessibile regions  
coAccessiblity.txt: results of co-accessibility analysis  
motif-TF.txt: results of motif/TF enrichment analysis  

~/Disease&Drug/:

Related diseases.rar: related diseases for aging-related genes  
Related drugs.rar: related drugs and chemicals for aging-related genes  

The processed rds file for scRNA data were provided in Google Drive. https://drive.google.com/drive/folders/160i9KmFJ0tEYP2QBT5IjbJqhqvuu5rBW?usp=sharing.


