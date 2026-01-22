# Interactive Metagenomic Visualization – Seawater Sample (Barcode 14)

## Overview

This repository contains **interactive visualizations** generated from a **Nanopore-based 16S metagenomic analysis** of a **single seawater sample (Barcode 14)**. The plots complement the static figures presented in the *NGS Metagenome Analysis Report* and enable dynamic exploration of taxonomic composition and abundance.

Due to limitations of word-processing software, interactive plots are hosted online and accessed via web browsers.

---

## Sample Information

* **Sample type:** Seawater
* **Sequencing platform:** Nanopore
* **Target:** Full-length 16S rRNA gene
* **Number of samples:** 1
* **Sample ID:** Barcode 14

---

## Bioinformatics Workflow Summary

1. **Quality control & preprocessing**

   * Adapter trimming using **Porechop**
   * Read quality assessment using **NanoStat**

2. **Taxonomic classification**

   * Classification performed using **KrakenUniq**
   * Reference database derived from NCBI RefSeq
   * Species-level read counts extracted

3. **Data processing**

   * Removal of taxa with zero abundance
   * Organization of taxonomic hierarchy from superkingdom to species
   * Handling of missing annotations as *Unknown*

---

## Interactive Visualizations Included

### 1. Krona Interactive Plot

* **File:** `interactive_plots.html`
* **Tool:** Krona (ktImportText)
* **Description:**

  * Hierarchical, zoomable visualization of taxonomic composition
  * Displays relative abundance across taxonomic ranks
  * Enables intuitive exploration from kingdom to species level


---

## How to View the Interactive Plot

1. Open the following link in a web browser:
   [![View Plot](https://img.shields.io/badge/View-Interactive%20Plot-blue?style=for-the-badge)](https://vettribiomed.github.io/Interactive-plot-Krona-/interactive_plot.html)

2. Download the interactive_plot.html raw file and open the file in the system

3. Use mouse or trackpad to:

   * Zoom into specific taxa
   * Explore hierarchical relationships
   * Inspect relative abundances interactively

> **Note:** Interactivity is not supported directly within Microsoft Word. Static images are included in the main report, while interactive versions are hosted here.

---

## Notes on Comparative Analysis

This project involved **only a single sample**. Therefore:

* No cross-sample comparative analysis was performed
* Relative abundance visualizations represent **within-sample distributions only**

---

## Repository Contents

```
├── interactive_plots.html   # Krona interactive visualization
├── README.md                # This file
```

---



## Contact

**Vettri BioMed Technologies Private Limited**
Andimadam, Tamil Nadu, India
📧 [ngsservices@vettribiomed.com](mailto:ngsservices@vettribiomed.com)
🌐 [www.vettribiomed.com](http://www.vettribiomed.com)


