# ScEnSor-Kit-Script

_NOTE._ This script was used to analyse data coming from the BioLector I. Example of the script output can be found in "Script_Output" folder or in the following publication: 

Getting started:

1. Install RMarkdown in R. No need of pre-installing the packages needed as they will be installed automatically if not already.
2. Check the data organisation in the example file (Data_Example_Analysis.xlsx) provided here.
3. Re-arrange the excel file. In a sheet called "analysis", transfer the BioLector I raw data. Here, the first column (called "well") should contain the name of the wells (A1, A2, etc.), the second one (called "channel") the channels used in the screening (up to 6) and then one column for each timepoint. In a sheet named "layout", assign the variables associated to each well (strain, biosensor, medium, etc.).
4. Download the script and place it in the same folder of the file to be analysed. The excel file name should end with "Analysis" and should be a .xlsx file. Changes in the script can be made to import other file formats.
5. Open the script and follow the directions. 
6. Make changes upon need (replace grouping variables, dimentions of images, etc.).

----
Luca Torello Pianale, lucat@chalmers.se, Industrial Biotechnology Division, Chalmers University of technology

Created: December, 2022.

The scripts were tested with: R Version 4.1.2 (2021-11-01) - RStudio (2021.09.2 Build 382)  

Acknowledgment of support: This material is based upon work supported by the Novo Nordisk Foundation grant DISTINGUISHED INVESTIGATOR 2019 - Research within biotechnology-based synthesis & production (#0055044). Société Industrielle Lesaffre, Division Leaf, is kindly acknowledged for providing the Ethanol Red strain.
