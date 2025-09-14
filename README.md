# EX---4-ORACLE-VM-VIRTUAL-BOX-INSTALLATION--
# Aim
To install Oracle VM VirtualBox, a free and open-source hosted hypervisor, on a computer system, enabling the creation and management of virtual machines for running multiple operating systems on a single host machine.

# Specifications:
# System Requirements:
Operating System: Windows, macOS, or Linux-based OS
Processor: x86/AMD64-compatible CPU (Intel or AMD)
RAM: Minimum 4 GB (8 GB or more recommended)
Storage: Minimum 100 MB for the base application, plus additional space for each virtual machine (at least 20 GB free recommended)
Graphics: Hardware virtualization support (Intel VT-x or AMD-V) is recommended for optimal performance
# Software Requirements:
Internet connection to download the VirtualBox installer
Optionally, Oracle VM VirtualBox Extension Pack for additional features
# Procedure:
# Step 1: Download VirtualBox
Go to the VirtualBox official website: VirtualBox Downloads
Choose the appropriate version for your operating system:
Windows hosts (for Windows users)
macOS hosts (for Mac users)
Linux distributions (for Linux users)
# Step 2: Install VirtualBox (Windows/macOS)
For Windows:
Open the downloaded installer (VirtualBox-x.x.x-xxxx-Win.exe).
Follow the setup wizard:
Click Next.
Select the installation location (default is recommended).
Choose the components you want to install and click Next.
The installer may show a warning about network interfaces; allow it to proceed by clicking Yes.
Click Install and allow the process to complete.
# Step 3: Verify the Installation
Launch VirtualBox from the desktop or start menu.
The VirtualBox Manager should open, showing options to create and manage virtual machines.
Output:

<img width="1918" height="1017" alt="image" src="https://github.com/user-attachments/assets/66c350ce-a710-4a33-8f97-bcf888da3433" />

Step 3: Create a New Virtual Machine
1. In VirtualBox, click on the New button to create a new virtual machine.
2. Name and Type Settings:
Name: Give a name like "Kali Linux". Type: Select Linux. Version: Select Debian (64-bit) or Debian (32-bit) depending on the ISO version you downloaded. 3. Click Next to proceed.

# Step 4: Allocate Memory (RAM)
1. Choose how much RAM to allocate to your virtual machine.
Recommended: At least 2 GB (2048 MB) for Kali Linux, or 4 GB if possible. 2. Click Next.

# Step 5: Create a Virtual Hard Disk
1. Select Create a virtual hard disk now.
2. Click Create.
# Step 6: Select Hard Disk File Type
1. Choose VDI (VirtualBox Disk Image).
2. Click Next.
# Step 7: Storage on Physical Hard Disk
1. Select Dynamically allocated (so the disk will grow as needed).
2. Click Next.
# Step 8: Allocate Storage Space
1. Set the hard disk size. Kali Linux requires at least 20 GB of storage.
You can increase this if you plan to install many additional tools later. 2. Click Create.

# Step 9: Configure Kali Linux ISO
1. Select the VM from the list in VirtualBox and click Settings.
2. Navigate to Storage from the side menu.
3. Under Controller: IDE, click the Empty CD icon.
4. On the right, click the CD icon next to Optical Drive and choose Choose a disk file....
5. Locate and select the Kali Linux ISO you downloaded.
6. Click OK.
# Step 10: Start the Virtual Machine
1. In VirtualBox, click Start to boot up your Kali Linux virtual machine.
# Step 11: Begin Kali Linux Installation
1. The VM will now boot from the ISO. You’ll see a boot menu.  Select Graphical Install and press Enter.
# Step 12: Select Language and Region
1. Choose your language, location, and keyboard layout.  These can be configured to your preference.
2. Click Continue after each selection.
# Step 13: Configure the Network
1. You’ll be prompted to configure the network.
Enter a hostname for your system (e.g., kali). You can leave the domain name empty if you don’t need to set up a domain.
# Step 14: Set Up Users and Passwords
1. Create a root password for the administrator account.
Choose a strong password and re-enter it for confirmation.
# Step 15: Partition Disks
1. Choose Guided - use entire disk for simplicity (recommended for beginners).
2. Select the virtual disk you created earlier.
3. Choose All files in one partition.
4. Finish partitioning and confirm to write the changes to disk.
# Step 16: Install the System
1. The installer will now copy files and install Kali Linux. This may take several minutes.
# Step 17: Install GRUB Bootloader
1. When prompted to install the GRUB bootloader, choose Yes.
2. Select the virtual hard disk as the location to install GRUB.
# Step 18: Complete Installation
1. After the installation is complete, click Continue to reboot the virtual machine.
# Step 19: Login to Kali Linux
1. Once the machine reboots, you’ll be presented with a login screen.
2. Log in using the root account and the password you set earlier.
<img width="1299" height="1031" alt="image" src="https://github.com/user-attachments/assets/ffaa27b1-dbac-48ce-885c-f9c63fb67f28" />

## .sh method

<img width="582" height="337" alt="image" src="https://github.com/user-attachments/assets/14596938-1c3a-433f-8377-9e18fbdd208e" />

# expected output:

<img width="332" height="223" alt="image" src="https://github.com/user-attachments/assets/4270527d-132b-4bb2-9655-abd98dff4486" />


## terminal method :

<img width="596" height="614" alt="image" src="https://github.com/user-attachments/assets/330b061b-a75a-4bee-aa5b-d3e29c6940d8" />

## RESULT:
Thus, this experiment helped in understanding the fundamentals of Linux commands and Bash scripting for automation and system management.
