# 🧬 Bulk RNA-seq Analysis Tutorial (Mus musculus)

## 📘 Overview

This repository contains a **beginner-oriented, step-by-step bulk RNA-sequencing (RNA-seq) analysis pipeline** implemented using **Bash and R**.  
The project is designed **for learning and teaching purposes**, guiding newcomers through standard RNA-seq workflows using **publicly available mouse datasets**.

The focus of this project is **methodological training**, not biological discovery.

---

## 🐭 Datasets Used

All primary datasets used in this project are **mouse (*Mus musculus*) datasets**.

### 1️⃣ GEO Series: GSE298151
- **Sample:** GSM9009135  
- **Organism:** *Mus musculus*  
- **Model:** B16 mouse melanoma cell line  
- **Data type:** Bulk RNA-seq  
- **Platform:** Illumina HiSeq 2000  

**Usage in this project:**
- Raw FASTQ quality control
- Adapter trimming
- Genome alignment
- Gene-level quantification
- Differential expression analysis
- Functional enrichment (GO, KEGG, GSEA)

---

### 2️⃣ GEO Series: GSE296967
- **Organism:** *Mus musculus*  
- **Data type:** Bulk RNA-seq  

**Usage in this project:**
- Differential gene expression analysis using DESeq2
- Metadata handling and experimental design
- MA plots and volcano plots

---

## 🧬 Reference Genome and Annotation

- **Reference genome:** *Mus musculus* GRCm39  
- **Gene annotation:** GENCODE vM106  
- **Annotation database:** `org.Mm.eg.db`

---

## 🔁 Analysis Workflow

### 1. Raw Data Processing (Bash)
- Quality control with **FastQC**
- Adapter trimming and filtering with **fastp**
- Genome indexing and alignment with **HISAT2**
- BAM file processing using **samtools**
- Gene-level quantification using **featureCounts**

### 2. Differential Expression Analysis (R)
- Import of count matrices
- Metadata preparation
- Differential expression analysis using **DESeq2**
- MA plots and volcano plots

### 3. Functional Analysis (R)
- Gene annotation
- **GO enrichment analysis**
- **KEGG pathway analysis**
- **Gene Set Enrichment Analysis (GSEA)**

---

## 🧪 Educational Scope

This project is intended to:
- Introduce beginners to bulk RNA-seq analysis
- Demonstrate best practices in RNA-seq workflows
- Provide a reproducible reference pipeline
- Serve as a learning resource for students entering bioinformatics

**No biological or clinical conclusions are claimed.**

---

## 🛠️ Tools and Technologies

- **Bash**
- **R**
- FastQC
- fastp
- HISAT2
- samtools
- featureCounts
- DESeq2
- clusterProfiler
- org.Mm.eg.db

---


---

## 👤 Author

**Sara Tolba**  
📧 sarahtolba842@gmail.com  
🔗 GitHub: https://github.com/sarahtolba

---

## ⚠️ Notes

- Internet access is required to retrieve public datasets.
- Parameters can be adjusted depending on dataset size and learning goals.
- This repository is meant for **training and demonstration purposes only**.

