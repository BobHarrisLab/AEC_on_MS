

# Human Placental Stem Cells Induce a Novel Multiple Myeloid Cell-Driven Immunosuppressive Program That Ameliorates Proinflammatory CNS Pathology

**Repository for the code and data used in the manuscript revision submitted to *Nature Communications***

## 📄 Manuscript Abstract

Despite a growing interest in Amniotic Epithelial Cell (AEC)-based therapies, the immune responses triggered by AEC transplantation in vivo remain poorly characterized, particularly within the central nervous system (CNS). Herein we describe a novel CNS-specific immunoregulatory myeloid pathway induced by intracisternal delivery of human AECs, comprising immunosuppressive Arginase 1⁺ (ARG1⁺) macrophages and a novel population of myeloid-derived suppressor cells with eosinophilic characteristics, which we term Eo-MDSCs. We further demonstrate that Eo-MDSCs produce Maresin 2 (MaR2), a specialized pro-resolving mediator (SPM) involved in the resolution of inflammation. In a mouse model of Multiple Sclerosis (MS) with established disease, AEC-induced immunological responses resulted in reduced numbers of pathogenic macrophages and T helper (TH)17 cells, increased anti-inflammatory T cell subsets, and enhanced myelin phagocytosis, culminating in functional recovery. These findings suggest that AEC therapy can target CNS-intrinsic inflammatory processes in MS, providing a strong rationale for translation into the clinic.

---

## 📁 Repository Structure

```
├── data/                         # Processed and raw data used in the study
│   ├── scRNAseq/                 # Single-cell RNA sequencing datasets
│   ├── flow_cytometry/          # Flow cytometry FCS files and gating strategy
│   └── histology/               # Imaging data and quantification outputs
│
├── scripts/                     # Scripts used for data processing and analysis
│   ├── scRNAseq_analysis.R      # Main Seurat pipeline for single-cell analysis
│   ├── DE_analysis.R            # Differential expression analysis code
│   └── flow_analysis.R          # Flow cytometry quantification scripts
│
├── figures/                     # Code for generating figures and supplementary data
│   ├── fig1_immune_landscape.R  # Main figure plotting (e.g., UMAP, barplots)
│   └── supp_figs/               # Scripts for supplementary figures
│
├── results/                     # Output files from analysis
│   └── DE_results/              # CSV files with differential expression stats
│
├── README.md                    # This file
└── requirements.txt             # R or Python package dependencies (see below)
```

---

## 🔧 Setup and Requirements

### For Single Cell RNA Sequencing Data Analysis:

We used [R (≥4.2)](https://www.r-project.org/) with the following R packages:
* `Seurat` ≥ 5.0
* `niceRplot`
* `tidyverse`
* `ggplot2`
* `flowCore`
* `ComplexHeatmap`
* `Gprofiler2`
* `clusterProfiler`
* `enrichplot`
* `Slingshot`
* `tradeSeq`
* `Cellchat`


For Python components:
* `pySCENIC`

### For Bulk RNA Sequencing Analysis:
* `FastQC`
* `HISAT2`
* `DESeq2`
* `Enhanced Volcanoon` 
* `ggvenn`



---

## 🧬 Data Availability

All datasets (processed and/or raw) will be made available upon acceptance via a public repository (e.g., GEO, FlowRepository, Zenodo).

Please refer to the `data/README.md` file in each subfolder for specific descriptions and usage notes.

---



## 🖋️ Citation

If you use this code, please cite:

**\[Author list TBD]**
"Human placental stem cells induce a novel multiple myeloid cell-driven immunosuppressive program that ameliorates proinflammatory CNS pathology."
*Submitted to Nature Communications, 2025.*

---

## 📬 Contact

For questions regarding the code or data, please contact:

* **\[Yuxi Guo]** – \[[yuxi.guo@ki.se](mailto:yuxi.guo@ki.se)]
* **\[Heela Sarlus]** – \[[heela.sarlus@ki.se](mailto:heela.sarlus@ki.se)]
* **\[Robert Harris]** – \[[robert.harris@ki.se](mailto:robert.harris@ki.se)]

---

Would you like me to help generate the actual `requirements.txt`, `data/README.md`, or figure script templates?
