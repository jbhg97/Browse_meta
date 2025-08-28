# Browse_meta

## A Global Meta-analysis of non-lethal mammal browsing control methods in forests

Contained in this repository are the input files, code, model outputs, figure outputs and table outputs for a meta-analysis of non-lethal mammal browsing control in forest landscapes. Code is supplied in the form of annotated .qmd files to be run in Rstudio. Input files are in the form of .xlsx or .rds files. Outputs are either .doc, .png or .rds depending on whehter it is a table, figure or modelling object.

### Analysis

Contains input files for both complete and imputed case meta-analyses and the .qmd file that conducts all meta-analytical modelling.

### Data processing

Contains an input file - Meta_full_data.xlsx - that holds all the raw data, description of literature screening process, records of author correspondence. See the meta worksheet for a description of the individual worksheets within this excel workbook. Meta_prelim_process.qmd takes the raw data and conducts any transformations necessary to generate the effect sizes that are fed into the meta-analytical modelling framework. LO and SMD .xlsx and .rds files are checkpoint files saved throughout Meta_prelim_process.qmd describing log odds ratio and standardised mean difference effects for both complete and imputed case meta-analyses.

### Results

Meta_results.qmd takes modelling results stored in the Models folder and extracts relevant information to produce figures for publication stored in the Figures folder. Results_summary_tables.qmd uses modelling results to generate summary tables presented in a supplement - these tables are stored in the Tables folder.
