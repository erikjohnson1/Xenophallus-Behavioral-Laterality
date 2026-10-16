# Code and Data for: Behavioral laterality and asymmetry in *Xenophallus umbratilis*

This repository contains the data and R code used for the analyses presented in:

**"Sex-specific patterns of behavioral laterality in the livebearing fish, *Xenophallus umbratilis* (Poeciliidae)"**

The repository provides the dataset and R Markdown workflow necessary to reproduce the statistical analyses and figures reported in the manuscript.

---

## Files

### `Data.csv`
Processed dataset used for all analyses.

### `Xeno Circle - for publication.Rmd`
R Markdown file containing the complete analysis workflow, including:

- Data processing and preparation
- Statistical analyses
- Model fitting
- Figure generation

### `Xeno Circle - for publication.nb.html`
HTML output generated from the R Markdown file showing the executed analysis, code, and results.

---

## Requirements

Analyses were performed in **R** using the following packages:

- tidyverse
- ggplot2
- dplyr
- tidyr
- lme4
- lmerTest
- emmeans
- broom
- purrr

Additional packages may be required depending on the R environment.

To reproduce the analyses:

1. Download or clone this repository.
2. Open `Xeno Circle - for publication.Rmd` in RStudio.
3. Ensure `Data.csv` is located in the same directory as the R Markdown file.
4. Knit the R Markdown document to reproduce the analyses and figures.

---

## Data Availability

The dataset provided here contains the processed data used in the manuscript analyses. All variables required to reproduce the reported results are included in `Data.csv`.

---

## Citation

If you use these data or code, please cite:

Johnson, E. et al.  
*"Sex-specific patterns of behavioral laterality in the livebearing fish, Xenophallus umbratilis (Poeciliidae)."*

---

## Contact

For questions regarding the data or analyses, please contact:

Erik Johnson  
smerikjohnson@gmail.com
