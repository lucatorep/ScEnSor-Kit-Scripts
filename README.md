# ScEnSor-Kit-Script

_NOTE._ This script has been developed for the following publication: https://pubs.acs.org/doi/full/10.1021/acssynbio.3c00124
The script analyses data coming from the BioLector I. Example of the script output can be found in "Script_Output" folder or in the above-mentioned publication.  
Script available also in the "ScEnSor-Kit_Biolector_Analysis_Markdown.pdf" file (with figures embedded in the code).

Getting started:

1. Install RMarkdown in RStudio. No need of pre-installing the other packages needed for the script as they will be installed automatically (if they are not already).
2. Check the data organisation in the example file provided in the Script+Data folder (Data_Example_Analysis.xlsx). 
3. Re-arrange your excel file. Briefly, in a sheet called "analysis", transfer the BioLector I raw data. Here, the first column (called "well") should contain the name of the wells (A1, A2, etc.), the second one (called "channel") should contain the channels used in the screening (up to 6) and then one column for each timepoint. In a sheet named "layout", assign the variables associated to each well (strain, biosensor, medium, etc.).
4. Download the script and place it in the same folder of the file to be analysed. The excel file name should end with "Analysis" and should be a .xlsx file. Changes in the script can be made to import other file formats.
5. Open the script and follow the directions. Make changes upon need (replace grouping variables, fluorescence analysis, dimentions of images, etc.).

----
Luca Torello Pianale, lucat@chalmers.se, Industrial Biotechnology Division, Chalmers University of technology

Created: January, 2023.

The scripts were tested with: R Version 4.1.2 (2021-11-01) - RStudio (2021.09.2 Build 382)  

Acknowledgment of support: This material is based upon work supported by the Novo Nordisk Foundation grant DISTINGUISHED INVESTIGATOR 2019 - Research within biotechnology-based synthesis & production (#0055044). 
