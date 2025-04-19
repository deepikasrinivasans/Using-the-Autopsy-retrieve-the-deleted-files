# Using-the-Autopsy-retrieve-the-deleted-files
### Name " Deepika S
### Reg No: 212222230028
## AIM:
To use Autopsy in Kali Linux to retrieve and analyze deleted files from a disk image.

## DESIGN STEPS:
### Step 1:
Open Autopsy and create a new case with appropriate case details.

### Step 2:
Add a disk image as a data source and let Autopsy analyze the content.

### Step 3:
Navigate to the "Deleted Files" section in Autopsy and examine or recover the deleted files.

## PROGRAM:
### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`C: or D:`), where the folder created in the New Virtual Disk
- Create a new folder (`Autospy`) and copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.  

![dfdi1](https://github.com/user-attachments/assets/f654bd06-10fe-4f99-940b-8de796ed8024)

- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

![Uploading dfdi2.png…]()


### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**


![Uploading dfdi3.png…]()

- Select **Local Disk** → **next** 


![Uploading dfdi4.png…]()

- Select Disk → **Choose the VHD drive (`Drive1`)**

![Uploading dfdi5.png…]()


- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  



![a6](https://github.com/user-attachments/assets/f7063263-697f-485f-ad92-ccb0e8a17552)


- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  



- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.
![dfdi6](https://github.com/user-attachments/assets/de8d34bb-c084-4137-8039-dca5622ad450)


## Output :
### Folder before deleting the files
![dfdi11](https://github.com/user-attachments/assets/a9440e46-eb53-4703-b6f4-34850a76e0b6)


### Folder after deleting the files
![dfdi22](https://github.com/user-attachments/assets/de92c23d-a553-4b30-a2a2-1220bf162090)


### Folder after extracting the deleted images using autopsy
![dfdi33](https://github.com/user-attachments/assets/e5a9a119-01d1-4d51-924c-abaf8f1fdee5)

## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
github
