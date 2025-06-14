# Windows-os-Virtual-Box
How to setup a Windows OS in Virtual Box

In this lab I will go over how to install a Windows OS onto a Virtual Machine using Virtual Box

## Instructions - Download and Install Software

Below are the links for the software that we will need. I have included the website to download Virtual Box and Windows OS.

Download both files.

[VirtualBox Website](https://www.virtualbox.org/wiki/Downloads)

[Windows ISO](https://www.microsoft.com/en-us/software-download/windows10)

When we download the Windows File, we will need to select a couple of options to download the file as an ISO so we can mount the image in VirtualBox.

- Click on Accept
- Select 'Create installation media (USB flash drive, DVD, or ISO file) for another PC'
- Click next

![image](https://github.com/seanmarqueling/Windows-os-Virtual-Box/blob/main/1.png?raw=true)

- Select 'ISO file'
- Click next
- Save the file in a folder to be used later


![image](https://github.com/seanmarqueling/Windows-os-Virtual-Box/blob/main/2.png?raw=true)

Open up VirtualBox - we are going to add a new VM. Click on New at the top.

![image](https://github.com/seanmarqueling/Windows-os-Virtual-Box/blob/main/3.png?raw=true)

The sections we need to update are:
- Name: Windows-VM
- ISO Image: Select en-us_windows_10_consumer_editions_version_22h2_x64_dvd_8da72ab3 (This image will be found in the folder we saved the Windows ISO from)
- Click on Skip Unattended Installation

![image](https://github.com/seanmarqueling/Windows-os-Virtual-Box/blob/main/4.png?raw=true)

Go into Hardware:
- Base Memory: I am giving this VM 8GB of Memory
- Processors: I am selecting 4 CPUs

Go into Hard Disk:
- Hard Disk Location and Size: I left the location alone, but gave it 5 GB of hard drive space.
- Click on Finish

![image](https://github.com/seanmarqueling/Windows-os-Virtual-Box/blob/main/5.png?raw=true)

VM is now created - go ahead and turn it on.

![image](https://github.com/seanmarqueling/Windows-os-Virtual-Box/blob/main/6.png?raw=true)

Once the VM is open, we need to go through the installation process.

- For the lab we do no have a product key - make sure to select that.
- I used Windows 10 Home Edition
- Select Custom Installation
- After everything installs, your VM is now usable

![image](https://github.com/seanmarqueling/Windows-os-Virtual-Box/blob/main/7.png?raw=true)
