# RNA-Seq Analysis of Breast Cancer vs Normal Tissue (GSE62944)

## 📌 Project Overview

This repository contains a **first-year–level RNA-Seq bioinformatics project** focused on identifying **differentially expressed genes (DEGs)** between **breast cancer tissue and normal breast tissue** using publicly available RNA-Seq data.

The analysis was performed **without coding**, using **GEO2R**, followed by **functional enrichment analysis** (GO Biological Process and KEGG pathways) to understand the biological mechanisms involved in breast cancer.

## 🎯 Objective

* Identify genes that are **upregulated and downregulated** in breast cancer compared to normal tissue
* Perform **functional enrichment analysis** to determine affected biological processes and pathways
* Interpret results in the context of **cancer biology**

## 📂 Dataset Information

* **Dataset:** GSE62944
* **Source:** NCBI Gene Expression Omnibus (GEO)
* **Organism:** Homo sapiens
* **Data type:** RNA-Seq

🔗 Dataset link: [https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE62944](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE62944)

## 🛠 Tools Used

* **GEO2R** – Differential gene expression analysis (web-based)
* **Enrichr** – GO Biological Process & KEGG pathway enrichment
* **Microsoft Excel** – Data filtering and bar chart visualization

## 🔬 Methodology

1. Accessed the GSE62944 dataset from GEO
2. Used GEO2R to divide samples into:

   * Breast cancer tissue
   * Normal breast tissue
3. Performed differential expression analysis using default GEO2R settings
4. Filtered DEGs based on:

   * Adjusted p-value < 0.05
   * |log2 fold change| > 1
5. Performed enrichment analysis:

   * GO Biological Process (BP)
   * KEGG pathways
6. Visualized top enriched terms using bar plots

## 📊 Key Results

### Differential Expression

* Identified multiple **upregulated and downregulated genes** in breast cancer tissue
* Genes show significant expression changes between cancer and normal samples

### GO Biological Process Enrichment

Major enriched biological themes include:

* Lipid and fatty acid metabolism
* Regulation of angiogenesis
* Oxidative stress (hydrogen peroxide metabolism)
* Metabolic reprogramming

### KEGG Pathway Enrichment

Top enriched pathways include:

* PPAR signaling pathway
* AMPK signaling pathway
* PI3K-Akt signaling pathway
* Adipocytokine signaling pathway
* Focal adhesion

These pathways are known to play roles in **tumor metabolism, survival, and progression**.

## ⚠ Notes / Exceptions

* Although the dataset contains **271 samples**, only **211 samples** were successfully processed by GEO2R.
* Some samples were automatically excluded due to **missing expression values or incomplete metadata**.
* This filtering is part of standard GEO2R preprocessing and does not affect overall biological conclusions.


## 📁 Repository Structure

```
├── report/
│   └── Differential_Gene_Expression_and_Functional_Enrichment_Breast_Cancer_RNASeq.pdf
│
├── figures/
│   ├── KEGG_2021_Human_bar_graph.png
│   └── GO_Biological_Process_2025_bar_graph.png
│
├── data/
│   └── genes.tsv
│
└── README.md
```

## 📌 Conclusion

This project demonstrates how publicly available RNA-Seq data can be analyzed using **no-code bioinformatics tools** to uncover meaningful biological insights into breast cancer. The results highlight key metabolic and signaling pathways involved in tumor development and progression.

## 👩‍🎓 Author

**Shriya Arora**
Undergraduate Biotechnology Student
Interested in Bioinformatics & Computational Biology

##📚 References

* GEO: [https://www.ncbi.nlm.nih.gov/geo/](https://www.ncbi.nlm.nih.gov/geo/)
* GEO2R: [https://www.ncbi.nlm.nih.gov/geo/geo2r/](https://www.ncbi.nlm.nih.gov/geo/geo2r/)
* Enrichr: [https://maayanlab.cloud/Enrichr/](https://maayanlab.cloud/Enrichr/)
* KEGG: [https://www.genome.jp/kegg/](https://www.genome.jp/kegg/)
* Gene Ontology: [http://geneontology.org/](http://geneontology.org/)

⭐ *If you found this project useful, feel free to star the repository!*



   

