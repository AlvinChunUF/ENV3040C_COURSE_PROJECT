# ENV3040C COURSE PROJECT BY ALVIN CHUN (CLASS #11906) 
This is the repository containing all code used in my ENV3040C Course Project which examined the correlation
between dry bulk density of soil and soil organic carbon. Please do not re-use without permission, and if there
are any issues feel free to reach out at achun2@ufl.edu. 

**IMPORTANT**

This code was not meant to be used with any dataset other than "Maxwell_MarSOC_dataset.csv". This has been
hardcoded into the program and should not be modified. 

**CODE SUMMARY**

The code is separated into 5 main groups:
- *##LIBRARY LOADING ZONE##*: This section is for loading all of the libraries and analytical functions that
  will be used to perform all of the data analysis. NO OUTPUT IS EXPECTED FROM THIS SECTION.
- *##DATA FRAME GENERATION AND INITIAL VISUALIZATION##*: This section is for producing the inital dataframe to
  make the .csv file easier to approach and to use, along with removing extra variables that we do not need and
  removing data with NAN values. NO OUTPUT IS EXPECTED FROM THIS SECTION
- *##GROUND LEVEL ANALYSIS##*: These chunks are for performing ground level analysis like mean, median, and mode.
  Generally the title of the ground level header will indicate which analysis is being performed.AN OUTPUT IS
  EXPECTED IN THESE SECTIONS. 
- *##HISTOGRAM GENERATION##*: This portion is responsible for generating the histograms used in the text, including
  the side by side histograms of two of the relevant variables. AN OUTPUT IS EXPECTED IN THESE SECTIONS
- *##LINEAR REGRESSION AND OTHER TWO VARIABLE ANALYSIS##*: This portion is responsible for performing the spearman
  and pearson correlation calculations along with generating a scatterplot with linear regression. AN OUTPUT IS
  EXPECTED IN THIS SECTION.
- *##PCA ANALYSIS##*: This portion is responsible for performing the PCA analysis and generating the PCA graphs.
  AN OUTPUT IS EXPECTED IN THIS SECTION.
  
Individual code descriptions are housed within the code in each section.

**GITHUB DIRECTORY MAP - FILE LIST**
- COURSE PROJECT CODE.ipynb: This is the code for the project itself.
- Maxwell_MarSOC_data.csv: This is the data for the project

**CREDIT FOR ORIGINAL DATA SET GOES TO MAXWELL ET. AL** 
https://github.com/Tania-Maxwell/MarSOC-Dataset 
