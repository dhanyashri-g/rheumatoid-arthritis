# 🧬 Bioinformatics Analysis of Hub Genes and Pathways in Rheumatoid Arthritis

This repository presents a project focused on the identification of **hub genes and biological pathways involved in Rheumatoid Arthritis (RA)** using transcriptomics datasets and protein–protein interaction (PPI) network analysis.

---

## 📁 Repository Details

**Title**: Identification of Potential Biomarkers and Pathways in Rheumatoid Arthritis via Gene Expression and PPI Network Analysis  
**Author**: Dhanyashri A/P Guruparan  
**Institution**: Management & Science University (MSU), Malaysia  
**Degree**: Bachelor of Bioinformatics (Hons)  
**Year**: 2023  
**Keywords**: rheumatoid-arthritis, DEG, hub-genes, PPI, GEO, DAVID, Cytoscape, bioinformatics, disease-biomarker

---

## 📌 Project Overview

Rheumatoid Arthritis (RA) is a chronic autoimmune inflammatory disorder primarily affecting joints. Understanding the genetic and molecular mechanisms underlying RA is essential to identifying novel biomarkers and therapeutic targets. This study used public microarray datasets and integrated bioinformatics tools to:

- Identify differentially expressed genes (DEGs) in RA patients
- Perform functional enrichment analysis using Gene Ontology (GO) and KEGG pathways
- Construct PPI networks and extract key hub genes
- Highlight potential biomarkers and gene functions relevant to RA pathogenesis

---

## 🎯 Objectives

1. Identify key DEGs in RA patient datasets retrieved from GEO (GSE205962, GSE224842, GSE80785)
2. Perform enrichment analysis (GO and KEGG) to understand biological functions and pathways
3. Construct protein–protein interaction (PPI) networks for DEGs
4. Detect hub genes that may serve as **potential biomarkers** for RA

---

## 🧪 Tools & Databases Used

| Tool / Database     | Purpose                                                        |
|----------------------|----------------------------------------------------------------|
| **GEO2R**            | Identification of DEGs between patient and control samples     |
| **DAVID**            | GO & KEGG pathway enrichment analysis                          |
| **STRING**           | Protein–protein interaction network construction               |
| **Cytoscape + CytoHubba** | Hub gene extraction via MCC (Maximal Clique Centrality) |

---

## 🔬 Key Findings

### 📊 Differentially Expressed Genes (DEGs)

- **Datasets used**: GSE205962, GSE224842, GSE80785 (total: 74 samples)
- Total DEGs identified:  
  - **Upregulated**: 208  
  - **Downregulated**: 361

### 🧬 Functional Enrichment (GO Terms)

| Category       | Upregulated DEGs                              | Downregulated DEGs                         |
|----------------|------------------------------------------------|--------------------------------------------|
| Biological Process | Neurogenesis                                | One-carbon metabolism, methotrexate resistance |
| Molecular Function | Serine/threonine-protein kinase             | Hydrolase, initiation factor, protease     |
| Cellular Component | Cytoplasmic vesicle, nucleus, sarcoplasmic reticulum | Cell projection, cell membrane          |

### 🔁 KEGG Pathway Analysis

| Upregulated Pathways           | Downregulated Pathways                        |
|--------------------------------|-----------------------------------------------|
| Olfactory transduction         | TGF-beta signaling, cancer pathways, colorectal & pancreatic cancer |

### 🔗 PPI Network Results

- **Upregulated DEGs**: 183 nodes, 111 edges  
- **Downregulated DEGs**: 309 nodes, 384 edges  
- Highest connectivity:  
  - **Upregulated**: EIF1  
  - **Downregulated**: CTNNB1

### 🔎 Top 10 Hub Genes

**Upregulated**:  
`RPS3, EIF1, EIF2S3, GNB2L1, RPS23, RPS5, RPS2, RPS27A, EIF1AX`

**Downregulated**:  
`SRC, TP53, EGF, HRAS, CTNNB1, EGFR, MYC, AKT1, ACTB, KRAS`

---

## ✅ Conclusion

This study used transcriptomic profiling and systems biology tools to identify **biologically significant genes** and pathways in RA. The integration of GEO2R, DAVID, STRING, and Cytoscape enabled the discovery of critical hub genes like **EIF1, SRC, TP53, and CTNNB1**, which are closely associated with inflammation, immune response, and joint degradation in RA.

These genes represent **promising biomarkers and potential drug targets**, warranting further experimental validation and clinical investigation.

---

## 🔭 Future Work

- Validate identified hub genes through **wet-lab experiments**
- Extend analysis with **RNA-seq data** for higher resolution
- Explore **drug–gene interaction networks** to identify potential therapies
- Apply **machine learning models** to classify RA severity using these biomarkers

---

## 📜 License

This work is licensed under the **MIT License**. Free for academic and research use. Attribution to the author and MSU is required.

---

| This work is original and solely belongs to the author (Dhanyashri) and MSU. All materials and results are intended for academic and non-commercial research purposes only.
