# Commission Ideas Project
 
This page contains the materials to reproduce the findings in Graham, Schoonvelde, Swinkels that examines Commission ideas in the European Semester.

The Semester document data can be found [here](Data/.). 

This folder contains two RMarkdown files:

- **1_Data_Cleaning_and_LSS_Estimation.Rmd** reads in the Semester documents, cleans them, and estimates the LSS model. The file also contains numerous validity checks. At some point in the script, the various seed dictionaries (located [here](Dictionary/.)) are read in. 
- **2_Analysis_CSR.Rmd** produces the figures and tables as reported in the paper. It relies in part on Eurobarometer data [here](EB_data/.) and unemployment data [here](Econ_data/.)


