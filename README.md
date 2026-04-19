# Installation-Guide-of-Battery-Notificator
This is a beginner-friendly Installation guide for the Battery Notificator.

**Project Name:** Battery Notificator  
**Repository:** https://github.com/Python-World/python-mini-projects/tree/master/projects/Battery_notification  
**Credits:** All source code credits go to the original author.   
**What it does:** This script monitors the system’s battery percentage and sends notifications when the battery is below 30%.

## Pre-requisites:  
### Python Installation  
Make sure Python is installed on your Windows machine. Link to download Python https://www.python.org/downloads/   
### Python packages: 
-**I)psutil:** It monitors CPU and memory usage. It can track disk and network statistics.  
*Installation:* To install this package, run this command on your terminal or command prompt:`pip install psutil`  

-**II) pynotifier:** This Python package is used to send desktop notifications. With the help of this package, programs will be able to provide the facility of showing pop-up alerts on the system.  
*Installation:* To install this package, run this command: `pip install pynotifier`  
To check if it is already installed on your machine or in your environment, run this command: `pip show pynotifier`  

-**III) win10toast:** This package is for showing the Windows desktop notifications.  
-*pynotifier:*  for cross-platform support  
-*win10toast:* specifically for Windows.  
This project includes both as dependencies, so it is recommended to install both.  
*Installation*: To install this package, run this command:  
`pip install win10toast`
OR
`python -m pip install win10toast`
OR
`pip3 install win10toast`

## Running the Script
To run the script, use this command: `python battery.py` 
Once executed, the script will run in the background to monitor the battery levels of the device. If the battery level is less than 30%, then it will notify you every 5 seconds.

## Troubleshooting common issues:
1.	pip is not recognised: run this command
`py -m pip install psutil` [It is the reliable method of installing the psutil package. Here, the Python interpreter is used, and [-m pip] tells Python to run the pip module.]
2.	If you have multiple Python versions installed, run this command:
`pip3 install psutil` [This command is for installing the package for Python 3.]

##  Uninstalling Packages and Stopping the Running Script  
**Stop running the script in the background:** To stop this script from running in the background, follow these steps:
-If running in the command prompt or terminal: Press Ctrl + C
-If you have run the file by double-clicking it, you can just close the window. 
-If you started running it in Visual Studio Code, then click the Stop button.   
To verify if it has stopped running in the background, open Task Manager and check the processes running. If it is still running, you can select it and choose the ‘End Task’ option.    

**To uninstall the packages: Run these commands in a terminal:**
`pip uninstall psutil`  
`pip uninstall pynotifier`  
`pip uninstall win10toast`  
You will be asked to confirm the action. Type y and press Enter to proceed with uninstalling the packages. 
*************************




