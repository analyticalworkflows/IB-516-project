Raw data files for OYTB and QGBCC Rockfish complex species analysis.

OYTB workflow:

1) wt.txt is the most recent data download from the Microsoft Access Database.
  -used to create a Recruitment2024.csv table (data_prep/legacy_recruitment_table.R)

2) props_sfla contains settlement rates for the Black and Yellowtail Rockfish (OYTB complex) and must be merged with the Recruitment2024.csv file created using the legacy code_recruitment_table_CR.R. 
This is done using the data_prep/OYTB_recruitment_table_CR.R script to create species_recruitment_CR.R file that can then be used in the species_specific_settlement_plots.R file for species specific settlement rates/plots.

QGBC workflow:

1) wt.txt is the most recent data download from the Microsoft Access Database.
  -used to create a Recruitment2024.csv table (data_prep/legacy_recruitment_table.R)

TO BE CONTINUED...
