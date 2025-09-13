## name: n v mohana krishna
## reg : 212224100039
# FILE-RECOVERY-USING-AUTOPSY-SOFTWARE

## AIM
To use **Autopsy Digital Forensics Tool** to retrieve deleted files from a disk image.

---

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tool**: [Autopsy Digital Forensics](https://www.autopsy.com/)  
- **Test Data**: Disk image file (`disk.dd`, `disk.img`, `.E01`)

---

## ARCHITECTURE DIAGRAM

<img width="577" height="785" alt="Screenshot 2025-08-22 151258" src="https://github.com/user-attachments/assets/0e9e4744-5534-4828-8715-d6210ba065c3" />

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
<img width="1814" height="1114" alt="Screenshot 2025-09-13 142202" src="https://github.com/user-attachments/assets/fefa6d0a-5da5-46a6-81dd-fb98e91a5164" />

- folder before deleting
  <img width="1213" height="688" alt="Screenshot 2025-09-13 140600" src="https://github.com/user-attachments/assets/c5a3fbe4-2764-4a45-a412-058f477254c0" />
- folder after deleting
  <img width="1209" height="687" alt="Screenshot 2025-09-13 140609" src="https://github.com/user-attachments/assets/82207d8c-ec23-4ddd-a6ee-036a04b16d34" />
- autopsy
<img width="1702" height="1078" alt="Screenshot 2025-09-13 140758" src="https://github.com/user-attachments/assets/ffe63d58-ec59-4e02-b529-d837e131c5bb" />
<img width="1719" height="1075" alt="Screenshot 2025-09-13 140921" src="https://github.com/user-attachments/assets/072d06f3-52c4-4dcd-a51d-3d020c53eaf2" />







- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  
<img width="1919" height="1199" alt="Screenshot 2025-09-13 141326" src="https://github.com/user-attachments/assets/af85f9a3-913b-484f-a6b6-e6e3c2e45a4a" />

- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.



## Output :


<img width="1919" height="1199" alt="Screenshot 2025-09-13 141431" src="https://github.com/user-attachments/assets/6b929449-d90f-47af-b7bd-9d97e447aa5f" />

<img width="1853" height="1199" alt="image" src="https://github.com/user-attachments/assets/d1f2b99b-9102-4200-9f56-7a726e08b37b" />





## RESULT:

Deleted files were successfully retrieved and analyzed using Autopsy.
