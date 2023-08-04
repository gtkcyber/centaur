# Centaur Virtual Machine

The Centaur Virtual Machine is a VM which contains the necessary Python libraries for GTK Cyber data science courses.

## Credentials
The username for the Centaur VM is `centaur` and the password (with `sudo` permissions) is `Centaur`. 

## Installing the VM

### Step 1:  Download VirtualBox
To run Centaur, you will need to install Virtualbox.  The VM should work with VMWare but has not been tested.  Please download and install the latest version of virtualbox here: https://www.virtualbox.org.

#### Note for Apple M1 Users
At the time of writing, VirtualBox does not support Apple Silicon. In order to run VirtualBox on Apple Silicon, you'll have to use a development build of VirtualBox which is available here: https://www.virtualbox.org/wiki/Testbuilds

### Step 2:  Download and Unzip Appliance 
First download the appliance here: https://drive.google.com/file/d/1_LvSiJA0ZLXGE4B52Uydc0-NcGNqmOK-/view?usp=sharing

Next, untar the file using the TAR program of your choice.

### Step 3:  Install the Appliance.
Navigate to the *File* menu and click on *Import Appliance*

![alt text](https://github.com/gtkcyber/griffon-vm/blob/master/images/import-menu.png "Import Appliance Menu")

Next, navigate to the file you just unzipped which contains the Centaur VM and click Continue.

![alt text](https://github.com/gtkcyber/griffon-vm/blob/master/images/step1.png "Import Appliance Dialog Box")

Once you've done that, the next screen will allow you to configure the VM.  If you are using Centaur to experiment with the various big data tools, we recommmend allocating as many CPUs and as much RAM as your system will allow. **Be sure to check the Reinitialize MAC Address box.**

![alt text](https://github.com/gtkcyber/griffon-vm/blob/master/images/step2.png "Configure Centaur Dialog Box")

Click continue, accept the license, and VirtualBox will install the appliance!
