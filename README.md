# Cloud_Module_Week_12

![image](https://github.com/user-attachments/assets/5ae6e95a-7dc9-48ad-88ce-43a1f0772028)


## Assignment: Set Up an Azure Virtual Machine with a Free Account

## Objective

#### The purpose of this assignment is to enable students to gain the skills to create, configure, and perform basic management of virtual machines on the Azure platform.

## Assignment Steps:

### 1-  Create an Azure Account:
* If you don't already have an Azure account, create a free Azure trial account.
You can take advantage of student benefits.

### 2- Create a Resource Group:
* Log in to the Azure portal.
* Go to the "Resource groups" service and create a new resource
group.
* Give the resource group a meaningful name (e.g.,
"StudentNameSurname_RG").
* Select the location of the resource group (e.g., "West Europe").

### 3- Create a Virtual Machine:

* Go to the "Virtual machines" service in the Azure portal and create
a new virtual machine.

##### Basic Settings:

- Resource group: Select the resource group you created.
- Virtual machine name: Give the virtual machine a meaningful
name (e.g., "StudentNameSurname_VM").
- Region: Select the location of the virtual machine (it can be the
same as the resource group).
- Image: Select an operating system image (e.g., "Windows
Server 2019 Datacenter" or "Ubuntu Server 20.04 LTS").
- Size: Choose
- an appropriate size for the virtual machine (e.g.,
"Standard_B1s" or "Standard_B2s"). Consider the credits in
your free trial account.
- Administrator username: Specify an administrator username for
the virtual machine.
- Password: Set a strong password for the virtual machine.


###### Disks:
* You can use the default disk settings. Premium SSD is
recommended for the operating system disk.

###### Networking:

* You can use a default virtual network and subnet.
* Assign a public IP address to the virtual machine to access it.
* Configure the necessary network security group rules to allow
RDP (Windows) or SSH (Linux) access to the virtual machine.

###### Management:
* You can configure monitoring and diagnostics settings.

######  Advanced:
* If necessary, you can configure extensions or other advanced
settings.

###### Tags:
* You can assign tags to the virtual machine (e.g.,
"StudentNameSurname", "Assignment").

###### Review and create:
* Review the virtual machine settings and click the "Create"
button.

### 4-Connect to the Virtual Machine:
* After the virtual machine is created, go to the virtual machine in the
Azure portal.
###### Windows:
* Click the "Connect" button and download the RDP file.
* Open the RDP file and log in with the administrator username
and password.

###### Linux:
* Connect using an SSH client (e.g., PuTTY or Windows Terminal)
using the virtual machine's public IP address.
* Log in with the administrator username and password

### 5-Create and Connect to Azure File Share:
* In the Azure portal, go to the "Storage accounts" service and
create a new storage account.
* Within the storage account, go to the "File shares" service and
create a new file share.
* Connect the file share you created to your virtual machine and your
PC (Windows or Linux).
  * Windows: Map a network drive to the file share
  * Linux: Mount the file share using CIFS

### 6-Tasks on the Virtual Machine (Optional!):
###### Windows:
** Install the IIS web server and publish a website.
** Install SQL Server Express and create a database.
** Create, read, and delete files on the Azure File Share you
created.

###### Linux:
