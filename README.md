# EUTech-Assignment-1
First assignment for software dev internship at EUTech engineers.
_________________________________________________________________________________________________________________________________________________________________________
### Objective: To gain a fundamental understanding of operating systems by installing and configuring a virtual machine with Windows OS.
Steps:
1. `Install Virtual Machine Software: Install virtual machine software, such as VirtualBox or VMware, on your computer.`
2. `Download Windows ISO Image: Download the Windows ISO image file from the Microsoft website or from a reliable source.`
3. `Create a New Virtual Machine: Open the virtual machine software and create a new virtual machine. Choose the type and version of the OS you want to install, and allocate sufficient memory and disk space.`
4. `Install the Windows OS: Mount the downloaded ISO image to the virtual machine, and install the Windows OS as you would on a physical machine. Follow the on-screen
instructions to complete the installation.`
5. `Configure the Virtual Machine: Configure the virtual machine's settings, such as network connectivity, shared folders, and other hardware components. Adjust the display settings and enable sound if necessary.`
6. `Install and Configure Drivers: Install and configure the necessary drivers for the virtual machine to function properly, such as graphics and audio drivers.`
7. `Install and Configure Software: Install and configure any software you need on the virtual machine, such as web browsers, productivity software, or programming tools.`
8. `Test the Virtual Machine: Test the virtual machine by opening various applications and performing some tasks. Make sure that the virtual machine is running smoothly and all components are functioning properly.`
9. `Save the Virtual Machine: Save the virtual machine to a snapshot or a backup file, so that you can easily restore it to its current state if needed.`

`Bonus Step: Experiment with different operating systems or configurations, such as dual- booting or virtualizing multiple OS on the same machine, to gain a better understanding of operating systems and their functionalities.`
_________________________________________________________________________________________________________________________________________________________________________
### Solution

1. Download VirtualBox from [The Official VirtualBox website](https://www.virtualbox.org/wiki/Downloads) and [start the program when downloaded](https://user-images.githubusercontent.com/98554249/232751851-efe02c11-50f4-4c75-bf10-3e257530e29f.png)
2. Download a Microsoft Windows ISO from [Microsoft's Website](https://www.microsoft.com/pl-pl/software-download/windows10)

##### _I downloaded an .OVA file which contains the tools necessary for the task as well as VirtualBox's Guest Addition drivers, therefore I have skipped steps 3, 4, 5, 6 and 7 and replaced them with the process of importing said file._

3. Import the ova by pressing the [import button](https://user-images.githubusercontent.com/98554249/232754384-d2256055-4fbd-4bc7-afde-ef8b2724c0bd.png)
4. Follow the [steps](https://user-images.githubusercontent.com/98554249/232755274-39c879e1-5281-4d50-8735-962446915130.png) provided by the VirtualBox Assistant
5. Check [the specifications of the virtual machine](https://user-images.githubusercontent.com/98554249/232755549-e399eaf6-2fe1-458a-a27d-d8c7d0d68ce6.png) before continuing
6. Once the virtual machine has been successfully imported, we can move on to the tests.
7. I have performed several tests, such as running [Microsoft Visual Studio](https://user-images.githubusercontent.com/98554249/232759237-287a707d-5899-412d-a4f1-22bed8493b32.png) and the virtual machine runs perfectly.


Bonus Step: It's possible to dual boot a virtual machine using a lightweight GNU distribution such as [Lubuntu's Desktop Environment (LXDE)](https://lubuntu.me/downloads/) for usage on top of a previously installed OS like Windows. However, this approach is realistically only viable for test purposes as the process of creating a virtual machine specifically for the lightweight OS is trivial.
