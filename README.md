<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1
- Step 2
- Step 3
- Step 4

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://imgur.com/UcBbGLq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Setting the domain controllers NIC to static .
</p>
<br />

<p>
<img src="https://imgur.com/ybBS4Qx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Conducting a perpetual ping ensuring connectivity between the domain controller and the client.
</p>
<br />

<p>
<img src="https://imgur.com/LEvdugx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Starting to install active directory on the Domain Controller.
</p>
<br />

<p>
<img src="https://imgur.com/BX3dMs9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Adding a new forest (mydomain.com).
</p>
<br />

<p>
<img src="https://imgur.com/KD3liNO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Creating a new organizational unit in active directory.
</p>
<br />

<p>
<img src="https://imgur.com/YOaQQrf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Creating new employee Jane Admin .
</p>
<br />

<p>
<img src="https://imgur.com/gSNATKv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Adding new employee (Jane) to domain admins security group .
</p>
<br />

<p>
<img src="https://imgur.com/vUrrbm6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Setting Client-1 DNS settings to Domain controllers private IP address .
</p>
<br />

<p>
<img src="https://imgur.com/4egUQHl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Client -1 successfully joined to the domain.
</p>
<br />

<p>
<img src="https://imgur.com/BeDhAid.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Allowing all domain (non-administrative users) to remotely access client-1  .
</p>
<br />

<p>
<img src="https://imgur.com/QYs4eYD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Using PowerShell to create multiple new users.
</p>
<br />

<p>
<img src="https://imgur.com/LEvdugx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://imgur.com/LEvdugx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

