## Monterey Bay Aquarium Research Institute
Last Update August 15, 2025 05:32PM PST

### Author:
Dominic Kyle Ypil
dominickyle.ypil@sjsu.edu
github.com/domspizza/

### Acknowledgement:
Data was provided from the Biological Oceanography Group. To access the most current version, email chfr@mbari.org or kpitz@mbari.org.

### Data Location:
https://github.com/domspizza/MBARI_Internship

### Data Content:
1. BCTD_data.ipynb
   - CTD data
2. CUTI_BEUTI.ipynb
   - CUTI and BEUTI analysis
3. QIIME2_Analysis.ipynb
   - QIIME2 analysis and PCA
5. Top20.ipynb
   - Create top 20 ASV
7. C1_DATA_20250723.csv
8. outside_18S_asv_filtered.csv
9. outside_18S_meta_filtered.csv
10. outside_18S_taxa_filtered.csv
11. BEUTI_monthly.csv
12. CUTI_monthly.csv

### Dependencies:
python 3.12,
numpy 2.2.2,
matplotlib 3.10.0,
pandas 2.2.3,
seaborn 0.13.2,
scipy 1.15.1,
cmocean 4.0.3,
qiime2-amplicon 2025.7


### Running Analysis:
Ensure all the files are downloaded from the MBARI_Internship repository and the dependencies are the correct version before running the analysis. 
In addition, the analysis is meant to run on Jupyter lab/notebook with some terminal commands for the QIIME2 analysis. Restart the kernell and run all the cells. 
Read the data frame and make sure the sites and parameters are the right heading. Adjust your code to view other sites and parameters. 12S and COI data not included, reach out to Dr. Francisco Chavez (chfr@mbari.org) or Katie Pitz (kpitz@mbari.org) for additional markers.
