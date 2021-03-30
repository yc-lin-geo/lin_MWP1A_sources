# Code supporting "A reconciled solution of Meltwater Pulse 1A sources using sea-level fingerprinting" by Lin et al. (2021)

This repository contains the Python code base for [Lin et al. 2021]:  "A reconciled solution of Meltwater Pulse 1A sources using sea-level fingerprinting".

**Project abstract:**

> The most rapid global sea-level rise event of the last deglaciation, Meltwater Pulse 1A (MWP-1A), occurred ∼14,650 years ago. Considerable uncertainty regarding the sources of meltwater limits understanding of the relationship between MWP-1A and the concurrent fast-changing climate. Here we present a data-driven inversion approach, using a glacio-isostatic adjustment model to invert for sources of MWP-1A via sea-level constraints from six geographically distributed sites. The results suggest contributions from Antarctica, 1.3 m (0-5.9 m; 95% probability), Scandinavia, 4.6 m (3.2-6.4 m) and North America, 12.0 m (5.6-15.4 m), giving a global mean sea-level rise of 17.9 m (15.7-20.2 m) in 500 years. Only a North American dominant scenario successfully predicts the observed sea-level change across our six sites and an Antarctic dominant scenario is firmly refuted by Scottish isolation basin records. Our sea-level based results therefore reconcile with field-based ice sheet reconstructions.

If you have any questions, comments, or feedback on this work or code, please [contact Yucheng](mailto:yucheng.lin@durham.ac.uk)

## Citation



## Data

The data used to construct the MWP-1A inversion used in this work has been archived at Zenodo


[![DOI](https://zenodo.org/badge/320596270.svg)](https://zenodo.org/badge/latestdoi/320596270)


## Getting Started

This codebase requires **Python version 3.5+** to run. It was written and tested with Python 3.5.2 and Jupyter Notebook 5.4.0.

### Dependencies

* [Pandas](https://pandas.pydata.org/) 1.0.1
* [NumPy](https://numpy.org/) 1.18.1
* [SciPy](https://www.scipy.org/) 1.4.1

## File Descriptions
* **[MWP-1A_sources_inversion.ipynb](./MWP-1A_sources_inversion.ipynb)** - A notebook contains the code used for MWP-1A sources inversion
* **RSL magnitude/Lin et al., Sup data.xlsx** - A excel spreadsheet contains the 20,000 samples of local MWP-1A sea-level rise magnitude at six sea-level sites, which are the input for our inversion. It also contains the inversion results for each iteration. Four spreadsheets contained with this excel file, please see the first description sheet for details.
* **[RSL magnitude/fingerprint.csv](RSL magnitude/fingerprint.csv)** - A csv file contains a 6x3 sea-level fingerprints matrix. Each row corresponds to each sea-level site and each column corresponds to each ice sheet.  


## Corresponding Author

* **Yucheng Lin**

### Co-authors
* **Dr Fiona Hibbert**
* **Dr Pippa Whitehouse**
* **Dr Sarah Woodroffe**
* **Dr Anthony Purcell**
* **Prof. Ian Shennan**
* **Dr Sarah Bradley**

## License

This project is licensed under the MIT License - see the [LICENSE] file for details

## Acknowledgments

We thank Chris D. Clark, Jeremy C. Ely and Henry Patton for providing their ice models, W.R Peltier and Lev Tarasov for making their ice models publicly available. Y.L. was supported by China Scholarship Council Durham University joint scholarship. F.D.H. received funding from the European Union’s Horizon 2020 research and innovation programme under the Marie Skłodowska-Curie grant agreement (No. 838841 – ExTaSea). S.L.B was supported by the Natural Environment Research Council consortium grant BRITICE-CHRONO NE/J009768/1 and has benefited from the PalGlac team of researchers and received funding from the European Research Council (ERC) to Chris Clark under the European Union’s Horizon 2020 research and innovation programme (Grant agreement No. 787263). The authors acknowledge PALSEA, a working group of the International Union for Quaternary Sciences (INQUA) and Past Global Changes (PAGES), which in turn received support from the Swiss Academy of Sciences and the Chinese Academy of Sciences. GIA calculations in this study were performed on the Terrawulf cluster, a computational facility supported through the AuScope Australian Geophysical Observing System (AGOS) and the Australian National Collaborative Research Infrastructure Strategy (NCRIS).
