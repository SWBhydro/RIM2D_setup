# Code for pre- and postprocessing of data for/from the RIM2D model
#### By Siep W. Bakker 
#### Contributions made by: dr. J. de Bruijn and T. Busker

##### DEM preparation
DEM_pre_processing_AHN -> Merging Dutch DEM tiles\
DEM_pre_processing_DTM -> Merging German DEM tiles\
DEM_pre_processing_NL_Ger_Flan_Wal -> Merging the DEMs form three countries (Flanders and Wallonie for Belgium). DEMs are referenced to the Dutch DEM's elevation.\
The final preparation of the merged DEM to be used in the RIM2D model is done in 1.Static_input_maps\

##### Resampling input data 
1. Processing of the static input maps
2. Processing of the Dynamic (precipitation) input maps

##### Processing the data
3. Calculating statistics of the output data
