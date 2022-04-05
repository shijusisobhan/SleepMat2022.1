# SleepMat2022.1

Here we introduce *SleepMat* (sleep analysis software based on MATLAB) software implemented entirely in MATLAB with a user-friendly graphical user interface (GUI) to analyze *Drosophila* activity monitoring data. It is straightforward to use and can calculate more than 25 sleep and circadian parameters within a short time, which will reduce the user time and effort considerably. In this repository, we provide A) A standalone application, which doesn't require Matalab installed on the system. B) A p-code that can run SleepMat in MATLAB, which requires a MATLAB license.

## Installation procedure of satndalone application

-You need internet connection at the time of installation. Once you installed, it will work even in the absence of internet.

### Windows
1. Download the *SleepMat_standalone_app_Windows.exe* file
2. Extract the files
3. Doubble click on the *SleepMat_standalone_app_Windows.exe* file.
4. Please check the box for creating the shortcut to the Desktop.
5. Depending on your machine and internet connection it will take 5-10 min to complete the installation. By deafault SleepMat installed in the 'C:\Program Files' folder
6. To run the *SleepMat*, doubble click on the *SleepMat* icon on the desktop

### Mac
1. Download the *SleepMat_satndalone_app_mac.app.zip* file
2. Extract the files
3. Doubble click on the *SleepMat_satndalone_app_mac* file. Select an appropriate folder for installing the application. Depending on your machine and internet connection it will take 5-10 min to complete the installation.

Note: Normally mac don't provide the permission to install the application. You can grant an exception for a blocked app by clicking the Open Anyway button in the General pane of Security & Privacy preferences OR by using any other system settings.

5. Go to installed folder and create a shortcut to desktop for 'SleepMat' icon.
6. To run the *SleepMat*, doubble click on the sleepmat icon on the desk top.


## Steps to run SleepMat in MATLAB 
1.	Open MATLAB
2.	Change the current folder to the new folder where SleepMat software is located. 
E.g., If SleepMat software is saved in the 'D' drive, then to change the current folder, type the following line in the MATLAB command window:

cd D:\sleepmat_Windows_V2022.1

3.	To open the software, type ‘sleepmat’ in the MATLAB command window, then hit enter.

## Errors and troubleshooting

| Error message | Possible reason |
| --------------------------- |
|ERROR! Please enter valid dates (See monitor file and genotype specification file) | Date format in the genotype specification file does not match with Monitor file
Date entered in the GT file is not present in the Monitor file |





