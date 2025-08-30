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
<img width="1692" height="948" alt="Screenshot 2025-08-30 081359" src="https://github.com/user-attachments/assets/033f8e32-fc1e-4b4a-adab-65534c59444c" />


- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

<img width="968" height="571" alt="Screenshot 2025-08-30 081514" src="https://github.com/user-attachments/assets/8f6f3543-c70a-4511-b152-667d9f1c6f70" />


### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

- Select **Local Disk** → **next** 

<img width="1067" height="670" alt="Screenshot 2025-08-30 081633" src="https://github.com/user-attachments/assets/51d01cf0-bac5-41b6-bc9b-fc3d1eb916e4" />


- Select Disk → **Choose the VHD drive (`Drive1`)**

<img width="1063" height="670" alt="Screenshot 2025-08-30 081710" src="https://github.com/user-attachments/assets/be0f7195-6187-4ce9-aaf1-ed8f07d7b045" />


- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  


<img width="1691" height="949" alt="Screenshot 2025-08-30 081841" src="https://github.com/user-attachments/assets/1c160565-39ca-409e-9ed7-e4d3e4201c51" />

<img width="1700" height="959" alt="Screenshot 2025-08-30 081930" src="https://github.com/user-attachments/assets/5ff4f6e1-97a6-4a73-aa93-996c5114d6b3" />


- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :

#### Name - PRAVESH N
#### Reg. No. - 212223230154

### Folder before deleting the files

<img width="1919" height="1079" alt="Screenshot 2025-08-30 081232" src="https://github.com/user-attachments/assets/fc96146d-77ca-477a-8eae-688dd5e8580b" />


### Folder after deleting the files

<img width="1919" height="1079" alt="Screenshot 2025-08-30 081258" src="https://github.com/user-attachments/assets/81a96b51-3f9a-4741-b1ea-1b58df8a5027" />


### Folder after extracting the deleted images using autopsy

<img width="1919" height="1079" alt="Screenshot 2025-08-30 081232" src="https://github.com/user-attachments/assets/eca9e521-74fc-4129-af73-007c9ee20de5" />

## RESULT:

Deleted files were successfully retrieved and analyzed using Autopsy.

