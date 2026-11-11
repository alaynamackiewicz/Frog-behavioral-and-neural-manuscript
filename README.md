PAPER TITLE: Behavioral and neural correlates of magnetic sensing in poison frogs

ABSTRACT: Diverse animals sense Earth’s magnetic field and exploit it as a cue during orientation and navigation, but the neural mechanisms underlying the detection and processing of magnetic cues remain poorly understood. Poison frogs perform complex navigational tasks related to territoriality and parental care and use multiple sensory cues to guide themselves through their environment. To explore whether the green-and-black poison frog (Dendrobates auratus) can orient using Earth’s magnetic field, we conducted behavioral experiments with frogs inside a magnetic coil system that allowed for manipulation of the ambient magnetic field. Under these conditions, frogs exhibited spontaneous magnetic alignment, in which they oriented approximately toward magnetic northwest or southeast in the absence of other sensory cues. Using immunohistochemistry for phosphorylated ribosomes (pS6) as a neural marker, we next investigated brain regions involved in the processing of magnetic cues. Relative to controls, frogs exposed to a slowly changing magnetic field displayed altered neural activity in two brain areas, the lateral pallium and habenula. These findings demonstrate that poison frogs can orient to Earth’s magnetic field, an ability that may facilitate navigation in their rainforest environment. In addition, poison frogs represent a promising new model system for investigating the neural mechanisms underlying magnetoreception.

PUBLICATION INFORMATION: <insert citation>

GENERAL INFORMATION

1. Title of Datasets:
   2024_08_27 Frog Orientation Data.csv
   2026_09_23 Obs Avg w Area.csv

3. Author Information
		Name: XXX
		Institution: Department of Biology, XXX
		Email: XXX 

4. Date of data collection: 2023

5. Geographic location of data collection: XXX  

6. Information about funding sources that supported the collection of the data: Funding was provided by XXX
   
7. License information: N/A

8. DOI for data and code repository: 10.1098/rspb.2026.2016


DATA & FILE OVERVIEW

1. File List: 

Data
2024_08_27 Frog Orientation Data.csv: csv file containing orientation data for each tested animal
2026_09_23 Obs Avg w Area.csv: csv file containing raw neural count data for each brain region

Code
2026_10_07 Frog Paper Code.Rmd: R markdown file containing statistical code used to analyze behavioral and neural data (including figure preparation)

2. Relationship between files, if important: N/A

3. Additional related data collected that was not included in the current data package: N/A

4. Are there multiple versions of the dataset? No

METHODOLOGICAL INFORMATION

1. Description of methods used for collection/generation of data: 
XXXX


2. Methods for processing the data: 
Data were analyzed using the 2026_10_07 Frog Paper Code.Rmd R code.

3. Instrument- or software-specific information (including package versions) needed to interpret the data: 

Version 2026.10.1+239 (2026.10.1+239)
Platform: 
Running under:

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages: thanks ******UPDATE
 [1] performance_0.15.0 emmeans_1.10.4     modelbased_0.8.8   glue_1.8.0         gtsummary_2.3.0    data.table_1.16.2  lubridate_1.9.3   
 [8] forcats_1.0.0      stringr_1.5.1      dplyr_1.1.4        purrr_1.0.2        readr_2.1.5        tidyr_1.3.1        tibble_3.2.1      
[15] ggplot2_3.5.2      tidyverse_2.0.0    ggthemes_5.1.0     lmerTest_3.1-3     lme4_1.1-35.5      Matrix_1.7-1      

loaded via a namespace (and not attached): N/A

DATA-SPECIFIC INFORMATION FOR: ******UPDATE

sim_data.csv
1. Number of variables: 4

2. Number of cases/rows: 120

3. Variable List: 
animal_id: Unique identity of the tested animal
population: indicates whether the anial came from population A or B
trial: indicates the behavioural trial that the data were recorded for (1 - 4)
distance_moved: how far the animal moved in metres

4. Missing data codes: NA
