# MPAL-Single-Cell-2019 Analysis Code (Granja JM*, Klemm SK*, McGinnis LM*, et al. 2019)

Link : https://www.nature.com/articles/s41587-019-0332-7

## Please cite : Granja JM et al., Single-cell multiomic analysis identifies regulatory programs in mixed-phenotype acute leukemia. Nature Biotechnology (2019)

# Brief Descriptions of Analysis Scripts

## scATAC Analyses

scATAC_01 - Script for reading in 10x scATAC-seq fragments identify cells using number of fragments and TSS enrichment scores and saving fitlered fragments.

scATAC_02 - Script for pre-clustering using large windows genome-wide and then calling peaks on putative clusters and create a master peak set

scATAC_03 - LSI-Clustering + UMAP of scATAC-seq data with visualization and demonstration of how to properly save
umap for projection.

scATAC_04 - Computing Gene Activity Scores using an adapted form of Cicero (Pliner et al 2018).

scATAC_05 - Identifying potential disease cells by clustering disease w/ healthy reference, and then projecting these
cells onto healthy hematopoiesis.

## scRNA Analyses

scRNA_01 - LSI-Clustering + UMAP of scRNA-seq data with visualization and demonstration of how to properly save
umap for projection.

scRNA_02 - Identifying potential disease cells by clustering disease w/ healthy reference, and then projecting these
cells onto healthy hematopoiesis.

## Integration (scATAC + scRNA) Analyses

scRNA_scATAC_Integration_01 - Alignment of scRNA and scATAC-seq data using Seurat CCA and identifcation of nearest
neighbors across modalities.

scRNA_scATAC_Integration_02 - Aggregate scRNA + scATAC-seq data for correlation focused analysis.

scRNA_scATAC_Integration_03 - Identify putative Peak-To-Gene Links with aligned scATAC and scRNA-seq data aggregates.

scRNA_scATAC_Integration_04 - Link TFs to putative target genes that are differential in both mRNA and nearby accessibility peaks containing motifs of the TFs.

# Additional Data Download Links

## Healthy Hematopoiesis

## Healthy + MPAL Data Sets

## Other




