# EX - 03 Install-Autopsy-and-Analyze-the-Disk-File-and-Folder-Configuration
## NAME: AANKARSH J
## REG NO: 212223233001
## AIM:
To install Autopsy on Kali Linux and analyze disk images, files, and folder configurations for digital forensic purposes.

## DESIGN STEPS:
### Step 1:
Install Autopsy using the terminal with the command:

### Step 2:
Launch Autopsy from the terminal or application menu and create a new case.

### Step 3:
Add a disk image or file to the case and analyze the contents such as deleted files, metadata, and folder structure.

## PROGRAM:
Autopsy Installation and Analysis Steps
## INSTALLATION PROCEDURE:
### Step1:Download Autopsy
  •	Visit Autopsy Official Website and download the latest version.
  <br>
  •	Double-click the downloaded file and follow the on-screen instructions.
  <br>
  ![image](https://github.com/Aankarsh/Install-Autopsy-and-Analyze-the-Disk-File-and-Folder-Configuration/blob/main/autopsy-download.png)

### Step2:Installation Process<br>
  •	Launch Autopsy if it correctly works. 
  ![image](https://github.com/Aankarsh/Install-Autopsy-and-Analyze-the-Disk-File-and-Folder-Configuration/blob/main/install-process.png)

    <br>
  •	Successfully installed & Autopsy Interface<br>
  ![image](https://github.com/Aankarsh/Install-Autopsy-and-Analyze-the-Disk-File-and-Folder-Configuration/blob/main/installed.png)

  
## CREATING A DISK PARTITION:
### Step1: Open File Manager
  ●	Right-click This PC → Click Show More Options.<br>
  ●	Select Manage.<br>
![image](https://github.com/Aankarsh/Install-Autopsy-and-Analyze-the-Disk-File-and-Folder-Configuration/blob/main/open%20file%20manager.png)
<br>
### Step2: Access Disk Management<br>
  ●	In the new window, select Disk Management.<br>
  ![image](https://github.com/Aankarsh/Install-Autopsy-and-Analyze-the-Disk-File-and-Folder-Configuration/blob/main/step%202.png)

### Step3: Shrink the C Drive to Allocate Space<br>
  •	Locate C: drive → Right-click → Select Shrink Volume.<br>
  •	Enter the amount of memory to allocate for the new disk.<br>
  •	Click Shrink.<br>
  ![image](https://github.com/Aankarsh/Install-Autopsy-and-Analyze-the-Disk-File-and-Folder-Configuration/blob/main/step3.png)
<br>
### Step4: Create a New Volume
  •	Right-click on the newly unallocated space → Select New Simple Volume.<br>
  ![image](https://github.com/user-attachments/assets/41558cda-0e2b-4fcb-87f8-3cb63162fd24)
<br>
  •	Follow the wizard and assign a disk name<br>
  •	Click Finish to complete the process.<br>
  •	The new Disk Partition is created<br>
![image](https://github.com/Aankarsh/Install-Autopsy-and-Analyze-the-Disk-File-and-Folder-Configuration/blob/main/disk%20partition.png)

## ADDING FILES:
### Step1: Copy Files to the Partition:
  •	Open File Explorer → Navigate to the newly created drive (C: or D:).

  •	Transfer images or files into it.
  ![image](https://github.com/Aankarsh/Install-Autopsy-and-Analyze-the-Disk-File-and-Folder-Configuration/blob/main/file%20copied.png)

## OUTPUT:ANALYSING FILES USING AUTOPSY:

### Step1: Create a Case
  •	Enter a case name and select a location to store the case data.
  
   ![image]((https://github.com/Aankarsh/Install-Autopsy-and-Analyze-the-Disk-File-and-Folder-Configuration/blob/main/create%20case.png))
  •	Provide a case number and investigator details if required.

### Step2: Add a Data Source
  •	Click "Add Data Source" and choose the type:
  •	Select the data source and let Autopsy process it.
### Step3: File Analysis
  •	Application
  
  ![image](https://github.com/Aankarsh/Install-Autopsy-and-Analyze-the-Disk-File-and-Folder-Configuration/blob/main/file%20analysis.png)

  •	File Metadata
  
  ![image](https://github.com/Aankarsh/Install-Autopsy-and-Analyze-the-Disk-File-and-Folder-Configuration/blob/main/file%20metadata.png)

  •	Click OS Account.
  
  ![image](https://github.com/Aankarsh/Install-Autopsy-and-Analyze-the-Disk-File-and-Folder-Configuration/blob/main/os%20account.png)

  •	Generate Report
  
  ![image](https://github.com/Aankarsh/Install-Autopsy-and-Analyze-the-Disk-File-and-Folder-Configuration/blob/main/analyse%20report.jpeg)


## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
