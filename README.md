# Code Repository
## Code to extract data and compute Dyadic Synchronization for co-performers in a musical ensemble

Note:
This repository contains the code that was developed in order to compute Dyadic Synchronization between co-performers in a small group of musicians. 
You will find two files:
  1. Module_DataExtraction
  2. Module_DyadicSynchronization

Module_DataExtraction:
This file contains the code that extracts the data for each performers by isolating them individually. It stores the output as a .csv file

Module_DyadicSynchronization:
This file contains the code that extracts the data from the .csv file processed by the first file (Module_DataExtraction), and provides the Dyadic Synchronization between all possible pairs in a musical ensemble.

Both the files have been shared as a jupyter notebook since this should make it easier to execute the code with more control.
The added control helps perform experiments carefully, particularly since the data from pose estimation algorithms can be noisy and sometimes requires manual intervention.

##### Author

Sanket Rajeev Sabharwal
UniGe, Casa Paganini
4709433
