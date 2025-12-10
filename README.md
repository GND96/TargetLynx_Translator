# TargetLynx_Translator

Python code for data wrangling of 13C stable isotope labelling data conducted on a Waters LC-MS and Waters TargetLynx software.

To generate the input .txt file navigate to your integrated MS data in TargetLynx. select File->Export->Complete Summary. A .txt file will be created, save locally.

To use this code ensure that you are able to run Python 3.12 or later on your machine. Download the  TargetLynx_Translator_v7.py and open it in your preferred code editor software. PIP Install the required packages (pandas,  re, openpyxl). Copy the file path for the input file in the string on line 75. Enter the desired file path for the output file at line 76. Run the code.

Terms used to exclude certain samples are listed as strings in line 36. Terms can be added or removed from this list as required.  

For queries contact dobsonge@msu.edu or georgedobson1996@gmail.com
