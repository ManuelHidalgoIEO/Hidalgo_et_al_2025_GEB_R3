# Hidalgo_et_al_2025_GEB_R3
R code, data set and readme document associated the manuscript submitted to journal Global Ecology and Biogeography

Readme

The code file (“PE_code_for_GEB.R”) is divided into four separate steps in order to perform the data preparation and the subsequent analyses:
•
The first step of the code works on the raw data on annual abundance by species and survey in order to extract PE metrics, z-value, and mean values for total abundance and taxonomic diversity. This code cannot be executed because time series are not freely available as explained in the text.
•
The second step of the code works on the ecosystem-level pairwise relationships and can be run in full. The data set is the one generated in the first step (“portfolioDataForGEB.txt”).
•
The third step of the code is focused on fitting the linear mixed-effects models (LMEs) to the time series data of total abundance by year and survey. This code cannot be executed because time series are not freely available as explained in the text.
•
The fourth step of the code deals with the structural equation models (SEMs) at the ecosystem-level data and can be run in full. The data set is the one generated in the first step (“portfolioDataForGEB.txt”).
The file “portfolioDataForGEB.txt” contains the following data:
Map: correspondence with ecosystem number in Figure 1
System: ecosystem name in Figure 1
plotOrd: ecosystem ID for ordering in Figure S7
Region: region name
Latitude: mean latitude
Longitude: mean longitude
K: mean CWM_k
L50: mean CWM_L50
TL: mean CWM_TL
Depth: mean depth
DepthCV: depth CV
Chla: mean Chla
ChlaCV: Chla CV
SBT: mean SBT
SBTrange: range of SBT
TAI: Total Anthropogenic Impact
Trawl: Bottom Trawling
cpue: mean total abundance
cpueSD: standard deviation of total abundance
richness: mean richness
shannon: mean Shannon diversity
evenness: mean evenness
z.value: Taylor’s Power law z-value
z.value.l: low for z-value
z.value.u: upper for z-value
synchrony: synchrony
avcvpe: CVPE
avcvpe.l: low for CVPE
avcvpe.u: upper for CVPE
mvpe: MVPE
mvpe.l: low for MVPE
mvpe.u: upper for MVPE
