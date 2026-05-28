# Supplementary Materials: TransCisPredict

Supplementary tables accompanying the manuscript:

**Leveraging cis- and trans-variants to improve protein expression level prediction for proteome-wide association studies**

Rui Dong<sup>1,5</sup>, Derek Lamb<sup>1,2,5</sup>, Gao T. Wang<sup>1</sup>, Andrew T. DeWan<sup>3</sup>, Suzanne M. Leal<sup>1,4,\*</sup>

<sup>1</sup> Center for Statistical Genetics, Gertrude H. Sergievsky Center, and the Department of Neurology, Columbia University Medical Center, New York, NY 10032, USA

<sup>2</sup> Department of Biostatistics, Mailman School of Public Health, Columbia University, New York, NY 10032, USA

<sup>3</sup> Department of Chronic Disease Epidemiology and Center for Perinatal, Pediatric and Environmental Epidemiology, Yale School of Public Health, 1 Church Street, New Haven, CT 06510, USA

<sup>4</sup> Taub Institute for Alzheimer's Disease and the Aging Brain, Columbia University Medical Center, New York, NY 10032, USA

<sup>5</sup> These authors contributed equally to this work.

<sup>\*</sup> Correspondence: sml3@cumc.columbia.edu

---

## Overview

This repository hosts the supplementary materials for the TransCisPredict manuscript. TransCisPredict is a method for proteome-wide association studies (PWAS) at biobank scale that incorporates both *cis*- and *trans*-variants to predict protein expression levels. The method uses linkage-disequilibrium (LD) block selection to reduce computational burden and applies four prediction methods — BayesR, Elastic Net, LASSO, and SuSiE — selecting the optimal one per protein via five-fold cross-validation.

Weight estimation was performed using White British UK Biobank study subjects with proteomic and genotype array data (N = 42,644). A PWAS for type 2 diabetes (T2D) was performed in the remaining White British UK Biobank subjects without proteomic data (N = 364,132), followed by two-sample Mendelian randomization for validation.

Please refer to the manuscript for full methodological details.

## Contents

| File | Description |
|------|-------------|
| `Supplementary_Tables.xlsx` | Excel workbook containing Supplementary Tables S1–S11 |
| `README.md` | This file |

The Excel workbook contains 11 supplementary tables (S1–S11) referenced in the manuscript. Each table appears on its own worksheet; see the manuscript for table titles, column definitions, and the in-text references where each table is cited.

## Manuscript

The preprint is available on bioRxiv: *[link to be added upon posting]*

If you use these supplementary materials in your work, please cite:

> Dong R, Lamb D, Wang GT, DeWan AT, Leal SM. Leveraging cis- and trans-variants to improve protein expression level prediction for proteome-wide association studies. *[Journal / bioRxiv]*, 2026.

A `CITATION.cff` file will be added once a DOI is available.

## Data sources

The underlying individual-level UK Biobank data used to derive these tables are not redistributed here. Access to UK Biobank data is available to approved researchers through the [UK Biobank Access Management System](https://www.ukbiobank.ac.uk/enable-your-research/apply-for-access). This work was conducted under UK Biobank Application Number 32285.

## License

The supplementary tables in this repository are released under the **Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)**.

See the [`LICENSE`](LICENSE) file or <https://creativecommons.org/licenses/by-nc/4.0/> for the full license text.

The accompanying manuscript on bioRxiv is licensed separately under CC BY-NC-ND 4.0.

## Contact

For questions about the supplementary materials or the manuscript, please contact the corresponding author:

**Suzanne M. Leal** — <sml3@cumc.columbia.edu>

For issues specific to this repository, please open a GitHub issue.
