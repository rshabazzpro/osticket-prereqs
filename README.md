<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This guide provides an overview of the requirements and the process for installing osTicket, an open-source help desk ticketing system.<br />




<h2>Utilized Environments and Technologies</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- PhPManager for IIS
- Rewrite Module  
- PHP
- VC_redist
- MySQL
- osTicket 

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/dlzzqGy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I began by establishing a resource group where my virtual machine would be hosted. After creating the resource group, I proceeded to generate the virtual machine and associated it with the resource group. Finally, I completed the setup of my virtual machine.
</p>
<br />

<p>
<img src="https://i.imgur.com/Nx8L9rI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here, I obtained the public IP address of my virtual machine to enable remote desktop control (RDC) and access the newly created virtual machine.
</p>
<br />

<p>
<img src="https://i.imgur.com/XTHURzM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here, I used Remote Desktop Control (RDC) to access my virtual machine. I downloaded PhpManager for IIS and then accessed it from my downloads folder to complete the setup.
</p>
<br />
<p>
<img src="https://i.imgur.com/gxZm5N9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this step, I installed the Rewrite Module, which is used to rewrite certain URLs. 😉
</p>
<br />
<p>
<img src="https://i.imgur.com/7TVIXAt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this step, I acquired a file named PHP containing its contents. I intend to unzip these contents into a directory I've established within the C/ directory, naming it PHP. The process involves extracting the contents from the right and transferring them into the designated directory on the left.
</p>
<br />

<p>
<img src="https://i.imgur.com/tFD77fE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
VC_redist serves as an installer for one of the redistributables.
</p>
<br />

<p>
<img src="https://i.imgur.com/sSpkLhS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
MySQL, the second-to-last requirement, functions as a simple database management system employed for this lab.
</p>
<br />

<p>
<img src="https://i.imgur.com/zNrUblb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Finally, osTicket! It's the last prerequisite that had to be installed to ensure everything runs smoothly.
</p>
<br />
