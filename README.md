00. Using Vagrant as a personal computer

01. Virtual Machine vs Virtual environment
A virtual machine is a programmed-computer installed on your computer, and emulates everything from the CPU to the RAM and Disk. In this way, virtual machines can be installed on your MacOS, window  or Linux distribution. The virtual machine now allows you to run its own virtual environment just as you are running your host operating system software.

02. Vagrant is a tool that works beyond a virtual machine provider. Vagrant gives you the possibility to use different virtual machine providers. Moreover, Vagrant is free, reliable and well-maintained.


03. How to install Vagrant
    000. For MacOS, Download VirtualBox, Install the VirtualBox, Download Vagrant, Install Vagrant. Open the Terminal application. Now you will execute the command line in your Terminal (each of them start with $). Add the Ubuntu 20.04 (Focal) image to your box list:$ vagrant box add ubuntu/focal64. This step may take time. Create your first virtual machine:$ vagrant init ubuntu/focal64 => this will generate a Vagrantfile with base = ubuntu/focal64
$ vagrant up => this starts the virtual machine
$ vagrant ssh => this puts you in the virtual machine
   001. There are different steps that also apply to installation on windows and Ubuntu

