# Bourne Again Shell (BASH)

A list of linux commands running on Linux Kernel Distro Ubuntu BASH.

## Changing the working directory
**Using absolute pathname.**
```bash
cd /path/name
```

**To change the working directory to your home directory.**
```bash
cd 
```

<<<<<<< HEAD
**To change the working directory to the previous working directory.**
=======
**To change the working directory to the previous working directory. **
>>>>>>> 7170bab88dff04eabd0d0246b30d25bf94bc341e
```bash
cd -
```

## List command
<<<<<<< HEAD
**To list files sorted by the file modification time.**
=======
**To list files sorted by the file modification time**
>>>>>>> 7170bab88dff04eabd0d0246b30d25bf94bc341e
```bash
ls -lt
```

**To reverse the sort.**
```bash
ls -lt --reverse
```

## Files
**To create an empty file.**
```bash
touch filename.ext
```

## File Type
**To determine the file type (revealing extension of the file)**
```bash
file filename
```

**To open a file.**
```bash
xdg-open filename
```

**To close a file.**
```bash
pkill -f filename
<<<<<<< HEAD
```

## Mounting Disks 
**To mount a disk/hard drive.**
Check the disks available on your system - list block-ed storage devices
```bash
lsblk 
```

Mount the drive.
```bash
sudo mount /dev/sda1 /mnt/myDrive
```

**To unmount the drive.**
```bash
sudo umount /mnt/myDrive
```
=======
>>>>>>> 7170bab88dff04eabd0d0246b30d25bf94bc341e

## Installations
**To install an app: (VS code)**
classic tag - grants the installed application (VS code) unrestricted access to the entire system and files.
```bash
sudo snap install --classic code
```
**To install using Advanced Package Tool (APT).**
```bash
sudo apt install ./application-name.deb
```
**To check an installed app:**
```bash 
snap list code
```

**To uninstall: (VS code)**
```bash
sudo snap remove code
```

**To check the apps installed from snap store:**
```bash
snap list 
```
**To check the apps installed using the apt (Advanced Package Tool):**
```bash 
apt list --installed
```

**To search for a specific installed name:**
```bash 
apt list --installed | grep application-name
