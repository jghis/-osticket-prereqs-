<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1 Create an Azure virtual machine Window 10, 4 vCPUs.
- Item 2 Install an enable IIS in Windows with CGI and common HTTP features.
- Item 3 Download and install PHP Manager for IIS.
- Item 4 Download and install Rewrite Module.
- Item 5 Download PHP  7.3.8 and unzip the content into c:\PHP
- Item 6 Download and install VC_Redist.x86.exe.
- Item 7 Download and install MySQL 5.5.62
- Item 7 Download and install HeidiSQL
  
![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/4530f78c-c980-4352-8f9d-3d53510597ab)
Creating a resource group  in Azure

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/5600267d-6c18-4f82-8398-2e9cbc061066)
Creating a virtual machine in Azure
<h2>Installation Steps</h2>

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/4e75465f-655b-4d62-bc17-6e63befe82f6) 
 Remote desktop into the virtual machine using microsoft remote desktop tool and install IIS With CGI and common HTTP features.

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/d4f31f5d-66f8-4a3f-a369-da984baa0b1e)
In a web browser type the loopback IP adress 127.0.0.1 to verify if IIS is sucessfully installed. 

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/d5728364-25ce-45fb-bdde-af456465dd02)

Download and install PHP Manager for IIS

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/42f63d2a-f7f2-4065-bc3a-57f32c9e5564)

Download and install Rewrite Module and create a directory named PHP in the C/drive

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/e1d6bc9f-7d14-40cc-be5a-c8517b20c330)

Download PHP 738, and extract the content in the directory created in the c/drive (PHP)

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/fe792712-8c19-431b-92a2-a84c963d0fd2)

Download and install VC_Redist.x86.exe

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/b8daa5a1-2bbc-45ca-927c-d15edaa16b15)
Download and install Mysql server(5.5.62)

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/d923ca3f-8c50-453e-85b0-78ea47d315a3)

Type in Mysql root password.

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/d0f82d7c-56ed-4a69-9444-4d2069d15c60)

Open IIS as an admin, register PHP Manager and restart the server.

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/0d4ab1d1-aad4-45d9-b77d-9612348ff059)

download osTicket

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/53c0d41d-0876-4281-8c81-4710d1552b2a)

Extract the upload folder and copy it into the c/drive (c\inetpub\www Root) and rename the upload folder to osTicket.
Go back to IIS and restart the server.

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/219af500-205d-4bce-9d26-7a365ba5529a)

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/d1000729-cbf4-42ae-a5c3-e9fdc211705b)

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/28046a3e-36a6-478a-8ed4-401695d55d05)

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/ec41e567-5eb7-4eaf-a7ba-0bcd885b9e4e)

In the osTicket installer we can notice that some extentions are not enabled. To enable them we will go back in IIS
and enable some PHP extentions (PHP_intl,PHP_opcache,PHP_inetmap)

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/ea030cd2-f89c-492b-8d22-c245c4ae43a1)

In IIS enable some PHP extentions (PHP_intl, PHP_opcache, PHP_inetmap) and restart the server

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/daf94f0c-9168-403d-8428-f594484ab16b)

rename the folder osT-sample config to ost-config. set up the permission on this file to let everyone access it.

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/16b1b824-d769-4de9-8b48-9860e1d8c2bb)
Install HeidiSQL 12.3.0  

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/8a2c0867-cb18-49f3-a5e4-dc45654fc8b6)
Enter Mysql root password.

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/b849d4b7-b7d6-47d7-8f82-92c61ad29874)

Create osTicket database

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/9780eb6e-db5f-46f7-8353-128d083c9354)

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/e67e6ecb-2f7d-4edb-ac53-f10361449e41)


setting up osTicket database in osTicket browser.

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/fda0e39b-3e78-4a4e-9d08-93480d7e99d1)













![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/9d86a0b8-006f-4602-8aa3-05108398c668)

osTicket logging












<p>
<img src="https://i.imgur.com/DJmEXEB.png" https://i.imgur.com/XUliOSj.pngheight="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
