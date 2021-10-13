# Leak-Data-Simulations-with-Measurement-and-Demand-Uncertainties

 The simulated leak datasets used for the project "A Leak Zone Location Approach in Water Distribution
Networks Combining Data-Driven and Model-Based Methods" are presented in the .dst files in this repository. 
These dataset files were generated using Python v3.8.5..
  The 5 files with the name format: 'TestDataset_DemandUncert_XX.dst' are the 5 test datasets used
to test the proposed methodology; where 'XX' is the corresponding demand uncertainty percentage.
  The 1 file with the name format: 'TrainDataset_DemandUncert_10.dst' is the dataset used to train
the SVM multiclass classifier.
  All dataset files (*.dst) contain a pickled SimulationDataset object which summarizes the 
data samples and simulation conditions. SimulationDataset class is defined in 
'SimulationDataset.py'.
  A simple example of how to load a dataset file and access some of its attributes is presented in
'Script_LoadDataset.py'.   
