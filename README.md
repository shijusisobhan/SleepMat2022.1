
# SleepMat version 2022.2 is updated - Now version name is SleepMat2025.1 (9/26/2025)

Here we introduce *SleepMat* (sleep analysis software based on MATLAB) software implemented entirely in MATLAB with a user-friendly graphical user interface (GUI) to analyze *Drosophila* activity monitoring data. [Here you can find the publication.](https://academic.oup.com/sleep/advance-article/doi/10.1093/sleep/zsac195/6674229?searchresult=1)
It is straightforward to use and can calculate more than 25 sleep and circadian parameters within a short time, which will reduce the user time and effort considerably. In this repository, we provide A) A standalone application, which doesn't require Matalab installed on the system. B) A p-code that can run SleepMat in MATLAB, which requires a MATLAB license.

### Steps to run SleepMat in MATLAB
1.	Download the file _SleepMat_Require_Matlab.zip_
	
2.	Extract the file (_sleepmat.p_)

3.	Open Matlab.
   
4.	Change the current folder to the new folder where _sleepmat.p_ file is located. E.g., If _sleepmat.p_ file is saved in the 'D' drive, in a folder _SleepMat_Require_Matlab_ then to change the current folder, type the following line in the MATLAB command window:
   
	_cd D:\SleepMat_Require_Matlab_

5.	To open the software, type _sleepmat_ in the MATLAB command window, then hit enter.

   ### SleepMat standalone app installation on Windows

1.	Download the _SleepMat_standalone_app_Windows.exe_ file
   
2.	Double click on the _SleepMat_standalone_app_Windows.exe_ file.
	
3.	Please check the box for creating the shortcut to the Desktop.
   
4.	Depending on your machine and internet connection it will take 5-10 min to complete the installation. By default, SleepMat installed in the 'C:\Program Files' folder
   
5.	To run the SleepMat, double click on the _SleepMat_ icon on the desktop

### SleepMat standalone app installation on Mac (Coming soon...)

1.	Download the _SleepMat_standalone_app_Mac.app.zip_ file
   
2.	Extract the file
   
3.	Double click on the extracted file
   
4.	Follow the instruction on the pop up windows.
   
5.	Depending on your machine and internet connection it will take 5-10 min to complete the installation.
    
6.	To run the SleepMat, double click on the SleepMat icon

### New in 2025.1 (9/26/2025)

  ### Fixes & Improvements

1. Sleep Parameter Analysis Error

Issue: 30-minute intervals with more than 30 channels per board caused errors.

Fix: The update now properly calculates sleep parameters for intervals with >30 channels per board. Results have been validated.

2. Invalid Date Error with Missing Values & Single-Digit Day Format

Issue: Invalid date errors occurred when missing values were present and when using single-digit day formats (e.g., 3 Aug 24).

Fix: SleepMat now supports both 03 Aug 24 and 3 Aug 24, with or without missing values.

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
Please check for latest version and updates: [here](https://github.com/shijusisobhan/SleepMat2024.1/tree/main)
Any queries, please contact: shijusisobhan@gmail.com








