Mini bulk RNA-seq differential expression analysis using DESeq2


 Project overview
This is a learning project demonstrating **bulk RNA-seq differential expression analysis** using the **DESeq2** R package.  
The aim of this project is to identify genes that are differentially expressed between **Control** and **Treated** conditions and visualise the results using a **volcano plot**.

---

 Dataset
This project uses a **simulated bulk RNA-seq count matrix** created for learning purposes.

- **Genes:** 20
- **Samples:** 4  
  - Control_1  
  - Control_2  
  - Treated_1  
  - Treated_2  

Two input files were generated:
- `raw_counts.csv` – gene expression count matrix  
- `metadata.csv` – sample condition information  

---

 Tools & packages used
- R (≥ 4.4)
- DESeq2
- ggplot2

---

Analysis workflow
1. Creation of a count matrix and metadata table
2. Construction of a `DESeqDataSet`
3. Normalisation and dispersion estimation using DESeq2
4. Differential expression analysis (Treated vs Control)
5. Result extraction and p-value adjustment
6. Visualisation using a volcano plot

---

Outputs
The following outputs are generated and saved:

- `deseq2_results.csv`  
  Differential expression results including:
  - log2 fold change
  - p-value
  - adjusted p-value (FDR)

- `volcano_plot.png`  
  Volcano plot showing:
  - Log2 fold change on x-axis
  - −log10(p-value) on y-axis
  - Significant vs non-significant genes

---

 Key learning outcomes
- Understanding bulk RNA-seq data structure
- Performing differential expression analysis using DESeq2
- Interpreting log2 fold change and p-values
- Visualising RNA-seq results using volcano plots
- Organising reproducible bioinformatics projects

 Outputs

- `deseq2_results.csv`  
  Differential expression results including log2 fold change, p-values, and adjusted p-values.

- `volcano_plot.png`  
  Volcano plot visualising differential gene expression between Treated and Control samples.


Author
Logaprabu Thanigachalam  
MSc Genomic Medicine (incoming)  
Bioinformatics & Genomic Data Science

