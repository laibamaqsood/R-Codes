# KEGG Pathway Enrichment Visualization

This repository contains R code for visualizing KEGG pathway enrichment results using **dot plots** and **lollipop plots**. These visualizations help in identifying and presenting biologically significant pathways from enrichment analysis in a clear and publication-ready format.

---

##  Overview

The analysis visualizes enrichment results (p-values, q-values, and overlapping genes) from a dataset of potassium channel-related pathways.  
Two main types of plots are included:

1. **Dot Plot** – Highlights pathway significance and gene counts using color and size.
2. **Lollipop Plot** – Provides a clear visual representation of the most significant KEGG pathways.

---

##  Data Description

The enrichment data includes:
- **Terms** – KEGG pathway names.
- **p_value** – Statistical significance of enrichment.
- **q_value** – Adjusted p-value for multiple testing.
- **Overlap_genes** – Genes overlapping with the pathway.
- **gene_count** – Number of overlapping genes (automatically calculated).

Example data:
```r
Terms: "GnRH secretion", "Cholinergic synapse", ...
p_value: 6.67E-08, 6.64E-07, ...
Overlap_genes: [KCNJ5, KCNJ6, KCNJ11, SPP1]
