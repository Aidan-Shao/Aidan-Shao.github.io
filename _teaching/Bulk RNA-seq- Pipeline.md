---
title: "Zebrafish Bulk RNA-seq Analysis Pipeline"
collection: teaching
type: "Teaching Resource"
permalink: /teaching/2024-Bulk-RNA-seq-Pipeline
date: 2024-08-01
location: "West Lafayette, USA"
---

### Course Description: Bulk RNA-seq Analysis Pipeline

This teaching resource provides a comprehensive guide to performing bulk RNA-seq analysis especially for zebrafish. The pipeline is designed for researchers and students looking to understand and implement RNA-seq data processing and analysis using a step-by-step approach. The resource includes detailed instructions, code snippets, visual aids, and explanations to ensure a clear understanding of each stage of the pipeline, from raw data acquisition to differential expression analysis.

**Structure of the Pipeline:**

1. **Introduction to Bulk RNA-seq**
   - Overview of RNA-seq technology and its applications.
   - Differences between bulk RNA-seq and single-cell RNA-seq.
   - Key considerations and challenges in RNA-seq analysis.

2. **Data Acquisition and Quality Control**
   - **Images:** Flowchart of data acquisition steps.
   - **Code:** Scripts for downloading raw RNA-seq data from public repositories (e.g., SRA, GEO).
   - **Text:** Explanation of quality control processes, including tools like FastQC and MultiQC.

3. **Read Alignment and Quantification**
   - **Images:** Diagram of alignment process.
   - **Code:** Example commands for using STAR or HISAT2 for read alignment.
   - **Text:** Discussion of different aligners and their advantages/disadvantages.

4. **Transcript Assembly and Quantification**
   - **Images:** Flowchart illustrating transcript assembly.
   - **Code:** Example pipeline for transcript quantification using tools like StringTie or featureCounts.
   - **Text:** Considerations for choosing transcript assembly methods.

5. **Differential Expression Analysis**
   - **Images:** Example of a volcano plot for differential expression results.
   - **Code:** R scripts for performing differential expression analysis with DESeq2 or edgeR.
   - **Text:** Guidelines for interpreting results, including p-value adjustments and biological relevance.

6. **Visualization and Interpretation**
   - **Images:** Examples of heatmaps, PCA plots, and gene ontology enrichment results.
   - **Code:** R scripts for visualizing RNA-seq data.
   - **Text:** How to present and interpret the results in a biological context.

7. **Final Thoughts and Best Practices**
   - **Text:** Summary of best practices in bulk RNA-seq analysis.
   - **Images:** Checklist of steps for ensuring robust analysis.

**Additional Resources:**
- Links to external resources, tools, and databases.
- References to relevant literature and tutorials for deeper understanding.

---

By following this pipeline, users will be equipped with the knowledge and tools necessary to conduct robust bulk RNA-seq analyses, interpret the results, and apply them to their research projects.
