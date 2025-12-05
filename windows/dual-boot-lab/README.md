# Dual Boot Lab – Windows 10 & Windows 8 on One Machine  
*Lab by Yusuf Mohmed Mamun*

This lab demonstrates how to run **two Windows operating systems** on one machine
using a dual-boot setup. It is based on my original college lab report and shows
my understanding of OS installation, disk partitioning, and boot configuration.

---

## 🔎 Lab Overview

**Goals:**
- Install and configure two Windows operating systems on a single disk  
- Set up a working dual-boot menu  
- Manually partition the disk into OS partitions and a shared data partition  
- Create a shared NTFS user-data volume accessible from both OSes  

**Key Skills Demonstrated:**
- Operating system deployment and configuration  
- Disk partitioning and volume management  
- Dual-boot setup and boot menu control  
- Use of Windows tools (Disk Management, msconfig, etc.)  
- Technical documentation and lab write-up  

---

## 🧾 Lab Summary

The original lab walks through:

1. **Planning the disk layout**  
   - Deciding how much space to allocate for each OS  
   - Reserving space for a separate user-data volume  

2. **Installing the first OS (Windows 10)**  
   - Creating a partition for Windows 10  
   - Leaving free space for the second OS and data volume  

3. **Installing the second OS (Windows 8)**  
   - Using the reserved partition for Windows 8  
   - Making sure the first OS is not overwritten  

4. **Configuring the dual-boot menu**  
   - Choosing the default OS  
   - Setting the boot timeout  

5. **Creating a shared user-data volume**  
   - Using Disk Management to create and format an NTFS data partition  
   - Assigning a drive letter (for example, `D:`)  
   - Verifying that both Windows 10 and Windows 8 can access it  

This lab is useful for learning how multi-OS environments work and how to
protect user data using a dedicated partition.

---

## 📄 Original Detailed Lab

The full step-by-step instructions, screenshots, and explanations are in my
original college lab report, stored in this folder:

`original-lab/Dual Boot Lab.docx`

---

## 👨‍💻 Author

**Yusuf Mohmed Mamun**  
Computer System Technician  
Email: `yusufmamun4@gmail.com`
