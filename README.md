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
  ![image]([https://github.com/Aankarsh/Install-Autopsy-and-Analyze-the-Disk-File-and-Folder-Configuration/blob/main/autopsy-download.png)

### Step2:Installation Process<br>
  •	Launch Autopsy if it correctly works. 
  ![image](https://github.com/user-attachments/assets/f0fb93a5-ae0e-4adc-943d-b904cd5a817d)

    <br>
  •	Successfully installed & Autopsy Interface<br>
  ![image](https://github.com/user-attachments/assets/84f04f68-a876-40a1-afee-d64dce4f0e53)

  
## CREATING A DISK PARTITION:
### Step1: Open File Manager
  ●	Right-click This PC → Click Show More Options.<br>
  ●	Select Manage.<br>
![image](https://github.com/user-attachments/assets/74032702-8933-4eef-a681-6dac708a2452)
<br>
### Step2: Access Disk Management<br>
  ●	In the new window, select Disk Management.<br>
  ![image](https://github.com/user-attachments/assets/d0522213-d3fb-4a45-bb79-bb8c4bb4f4c9)

### Step3: Shrink the C Drive to Allocate Space<br>
  •	Locate C: drive → Right-click → Select Shrink Volume.<br>
  •	Enter the amount of memory to allocate for the new disk.<br>
  •	Click Shrink.<br>
  ![image](https://github.com/user-attachments/assets/1b92460f-3b9b-4abb-b794-bd48b9f90a9f)
<br>
### Step4: Create a New Volume
  •	Right-click on the newly unallocated space → Select New Simple Volume.<br>
  ![image](https://github.com/user-attachments/assets/41558cda-0e2b-4fcb-87f8-3cb63162fd24)
<br>
  •	Follow the wizard and assign a disk name<br>
  •	Click Finish to complete the process.<br>
  •	The new Disk Partition is created<br>
![image](https://github.com/user-attachments/assets/1cf2a252-b34d-4100-8253-b1736cac479d)

## ADDING FILES:
### Step1: Copy Files to the Partition:
  •	Open File Explorer → Navigate to the newly created drive (C: or D:).

  •	Transfer images or files into it.
  ![image](https://github.com/user-attachments/assets/a0142b7a-366d-47dc-9d34-6290e0bee579)

## OUTPUT:ANALYSING FILES USING AUTOPSY:

### Step1: Create a Case
  •	Enter a case name and select a location to store the case data.
  
   ![image](https://github.com/user-attachments/assets/bc808727-106c-4214-8f91-7ae555fb8636)
  •	Provide a case number and investigator details if required.

### Step2: Add a Data Source
  •	Click "Add Data Source" and choose the type:
  •	Select the data source and let Autopsy process it.
### Step3: File Analysis
  •	Application
  
  ![image](https://github.com/user-attachments/assets/bda92cad-9f47-4a7c-97f6-05910c373fe0)

  •	File Metadata
  
  ![image](https://github.com/user-attachments/assets/0450bf95-28a5-44be-b875-016216e62136)

  •	Click OS Account.
  
  ![image](https://github.com/user-attachments/assets/63a21fd6-4ea2-408a-ac70-d6a0274e702b)

  •	Generate Report
  
  ![image](https://github.com/user-attachments/assets/5a82b31d-3f4f-49dd-9b23-4872df3ab8a9)


## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
