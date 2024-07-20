# Gene-EXpression-Clustering
The primary objective of this project is to analyze and cluster gene expression data obtained from MCF7 cells exposed to different conditions: benzoapyrene, ionizing radiation, or untreated (control)
# Dataset Description
Columns:
Geneid: The unique identifier for each gene, in this case, using the Ensembl Gene ID format (e.g., ENSG00000223972).

Chr: The chromosome(s) where the gene is located. Multiple chromosomes are separated by semicolons.

-Start: The start positions of the gene on the chromosome(s). If a gene has multiple start positions, they are separated by semicolons.

End: The end positions of the gene on the chromosome(s). Like the start positions, multiple end positions are separated by semicolons.

Strand: The DNA strand (either '+' for the forward strand or '-' for the reverse strand) on which the gene is located. Multiple strands for a gene are separated by semicolons.

Length: The length of the gene in base pairs.

Expression: This column contains the expression levels of the genes under specific experimental conditions. The values are numeric and represent the read counts from RNA sequencing.

## Data
The data is taken from GEO database with acession id of GSE234862 

Geneid	Chr	Start	End	Strand	Length	Expression
ENSG00000223972	1;1;1;1;1;1;1;1;1	11869;12010;12179;12613;12613;12975;13221;13221;13453	12227;12057;12227;12721;12697;13052;13374;14409;13670	+;+;+;+;+;+;+;+;+	1735	0
Geneid: ENSG00000223972

This is the Ensembl Gene ID for a specific gene.
Chr: 1;1;1;1;1;1;1;1;1

The gene is located on chromosome 1, and it has multiple exons or regions on this chromosome.
Start: 11869;12010;12179;12613;12613;12975;13221;13221;13453

The start positions of different exons or regions of the gene on chromosome 1.
End: 12227;12057;12227;12721;12697;13052;13374;14409;13670

The end positions of different exons or regions of the gene on chromosome 1.
Strand: +;+;+;+;+;+;+;+;+

The gene is located on the forward strand of the DNA in all these regions.
Length: 1735

The total length of the gene is 1735 base pairs.
Expression: 0

The expression level of this gene under the given experimental condition is 0. This could indicate no expression or very low expression in this particular sample.
Understanding the Context
The dataset description provided:

Title: Impact of benzoapyrene and ionizing radiation on gene expression of MCF7 cells

Organism: Homo sapiens (human)

Experiment Type: Expression profiling by high throughput sequencing

## Summary

The study involves the analysis of transcriptomic gene expression of MCF7 cells.
The cells were stimulated for 120 hours with either benzoapyrene, ionizing radiation, or were untreated (control).
Overall Design:

MCF7 cells were exposed to 1 µM benzoapyrene, 5 Gy ionizing radiation, or nothing for 120 hours.
RNA-seq was used to perform comparative gene expression profiling analysis from 3 independent experiments.
Purpose of the Dataset
The primary aim is to investigate the gene expression profiles of MCF7 cells when exposed to benzoapyrene and ionizing radiation compared to untreated cells. This kind of analysis can help identify which genes are upregulated or downregulated in response to these treatments, providing insights into the molecular mechanisms of stress response, DNA damage repair, and possibly carcinogenesis.

### How This Dataset Fits into my Project

Cluster Genes: Based on their expression levels across different conditions (benzoapyrene, ionizing radiation, and control).
Identify Patterns: Discover patterns of gene expression that might suggest co-regulation or similar functional roles.
Biological Insights: Gain insights into the biological impact of benzoapyrene and ionizing radiation on MCF7 cells, which could have implications for understanding cancer biology and treatment responses.
