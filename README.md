# BrainStation-Capstone Project - Investigation of Various Factors Influencing the Crop Yield Globally
**By Ali Sehpar Shikoh**

This was my capstone project that was submitted for BrainStation's Data Science Diploma.

Food security is profoundly important for human beings all over the world. Generally, food security is predominantly studied under various climate change scenarios.  It is required to integrate various other variables for the evaluation of food security in a complete and systematic fashion. The main aim of this project was to determine the influence of various parameters in the determination of crop yield (i.e. the target variable).

The project follow the following sequence:

1) Clean the raw data, perform basic EDA and export the refined version to a CSV file.
2) Combine various refined datafiles into a single dataset, perform additional EDA and export the combined version to a CSV file.
3) Preprocess the data, implement various models, evaluate and later interpret the fitted models.


## Directories
All the project related files are organized in two main folders as seen below:

* _01 DataAndWorkingFiles/_  - Contains all the notebooks and data files.
    * _DataFiles/_  - Contains all the raw and refined data files in CSV format.
* _02 Report/_  - Contains the report for the capstone project.


## Notebooks
There a total of 13 notebooks in this project and can be divided into two sections i.e.: 

#### Raw data processing notebooks:
* 01-AtmosphericDeposition-RAW.ipynb
* 02-BiologicalFixation-RAW.ipynb
* 03-CropRemoval-RAW.ipynb
* 04-Crops-RAW.ipynb
* 05-FertilizerUse-RAW.ipynb
* 06-Livestock-RAW.ipynb
* 07-ManureApplied-RAW.ipynb
* 08-Population-RAW.ipynb
* 09-RoundwoodProduction-RAW.ipynb
* 10-TemperatureChange-RAW.ipynb

#### Post-processing notebooks
* 11-CombiningDataSets-AdditionalEDA.ipynb - Deals with the combining of various refined datasets mentioned above and performing additional EDA.
* 12-DataModelling.ipynb - Deals with the fitting of various models onto the combined dataset and interpreting the results obtained.
* 13-KeyFindings.ipynb - Mentions key findings gathered throughout the course of this project.

