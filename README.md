<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Installed Active directory through server manager
- Created a user for the admin unit organizational group 
- Created two new organizational groups called _EMPLOYEES & _ADMINS
- Added _ADMINS to the new user that was created

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/qIy4bnm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Installed Active directory by going through the server manager.
</p>
<br />

<p>
<img src="https://i.imgur.com/fKVEcA5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Created a user for the admin unit organizational group. The user Jane_admin was created as an example of a current employee who would be promoted using the active directory. 
</p>
<br />

<p>
<img src="https://i.imgur.com/SL4ussd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <p>
<img src="https://i.imgur.com/HcwI813.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Created two new organizational groups called _EMPLOYEES & _ADMINS. Assigned the _ADMINS group to Jane by opening system properties, Clicking “Remote Desktop”, and Allowing “domain users” access to the remote desktop.

</p>
<br />
