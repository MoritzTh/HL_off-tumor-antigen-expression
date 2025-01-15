# Computational assessment of on-target, off-tumor toxicities of targets for CAR-T cell therapy in HL


This repository contains all jupyter notebooks to reproduce the results of the single cell cross-organ CAR T target expression analysis from:

Dissection of single-cell landscapes for the development of chimeric antigen receptor T cells in Hodgkin lymphoma
Gottschlich et al, 2025 (Blood)

The notebooks contain code for the following analyses:

- Preprocessing and Harmonization of multiple public single cell RNA datasets
- Plotting expression patterns of targets for CAR-T cell therapy in HL


Note that the analysis was done in python 3 using ```scanpy``` v.1.4.6 to 1.9.1 and ```anndata``` v.0.7.1 to 0.8.0 unless otherwise stated. 
Some functions may have changed when using other package versions. Additionally, ```numpy``` (v. 1.18.2+), ```pandas``` (v. 1.3.5+) and ```scipy``` (v. 1.4.1+) are required. 
Numeric results can vary depending on package versions and e.g. minor results. All scRNA-seq figures were plotted using matplotlib and seaborn.

If the materials in this repository are of use to you, please consider citing the above publication.
