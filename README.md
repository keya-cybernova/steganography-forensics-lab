# 🔐 Steganography & Digital Forensics Lab

## 📌 Project Overview

This project demonstrates digital forensics techniques by hiding data inside an image (steganography) and recovering deleted evidence using forensic tools.

The lab simulates a real-world investigation scenario where hidden data is embedded, deleted, and later recovered from a disk using forensic analysis.

---

## 🛠️ Tools Used

* SilentEye (Steganography Tool)
* FTK Imager (Digital Forensics)
* VirtualBox (Lab Environment)

---

## ⚙️ Lab Setup

* Created virtual disks (Data & Evidence)
* Configured NTFS file system
* Set up a controlled virtual lab environment

---

## 🔍 Steps Performed

### 1. Data Hiding (Steganography)

* Embedded a secret message inside a JPG image using SilentEye

### 2. Data Storage

* Stored the image inside a virtual disk

### 3. File Deletion

* Deleted the image to simulate a real-world data loss scenario

### 4. Forensic Recovery

* Used FTK Imager to recover deleted files
* Extracted the hidden image from disk

---

## 🚨 Key Findings

* Hidden data inside images can be recovered using forensic tools
* Deleted files remain accessible if not overwritten
* Demonstrated importance of digital forensics in investigations

---

## 🎯 Result

Successfully recovered a deleted image containing hidden data, proving data persistence and forensic recoverability.

---

## 📸 Screenshots

The following screenshots demonstrate key stages of the forensic investigation:

### Lab Setup
![Lab Setup](01_lab_setup.png)

### Steganography (Hidden Data)
![Steganography](steganography.png)

### FTK Recovery Process
![FTK Recovery](ftk-recovery.png)

### Final Recovered File
![Final Output](final-output.png)
## 🚀 Conclusion

This project highlights how attackers can hide sensitive data using steganography and how forensic investigators can recover and analyze hidden or deleted data using specialized tools.
