# Install-Autopsy-and-Analyze-the-Disk-File-and-Folder-Configuration
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
### **Install Autopsy for Windows (GUI-based Forensic Tool)**
🔗 **Download Autopsy**: [Click Here](https://www.autopsy.com/download/)  
1. Download the **Autopsy Windows Installer** from the official website.  
2. Extract the ZIP file and open the **bin** folder.  
3. Run `autopsy.exe` and set up a new forensic case for analysis.

### **Install Autopsy for Linux**
1. Open Terminal.
2. Update your package list: sudo apt update
3. Install Autopsy: sudo apt install autopsy
4. Launch Autopsy using: autopsy
5. Open http://localhost:9999/autopsy in a web browser.

### **Create & Configure a Virtual Hard Disk (VHD) in Windows**

1. Press **Win + X**, Select Disk Management.
2. Click Action > Create **VHD**.
3. Choose a location and set a disk size (e.g., 10GB+).
4. Select Fixed Size or Dynamically Expanding and click OK.
5. In Disk Management, find your new disk (marked as "Not Initialized") -> Right-click the new disk → Initialize Disk → Select **MBR**.
6. Right-click Unallocated Space → **New Simple Volume** → Format the disk -> Click next → Finish.

## OUTPUT:
### Autopsy for Windows

![image](https://github.com/user-attachments/assets/48b911c3-1e0c-4c7c-ac34-7aa61f4a5f73)

### Autopsy for kali linux

!![image](https://github.com/user-attachments/assets/17f1daf9-af15-4f84-809f-14e29c3b08ed)

### Analysing the disk file and configuration:

![image](https://github.com/user-attachments/assets/9c8f31c8-3242-4318-a98f-b09088d4f762)

![image](https://github.com/user-attachments/assets/3655a10b-93cb-4479-962a-2e9066f63bee)

### Timeline:

![image](https://github.com/user-attachments/assets/8ac62916-477f-4630-9de9-ebe508d34fac)

### Data Source Summary Report:


![image](https://github.com/user-attachments/assets/320f4bbc-51bc-4ab0-994d-37e4ad035e54)

### RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
