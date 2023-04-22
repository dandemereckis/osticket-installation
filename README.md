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

- Windows 10 Pro Version 21H2</b>

<h2>List of Prerequisites</h2>

- Create Windows 10 virtual machine using Microsoft Azure
- Enable Internet Information Services (IIS) with CGI
- Download PHP Manager for IIS
- Download Rewrite Module
- Download PHP 7.3.8
- Download Microsoft Visual C++ Redistributable
- Install MySQL Server 5.5.62
- Register PHP from within IIS
- Install osTicket v1.15.8
- Download HeidiSQL to connect to SQL database

<h2>Installation Steps</h2>


<p>
First step is to create a virtual machine using Microsoft Azure. Our virtual machine will be running Windows 10.
</p>
<p>
<img src="https://i.imgur.com/ENjbog3.jpg" height="80%" width="80%" alt="Create VM"/>
</p>
<br />

<p>
We will then use Remote Desktop Connection to log into our virtual machine.
</p>
<p>
<img src="https://i.imgur.com/lSLclNQ.jpg" height="80%" width="80%" alt="Remote Desktop Connection"/>
</p>
<p>
<img src="https://i.imgur.com/MFkqhpZ.jpg" height="80%" width="80%" alt="VM Desktop"/>
</p>
<br />

<p>
From the control panel we need to install Internet Information Services (IIS) with CGI. This will allow us to install PHP manager which will be needed to run our osTicket.
</p>
<p>
<img src="https://i.imgur.com/vUygTZR.jpg" height="80%" width="80%" alt="Install IIS with CGI"/>
</p>
<br />

<p>
We will then download and install PHP Manager if IIS. (Link to download: <a href="https://drive.google.com/uc?id=1RHsNd4eWIOwaNpj3JW4vzzmzNUH86wY_&export=download">PHP Manager Download</a>)
</p>
<p>
<img src="https://i.imgur.com/LaHfdiI.jpg"/>
</p>
<br />

<p>
We will then download the Rewrite Module.  This is needed for osTicket to access URLs behind the scenes properly.  (Link to download: <a href="https://drive.google.com/uc?id=1tIK9GZBKj1JyUP87eewxgdNqn9pZmVmY&export=download">Download Rewrite Module</a>)
</p>
<p>
<img src="https://i.imgur.com/p87FkW3.jpg" height="80%" width="80%" alt="Download Rewrite Module"/>
</p>
<br />

<p>
We will then create a new directory in the C:\ Drive called PHP to store all of our PHP files.
</p>
<p>
<img src="https://i.imgur.com/liMIcIR.jpg" height="80%" width="80%" alt="Create PHP Folder in C:\ Drive"/>
</p>
<br />

<p>
Next step will be to download the files for PHP 7.3.8 and unzip those files into the PHP directoy we just created.  (Link to download: <a href="https://drive.google.com/uc?id=1snNMtLdCOpMtkCyD4mvl9yOOmvVIp9fP&export=download">Download PHP 7.3.8</a>)
</p>
<p>
<img src="https://i.imgur.com/Bd87z3k.jpg" height="80%" width="80%" alt="Extract Files into C:\ Driver"/>
</p>
<br />

<p>
Next we will download Microsoft Visual C++ Redistributable. This is needed for PHP to run correctly.  (Link to download: <a href="https://drive.google.com/file/d/1s1OsGF3-ioO0_9LYizPRiVuIkb3lFJgH/view">Download C++ Redistributable</a>)
</p>
<p>
<img src="https://i.imgur.com/n3AOsxf.jpg" height="80%" width="80%" alt="Download C++ Redistributable"/>
</p>
<br />

<p>
Next we need to download MySQL 5.5.62.  When setting up credentials choose standard configuration.  It will ask you to create a Root password, make sure you write this password down and don't forget it. (Link to download: <a href="https://drive.google.com/file/d/1_OWh9p7VQLcrB0q_V7qT8yHl0xo5gv7z/view">Download MySQL</a>)
</p>
<p>
<img src="https://i.imgur.com/vUygTZR.jpg" height="80%" width="80%" alt="Download MySQL"/>
</p>
<p>
<img src="https://i.imgur.com/KI9EquM.jpg" height="80%" width="80%" alt="Create Root Password"/>
</p>
<br />

<p>
From the control panel we need to install Internet Information Services (IIS) with CGI. This will allow us to install PHP manager which will be needed to run our osTicket.
</p>
<p>
<img src="https://i.imgur.com/vUygTZR.jpg" height="80%" width="80%" alt="Install IIS with CGI"/>
</p>
<br />

<p>
From the control panel we need to install Internet Information Services (IIS) with CGI. This will allow us to install PHP manager which will be needed to run our osTicket.
</p>
<p>
<img src="https://i.imgur.com/vUygTZR.jpg" height="80%" width="80%" alt="Install IIS with CGI"/>
</p>
<br />

<p>
From the control panel we need to install Internet Information Services (IIS) with CGI. This will allow us to install PHP manager which will be needed to run our osTicket.
</p>
<p>
<img src="https://i.imgur.com/vUygTZR.jpg" height="80%" width="80%" alt="Install IIS with CGI"/>
</p>
<br />

<p>
From the control panel we need to install Internet Information Services (IIS) with CGI. This will allow us to install PHP manager which will be needed to run our osTicket.
</p>
<p>
<img src="https://i.imgur.com/vUygTZR.jpg" height="80%" width="80%" alt="Install IIS with CGI"/>
</p>
<br />

<p>
From the control panel we need to install Internet Information Services (IIS) with CGI. This will allow us to install PHP manager which will be needed to run our osTicket.
</p>
<p>
<img src="https://i.imgur.com/vUygTZR.jpg" height="80%" width="80%" alt="Install IIS with CGI"/>
</p>
<br />

<p>
From the control panel we need to install Internet Information Services (IIS) with CGI. This will allow us to install PHP manager which will be needed to run our osTicket.
</p>
<p>
<img src="https://i.imgur.com/vUygTZR.jpg" height="80%" width="80%" alt="Install IIS with CGI"/>
</p>
<br />
