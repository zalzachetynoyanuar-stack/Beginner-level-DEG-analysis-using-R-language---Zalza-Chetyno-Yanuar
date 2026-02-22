\# In this day and age biological research generates large volumes of
data that require computational tools for proper analysis and
interpretation. One of the most widely used platforms for data analysis
is Rstudio. RStudio is commonly used to analyze gene expression
datasets, perform statistical testing, and generate visualizations such
as heatmaps and volcano plots from the data obtained from experiments.
With Rstudio there are lots of add ins which can help facilitate the
analysis of gene expression data, such as GEOquery to retrieve data
directly from the NCBI GEO database, limma to calculate P-values and
DEGs, BiocManager for bioinformatics analysis, ggplot2 to create volcano
plots, pheatmap to create heatmaps etc. Analysing GSE48018 (Vaccine vs
Baseline) with Microarray (Illumina HumanHT-12 V4.0 - GPL10558) platform
using Rstudio, in this analysis we expected to obtained upregulated and
downregulated genes that are displayed as a volcano plot, top 50
Differentially Expressed Genes (DEGs) that are displayed as a heatmap,
and the enrichment analysis. After analysis using the Rstudio is
complete, we are able to get lots of information

1\. Based on the volcano plot and the data that are used for the volcano
plot, these are the list of upregulated and downregulated genes
\[Volcano Plot Data\]
(https://drive.google.com/file/d/1wcyuSaBaUwZ7oJAoHIqnvSpz_YTY_Gqv/view?usp=sharing)
\![Volcano
Plot\](https://drive.google.com/file/d/1_C_P5yLZI8NpjZLCUqQS45BiV-B4cmKS/view?usp=sharing)

2.Heat Map \[Top 50 Heat Map data\]
(https://drive.google.com/file/d/1nVrmz7IqCOOE525T6SHi0fmbyzz6-by8/view?usp=sharing)
\![Heat
map\](https://drive.google.com/file/d/12tUmo33YD4ioG6ZLcHciDgn88004Q0Ju/view?usp=sharing)

3\. Gene Ontology \[Gene Ontology Data\]
(https://docs.google.com/spreadsheets/d/1-Oyf0dQjBNdA6snvUt9mlNVoB8Wn21ip/edit?usp=sharing)

4.KEGG Pathway \[KEGG Pathway Data\]
(https://docs.google.com/spreadsheets/d/1HGpRaAbBSXffpLBhL3rzMZUZ_KMzuiIT/edit?usp=sharing)
\![KEGG Visualization\]
(https://drive.google.com/file/d/1eHJIrA4-WmpDL9izn5kgwDoNfIWR-cZ-/view?usp=sharing)

\## Out of 260 top table results, 50 are downregulated and 77 are
upregulated. This means that the 50 genes are downregulated in the
baseline samples and 77 genes are upregulated in the baseline samples.
Out of the top 50 DEGs, 17 are downregulated and 33 are upregulated.
Gene Ontology (GO) analysis revealed that many of the upregulated genes
are involved in immune response, regulation of gene expression, signal
transduction, and antiviral defense mechanisms. Several genes such as
STAT1, TLR7, GBP1, GBP2, and IFIT2 are associated with interferon
signaling and innate immune pathways, which play important roles in
antiviral responses. KEGG analysis further back up the GO with most
pathway in the top 50 function as immune responses, and genetic
information processes.

\### The gene expression analysis shows clear differences in gene
activity in the dataset. Out of the 260 genes from top table results,
more genes were upregulated than downregulated in the baseline samples.
Among the top 50 DEGs, 33 genes were upregulated and 17 were
downregulated. Further analysis using Gene Ontology and KEGG pathways
indicates that many of the upregulated genes are related to immune
response, interferon signaling, and gene regulation. In general, the
results show that immune-related pathways play an important role in the
gene expression patterns observed in this dataset
