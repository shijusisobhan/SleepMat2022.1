
# SleepMat version 2022.2 [(A newer versionis available here)](https://github.com/shijusisobhan/SleepMat2024.1/tree/main)

Here we introduce *SleepMat* (sleep analysis software based on MATLAB) software implemented entirely in MATLAB with a user-friendly graphical user interface (GUI) to analyze *Drosophila* activity monitoring data. [Here you can find the publication.](https://academic.oup.com/sleep/advance-article/doi/10.1093/sleep/zsac195/6674229?searchresult=1)
It is straightforward to use and can calculate more than 25 sleep and circadian parameters within a short time, which will reduce the user time and effort considerably. In this repository, we provide A) A standalone application, which doesn't require Matalab installed on the system. B) A p-code that can run SleepMat in MATLAB, which requires a MATLAB license.

## Installation procedure of satndalone application

-Please read the user guide for the installation procedure. You need internet connection at the time of installation. Once you installed, it will work even in the absence of internet.

## Steps to run SleepMat in MATLAB 
1.	Open MATLAB
2.	Change the current folder to the new folder where SleepMat software is located. 
E.g., If SleepMat software is saved in the 'D' drive, then to change the current folder, type the following line in the MATLAB command window:

cd D:\sleepmat_Windows_V2022.2

3.	To open the software, type ‘sleepmat’ in the MATLAB command window, then hit enter.

## Errors and troubleshooting

| Error message | Possible reason |
| ------------- | ------------ |
|ERROR! Please enter valid dates (See monitor file and genotype specification file) | 1) Date format in the genotype specification file does not match with Monitor file 2) Date entered in the GT file is not present in the Monitor file |
|ERROR! start day of sleep or Number of days of sleep analysis is out of range| 1)The start day exceed the number of days of data present in the data file. 2)Number of days of analysis extend past the end of the data available|
|Error! check sleep deprivation entries|Combination of SD day, SD starting time, SD duration exceed the number of days of data present in the data file|
|ERROR! starting day or number of days of eduction/anticipation is out of range|1)The start day exceed the number of days of data present in the data file 2)Number of days of anticipation extend past the end of the data available|
|Error! start day OR number of days of periodogram is out of range|1.The start day exceed the number of days of data present in the data file 2)Number of days of anticipation extend past the end of the data available|
|'Error ! check triage date'|1)Triage date entered in the GT file is not in the correct format 2)Triage date is not present in the data available|
|Unknown Error! Please check the input(eg: genotype specification file, days...)| 1)GT file format is not correct (eg: columns are interchanged) 2)Monitor files are not available  3)Input are not in the reasonable range  4) start time (light ON time) is not available in the monitor file  5) problem with name of the genotype used in the genotype specification file (don't use >, <, \, /, :, ?, ",for genotype naming or project naming) 6) Other unknown errors (Missing toolbox when running on MATLAB)|


## Updates
SleepMat has been updated. SleepMat2024.1 version of the software can be found here.[here](https://github.com/shijusisobhan/SleepMat2024.1/tree/main)








