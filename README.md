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

<h2>List of Prerequisites/Steps</h2>

- Install / Enable IIS in Windows WITH
CGI and Common HTTP Features and IIS Management Console
- Install Web Platform Installer
- Install MySQL (set up Usernames and Passwords), Open IIS as an Admin, Register PHP from within IIS,
  and Reload IIS (Open IIS, Stop and Start the server)
- Install C++ Redistributable
- Configure Permissons and Install OsTicket

<h2>Installation Steps</h2>

<p>
![image](https://github.com/drayyan23/osticket-prereqs/assets/165277054/785c7284-8fd1-4db3-b454-8464d804c029)
</p>
<p>
To install IIS with CGI and Common HTTP Features, along with the IIS Management Console on Windows, open the Control Panel and navigate to Programs and Features. Click on "Turn Windows Features On or Off" and check the boxes for "Internet Information Services," "CGI," "Common HTTP Features," and "IIS Management Console." Then, click OK to install. After installation, verify by searching for "Internet Information Services (IIS) Manager" in the Start menu.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To install the Web Platform Installer (Web PI) on Windows, download and run the installer from Microsoft's website. Follow the setup instructions, including accepting license terms. Optionally select additional components. Once installed, launch Web PI from the Start menu or desktop shortcut to browse and install web server components and applications.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install MySQL and set up usernames and passwords via the setup wizard.
Open IIS as an administrator by selecting "Run as administrator" from the Start menu.
Register PHP from within IIS by navigating to the server node, accessing "Handler Mappings," and adding a module mapping for PHP.
Reload IIS by stopping and then starting the server in the IIS Manager.
</p>
<br />
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First, download and install the C++ Redistributable package from the official Microsoft website or through the Microsoft Visual C++ Redistributable download page. Next, configure permissions for the installation directory and relevant system resources. Then, download and install OsTicket from its official website or repository. During the installation process of OsTicket, provide necessary configuration details such as database connection information and administrative credentials. Finally, verify OsTicket's functionality by accessing it through a web browser and perform any additional configuration or customization as needed.
</p>
<br />
