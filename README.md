PAPER TITLE: Behavioral and neural correlates of magnetic sensing in poison frogs

ABSTRACT: Diverse animals sense Earth’s magnetic field and exploit it as a cue during orientation and navigation, but the neural mechanisms underlying the detection and processing of magnetic cues remain poorly understood. Poison frogs perform complex navigational tasks related to territoriality and parental care and use multiple sensory cues to guide themselves through their environment. To explore whether the green-and-black poison frog (*Dendrobates auratus*) can orient using Earth’s magnetic field, we conducted behavioral experiments with frogs inside a magnetic coil system that allowed for manipulation of the ambient magnetic field. Under these conditions, frogs exhibited spontaneous magnetic alignment, in which they oriented approximately toward magnetic northwest or southeast in the absence of other sensory cues. Using immunohistochemistry for phosphorylated ribosomes (pS6) as a neural marker, we next investigated brain regions involved in the processing of magnetic cues. Relative to controls, frogs exposed to a slowly changing magnetic field displayed altered neural activity in two brain areas, the lateral pallium and habenula. These findings demonstrate that poison frogs can orient to Earth’s magnetic field, an ability that may facilitate navigation in their rainforest environment. In addition, poison frogs represent a promising new model system for investigating the neural mechanisms underlying magnetoreception.

PUBLICATION INFORMATION: <insert citation>

GENERAL INFORMATION

1. Title of Datasets:
   2024_08_27 Frog Orientation Data.csv
   2026_09_23 Obs Avg w Area.csv

3. Author Information
		Name: XXX
		Institution: Department of Biology, XXX
		Email: XXX 

4. Date of data collection: 2023-2024

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

R Version 2026.10.1+239 (2026.10.1+239)
Platform: 2 GHz Quad-Core Intel Core i5
Running under: Mac 26.6.2 (25G83)

attached base packages:
stats
graphics
grDevices
utils
datasets
methods
base     

other attached packages: 
RColorBrewer 1.1-3
circular 0.5-1
dplyr 1.1.4
tidyverse 2.0.0
CircMLE 0.3.0
CircStats 0.2-6
tidyr 1.3.1
ggplot2 3.5.1
ggpubr 0.6.0
rstatix 0.7.2
ggsignif 0.6.4
lme4 1.1-35.5
emmeans 1.10.5
glmmTMB 1.1.10
DHARMa 0.4.7
broom.mixed 0.2.9.6

loaded via a namespace (and not attached): N/A

DATA-SPECIFIC INFORMATION FOR: ******UPDATE

2024_08_27 Frog Orientation Data.csv
1. Number of variables: 6

2. Number of cases/rows: 48

3. Variable List: 
Subject: unique number for each tested animal
MF: indicates magnetic field treatment
Avg_Angle: indicates the average angle of orientation across 10 trials for each animal
Norm_Avg_Angle: the average angle of orientation normalized to magnetic north to account for MF treatment
Bimodal_Norm_Avg_Angle: to test for bimodal magnetic alignment, mean orientation angles (Norm_Avg_Angle) were doubled and values greater than 360 were reduced by subtracting 360 
r.value:

5. Missing data codes: NA
