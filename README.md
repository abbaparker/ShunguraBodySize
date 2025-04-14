# Data and code for analyses of body size changes across the Shungura Formation

This repository includes code for correlation analysis and figure plotting for the manuscript titled "Body size histories of Shungura Formation reptiles in biotic and abiotic environmental context"

# Data
ShunguraBodySize_Delta includes all data series analyzed across the 12 members of the Shungura Formation. Summary of the columns of data:
For reptiles, columns with the name of the group followed by Mass (e.g. PelomedusidMass) are the masses reported in the supplementary tables for the largest specimen from each member. Columns with Log_Delta (e.g. LogTestudinid_Delta) are the first differences or change between members in log10 values of each maximum size series. 
Next are specimen counts identified to each group by member, then all of the paleoenvironmental proxy time series derived from sources cited in the text. Each of these also has a _Delta series of its first differences. 
Next, maximum body size series for mammals. Hippos_protkaru are the Hippopotamus protamphibius/karumensis lineages, Hippos_aethi are Hippopotamus aethiopicus, and Hippopotamus is Hippopotmaus sp. (see text). The other mammal groups' mass estimates come from Bibi (2023)'s measurements and regressions in Bibi and Cantalapiedra (2023).
Finally, series for soil temperature estimates from Passey et al. (2010), precipitation estimates from Hernández Fernández & Vrba (2006), abbreviated HFprecip, and depositional environment scores from Heinzelin (1983); for these, HeinzelinEnv is the average score for the units in each member, while HeinzelinMaxLake is the maximum score (see text for scoring scheme).   

ShunguraBodySize_Figures includes the same data, but with further series used for plotting the figures. Notably, these are columns ending in Interpolated, which include interpolations of maximum size for members with missing data used only for plotting lines in the figures. 
This data sheet also includes higher-reslution data on lake level NutzLakeLevel, (from Nutz et al. 2020), accompanied by ages of each sample in the column LLAge. For paleosol isotope data, sample ages are in the LevinAge column, followed by the d18O and d13C values.  

# Code
All correlation tests carried out can be replicated using the ShunguraBodySize_Delta script. 
ShunguraBodySize_Figures includes code to plot versions and adaptations of the figures in the manuscript. 

