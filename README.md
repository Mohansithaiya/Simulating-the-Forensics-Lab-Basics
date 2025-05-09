# Simulating-the-Forensics-Lab-Basics

# Name: Mohan S
# Register Number: 212223240094

# AIM:

To install VirtualBox and set up a virtual machine(Kali Linux), install Autopsy and Sleuth Kit, and use them for forensic investigation by analyzing disk storage and file system.

# Implementation Steps :

# Step 1: 
Install VirtualBox

# Installation Steps:

1.Download the Windows hosts .exe file from the official VirtualBox website<br>

2.Run the installer and follow the on-screen instructions<br>

3.Once installed, launch VirtualBox to verify the installation.<br>

# Step 2:
Install Kali Linux on VirtualBox

# Installation Steps:

1.Download the Kali Linux ISO file.Open VirtualBox, click New, enter "Kali Linux", select Type: Linux and Version: Debian (64-bit)<br>

2.Set RAM to at least 4GB ,Set disk storage to at least 30GB, choose Dynamically Allocated or Fixed Size, and create the VM.<br>

3.Go to Settings > Storage, click Empty under Controller: IDE.<br>

4.Select Graphical Install, follow the prompts to set language, location, username, and password.<br>

5.Choose Partitioning Method (Guided - Use Entire Disk) and wait for installation to complete.<br>

# Step 3:
Install Autopsy (GUI-based Forensic Tool)

# Installation Steps:

1.Download the Autopsy Windows Installer from the official website.<br>
2.Extract the ZIP file and open the bin folder<br>
3.Run autopsy.exe and set up a new forensic case for analysis.<br>

# Step 4:
Install Sleuth Kit (CLI-based Forensic Tools)

# Installation Steps:

1.Download the Windows ZIP package from the official website.<br>

2.Extract the ZIP folder and move it to a suitable directory (e.g., C:\sleuthkit).<br>

3.Add the bin folder to Windows PATH:<br>
    *Open Control Panel → System → Advanced System Settings.<br>
    *Click Environment Variables → Edit Path.<br>
    *Add the Sleuth Kit bin folder path and save changes.<br>

4.Verify installation by running:<br>
```python
fls -version<br>
```    

# Step 5: Create & Configure a Virtual Hard Disk (VHD) in Windows

1. Press Win + X, Select Disk Management.<br>
2.Click Action > Create VHD.<br>
3.Choose a location and set a disk size (e.g., 10GB+).<br>
4.Select Fixed Size or Dynamically Expanding and click OK.<br>
5.In Disk Management, find your new disk (marked as "Not Initialized")   -> Right-click the new disk → Initialize Disk → Select MBR.<br>
6.Right-click Unallocated Space → New Simple Volume → Format the disk -> Click next → Finish.<br>

# Output:

# Virtual Box:

![alt text](<Screenshot 2025-03-28 083037.png>)

# Virtual Machine (Kali Linux):

![alt text](<Screenshot 2025-03-28 083037.png>)

# Autopsy:

![alt text](IMG-03.jpg)

# Sleuth Kit:

![alt text](<Screenshot 2025-03-28 083623.png>)

![alt text](IMG-02.jpg)

# Creation of Virtual Hard Disk:

![alt text](IMG-01.jpg)

# Result:

The installation of VirtualBox, Autopsy, and Sleuth Kit, along with the setup of Kali Linux - Virtual Machine and the creation of a new virtual disk, has been successfully completed.



