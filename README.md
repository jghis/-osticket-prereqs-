<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5
![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/4530f78c-c980-4352-8f9d-3d53510597ab)
creating a resource group  in Azure

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/5600267d-6c18-4f82-8398-2e9cbc061066)
creating a virtual machine in Azure
<h2>Installation Steps</h2>

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/4e75465f-655b-4d62-bc17-6e63befe82f6) 
IIS installed

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/d4f31f5d-66f8-4a3f-a369-da984baa0b1e)
IIS installed

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/d5728364-25ce-45fb-bdde-af456465dd02)

Download and install PHP Manager for IIS

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/42f63d2a-f7f2-4065-bc3a-57f32c9e5564)

Download and install Rewrite Module and create a directory named PHP in the C/drive

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/e1d6bc9f-7d14-40cc-be5a-c8517b20c330)

Download PHP 738,extract and extract the content in the directory created in the c/drive (PHP)

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/fe792712-8c19-431b-92a2-a84c963d0fd2)

Download and install Redistributable X86 exe

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

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/ea030cd2-f89c-492b-8d22-c245c4ae43a1)

In IIS enable some PHP extentions (PHP_intl, PHP_opcache, PHP_inetmap) and restart the server

![image](https://github.com/jghis/-osticket-prereqs-/assets/132087784/daf94f0c-9168-403d-8428-f594484ab16b)

rename the folder osT-sample config to ost-config. set up the permission on this file to let everyone access it.

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
