# Sorting Annual Reports

## Project Overview
In this Sorting Annual Reports project, I've developed an automation for a process that sorts files in a given folder into subfolders based on the date in the file name.

This project involves navigating to a webpage and downloading a zip file to sort. Then moving the file to a particular folder depending upon the process requirement:

1. For each file in the folder that follows this naming convention “CustomerName_Report_DDMMYYYY.xlsx/.pdf”, The bot creates a folder named “YYYY”(Date format) depending on the last four characters of the file name, which denotes the year in the “YYYY”(date format). For example, if the file name is “Heba_Report_13072019.pdf” then creates a folder with the name “2019” and moves the file into this folder.
2. If any of the files don't follow the naming convention, then the bot creates a new folder with today’s date (format MMDDYYYY) and moves them there.

## Workflows Screenshots

### Main Workflow
<img src="git_screenshots/0_Main.jpg">

### Project_GlobalVariables Workflow
<img src="git_screenshots/2_Project_GlobalVariables.jpg">

### Generic_CreateFolderIfNotExists Workflow
<img src="git_screenshots/1_Generic_CreateFolderIfNotExists.jpg">

### Edge_ChangeDownloadsFolder Workflow
<img src="git_screenshots/3_Edge_ChangeDownloadsFolder.jpg">

### Github_DownloadRepo Workflow
<img src="git_screenshots/4_Github_DownloadRepo.jpg">

### ZipFile_Extract Workflow
<img src="git_screenshots/5_ZipFile_Extract.jpg">

### Generic_ListofAllFiles Workflow
<img src="git_screenshots/6_Generic_ListofAllFiles.jpg">

### Generic_SortFiles Workflow
<img src="git_screenshots/7_Generic_SortFiles.jpg">

## About The Author

* Author: Mohamed Abdel-Gawad Ibrahim
* Contact: muhammadabdelgawwad@gmail.com
* Phone: +201069052620 || +201147821232
