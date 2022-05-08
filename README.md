# huSync (Human Sync) Code Repo
## Code to extract data and compute Dyadic Synchronization between dyads in small-group setups
## Use Case: Musical Joint Actions

Note:
This repository contains the code that was developed in order to compute Dyadic Synchronization between co-performers in a small group of musicians. 
You will find two files:
  1. Module_DataExtraction
  2. Module_DyadicSynchronization

Module_DataExtraction:
Contains code that extracts the data for each performers by isolating them individually, and stores trajectory information as a .csv file

Module_DyadicSynchronization:
Contains code that extracts data from the .csv file processed by the first file (Module_DataExtraction), and provides the Dyadic Synchronization between all possible pairs in the musical ensemble.

Both the files have been shared as a jupyter notebook since this should make it easier to execute the code and helps perform experiments with more control. 

##### Author

Sanket Rajeev Sabharwal
UniGe, InfoMus-Casa Paganini
4709433
