# The Analysis of Sulfur and Nitrogen in Anaerobic Digestion
This report compares the effects of adding a nitrogen and sulfur-rich protein feedstocks to sewage sludge under anaerobic digestion, using hexanaote as a control feedstock. It analyses VFA degradation and pH trend, and uses a first-order kinetic model to determine methane production rate.

## Table of Contents
- [Details](#details)
- [Folder Structure](#folder-structure)
- [Software Requirements](#software-requirements)
- [Usage](#usage)

## Details
- Start date: 2024-05-04
- Last updated: 2024-05-06
- Conctact Info: jh3500@york.ac.uk

## Folder Structure
```bash
-- project/
   |__data
      |__raw/
         |__casein_comp.csv
         |__hex_comp.csv
         |__hex_ph.csv
         |__k_values.csv
         |__keratin_comp.csv
         |__protein_ph.csv
         |__sum_meth.csv
         |__vfa.csv
         |__mol_wt.txt
      |__processed/
         |__model.xlsx
   |__images/
      |__casein_comp.png
      |__hex_comp.png
      |__hex_ph.png
      |__indiv_vfa.png
      |__k_values.png
      |__keratin_comp.png
      |__protein_ph.png
      |__rate_methane.png
      |__total_vfa.png
   |__project.Rproj
   |__README.md
   |__report.pdf
   |__report.qmd
```

## Software Requirements



#### R

- Version: 4.3.3
- Platform: Windows 10 x64 (build 19045)

#### R Packages

- lubridate: 1.9.3
- xfun: 0.42
- tidyselect: 1.2.0
- magrittr: 2.0.3
- glue: 1.7.0
- stringr: 1.5.1
- knitr: 1.45
- timechange: 0.3.0
- generics: 0.1.3
- lifecycle: 1.0.4
- cli: 3.6.2
- snakecase: 0.11.1
- compiler: 4.3.3
- rstudioapi: 0.15.0
- tools: 4.3.3
- janitor: 2.2.0
- rlang: 1.1.3
- stringi: 1.8.3

#### Microsoft Excel

- Microsoft Excel for Microsoft 365 MSO x64 (Version 2403)

## Usage

#### Running the Code

1. Open command prompt
2. Copy repository
```bash
git clone https://github.com/JonoHa11/Sulfur.git
```
3. Naviagte to project directory
```bash
cd Sulfur
```
4. Install Quarto
Follow the instructions [here](https://quarto.org/docs/get-started/) to install Quarto.
5. Run Quarto to generate the report
```bash
quarto render report.qmd
```

#### Building Reports

1. Download raw data from the 'data/raw' directory
2. Run the code from the report.qmd file in R to generate the figures.
3. Figures will be generated in the 'images' directory
