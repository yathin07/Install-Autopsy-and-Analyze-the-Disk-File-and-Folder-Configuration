
# Install Autopsy and Analyze the Disk File and Folder Configuration

## AIM
To install **Autopsy** and use it to analyze the disk’s file and folder configuration for forensic investigation.

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tools**:  
  - [Autopsy Digital Forensics Platform](https://www.autopsy.com/)  
  - Optional: Sleuth Kit CLI tools for deeper analysis
- **Test Data**: Disk image file (`.dd`, `.img`, `.E01`)

## ARCHITECTURE DIAGRAM
```mermaid
flowchart TD
    A[Disk Image / Physical Drive] --> B[Install Autopsy]
    B --> C[Create New Case in Autopsy]
    C --> D[Add Data Source: Disk Image]
    D --> E["Autopsy Modules Run: File System, Metadata, Keywords"]
    E --> F[File & Folder Structure View]
    F --> G[Export / Recover Files]
```
## DESIGN STEPS:
### Step 1:
Download Autopsy from the official website and install it on your system.

### Step 2:
Launch Autopsy and create a new case.

### Step 3:
Add your disk image or physical drive as the data source.

### Step 4:
Allow Autopsy to run its built-in ingest modules (file system analysis, hash lookup, keyword search, metadata extraction).

### Step 5:
View the file and folder hierarchy in the left-hand tree panel.

### Step 6:
Export or recover files if required for the investigation.

## PROGRAM(Windows)

1. Download Autopsy from autopsy.com.
2. Install and launch the application.
3. Select **New Case → Name your case → Choose case folder**.
4. Click Add **Data Source → Select Disk Image → Browse to file**.
5. Choose ingest modules (file system, metadata, hash lookup, keyword search).
6. Wait for processing to finish.
7. Explore file/folder structure in the navigation pane.
8.Export selected files for further examination.

## OUTPUT:

<img width="1693" height="874" alt="Screenshot 2025-08-20 101659" src="https://github.com/user-attachments/assets/132c84c0-905c-40b6-8b52-ea7930488331" />

<img width="1128" height="696" alt="Screenshot 2025-08-22 084016" src="https://github.com/user-attachments/assets/c15563a1-a29b-47da-a94f-3c6118476b6f" />

<img width="1917" height="1013" alt="Screenshot 2025-08-22 092539" src="https://github.com/user-attachments/assets/79c0dcc6-8a4a-4d68-aa4b-2a23805272c3" />

<img width="1059" height="674" alt="Screenshot 2025-08-22 092651" src="https://github.com/user-attachments/assets/f1fa148a-5be4-4f0b-abc6-72f3d0cf7ba3" />

<img width="1706" height="898" alt="Screenshot 2025-08-22 092855" src="https://github.com/user-attachments/assets/14490697-0ca7-45f3-b566-22547c9cb2ca" />

<img width="1694" height="895" alt="Screenshot 2025-08-22 094047" src="https://github.com/user-attachments/assets/2eb1e6d8-9967-4c48-abdd-a64a9dfcdd1b" />

<img width="1844" height="923" alt="Screenshot 2025-08-22 094455" src="https://github.com/user-attachments/assets/a74c1122-b1c3-4321-b2e2-18242efa12bd" />

<img width="1756" height="899" alt="Screenshot 2025-08-22 094650" src="https://github.com/user-attachments/assets/3286485a-c136-47a6-bde3-c917e8352664" />

<img width="971" height="581" alt="Screenshot 2025-08-22 094848" src="https://github.com/user-attachments/assets/e1ccef9e-1ac0-4838-acc9-855127fcd85f" />

<img width="843" height="126" alt="Screenshot 2025-08-29 091911" src="https://github.com/user-attachments/assets/12a5711c-4747-474b-b955-be75883a0e66" />

<img width="1710" height="902" alt="Screenshot 2025-08-29 093343" src="https://github.com/user-attachments/assets/94af3cd0-add7-4b58-84c9-d7b9defde44b" />

<img width="1510" height="871" alt="Screenshot 2025-08-29 093959" src="https://github.com/user-attachments/assets/2c31a38d-31bf-4f72-9c6a-ed7be30d5a7f" />

<img width="1845" height="871" alt="Screenshot 2025-08-29 094301" src="https://github.com/user-attachments/assets/74f5e835-541a-4782-9479-d9cc3f263aa8" />

<img width="1206" height="380" alt="Screenshot 2025-08-29 095018" src="https://github.com/user-attachments/assets/4f2714e9-b220-42e3-aa05-8eda9a46dbcc" />
















File and Folder Configuration Analysis Results

## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
