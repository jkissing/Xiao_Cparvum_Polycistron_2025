# Xiao_Cparvum_Polycistron_2025

![Project Status](https://img.shields.io/badge/status-active-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue) ![Contributors](https://img.shields.io/badge/contributors-1-orange)

Welcome to the repository for the Xiao et al. 2025 *Cryptosporidium parvum* polycistron paper! This repository contains all the scripts and tools used to analyze data and generate results for the manuscript.

---

## 📚 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Usage](#usage)
- [Shell Scripts](#shell-scripts)
- [Python Scripts](#python-scripts)
- [R Scripts](#r-scripts)
- [Contributors](#contributors)
- [License](#license)

---

## About the Project

This project focuses on analyzing polycistronic transcription in *Cryptosporidium parvum*. It includes tools and scripts for processing various sequencing data types, performing statistical analyses, and generating visualizations.

---

## Features

- Comprehensive analysis pipeline for RNA-seq and ATAC-seq.
- Tools for transcript modeling and codon usage analysis.
- Poly-A tail length assessment and single-cell atlas visualization.
- Easily adaptable scripts for diverse datasets.

---

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/jkissing/Xiao_Cparvum_Polycistron_2025.git
   ```
2. Navigate to the desired script directory.
3. Follow the instructions provided in each script to execute the analyses.

---

## Shell Scripts

| Script                         | Description                                                                 |
|--------------------------------|-----------------------------------------------------------------------------|
| `splice_leader_discovery`      | Small RNA-seq-based splice-leader discovery.                               |
| `atac_meme_run`                | Processes and analyzes ATAC-seq data.                                      |
| `illumina_trimming`            | Trims single or paired-end Illumina reads using `trim_galore`.             |
| `long_read_process`            | Processes PacBio Iso-seq and Oxford Nanopore Direct RNA-seq data.          |
| `tama_processing`              | TAMA-based transcript modeling using long-read RNA-seq.                    |
| `short_read_rnaseq_process`    | Handles Illumina RNA-seq processing.                                       |
| `long_read_abundance`          | Generates read abundance per annotated transcript models.                  |
| `run_sqanti3`                  | Produces SQANTI3 quality reports for long-read RNA-seq data.               |
| `polya_analysis`               | Conducts poly-A tail length analysis using Direct RNA-seq data.            |
| `start_stop_codon_sequence_extract` | Analyzes Kozak sequences and polyadenylation signals.                    |
| `peptide_analysis`             | Performs peptide mapping and enrichment analysis.                          |

---

## Python Scripts

| Script                          | Description                                                                 |
|---------------------------------|-----------------------------------------------------------------------------|
| `polycis_finder`                | Identifies de novo polycistrons from TAMA-discovered and SQANTI3-processed transcript models. |
| `polycis_chi_square_distribution` and `polycis_autocorrelation` | Analyze polycistron distributions using chi-square and autocorrelation methods. |
| `codon_analysis`                | Examines codon usage patterns.                                              |

---

## R Scripts

| Script               | Description                                                       |
|----------------------|-------------------------------------------------------------------|
| `polya_R`            | Visualizes and analyzes poly-A tail lengths.                     |
| `single_cell_analysis` | Analyzes publicly available *C. parvum* single-cell atlas data. |

---

## Contributors

- **Author:** Xiao et al. (2025 manuscript lead)
- **Maintainer:** [Your Name](https://github.com/jkissing)

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

🌟 **If you find this repository helpful, please consider starring it!**

