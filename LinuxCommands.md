# Commands For Instance Recovery project
# Give Root Privileges
```cmd
sudo su
```
## Display the disks
```cmd
fdisk -l
```
## List the files 
```cmd
ls -la
```
## Make Directory 
```cmd
mkdir DirName
```
# Check the Directory Created or Not
```cmd
ls -la
```
# Mount the that file system in new Dir
```cmd
mount /dev/nvme0n1p1 /swati
```
# Check the files system is mounted or not 
```cmd
df -Th
```
# Goto .ssh Directory
```cmd
cd 
```
```cmd
cd .ssh
```
# List the file in .ssh 
```cmd
ls -la
```
# Open the file named authorized_keys
```cmd
cat authorized_keys
```
# Goto root 
```cmd
cd
```
## HERE WE FOUD ONLY ONE KEY SO WE NEED TO REBOOT THE INSTANCE
```cmd
reboot
```
## CONNET THE SAME INSTANCE BY THE SSH PATH
# Give Root Privileges
```cmd
sudo su
```
# Goto .ssh Directory
```cmd
cd .ssh
```
# Open the file named authorized_keys
```cmd
cat authorized_keys
```

# AFTER WORK ON CONSOLE
1. DETACH THE VOLUME AND AGAIN ATTACH TO THE SERVER WHICH WE HAD STOPED
2. WHILE ATTACHING VOLUME TO THE STOP INSTANCE RENAME THE DEVICE NAME eg. Xvda
3. AT THE END WE RESTART THE INSTANCE WHICH IS IN STOP STATE AND ACCESSED IT .
