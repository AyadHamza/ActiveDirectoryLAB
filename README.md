<h1>Virtual Active Directory Lab<h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
Project consists of two virtual machines running on VirtualBox, an active directory domain, and a powershell script that automates the creation of 1000+ users. This project will showcase the ability to setup and configure a virtual network, domain using active directory, objects such as orgaizational units(OU), and automating tasks such as the creation of 1000+ users.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>VirtualBox</b>
- <b>Active Directory</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>Windows Server 2019</b>
- <b>Powershell Integrated Scripting Enviroment<b>

<h2>Program walk-through:</h2>

<p align="center">
Lauch Virtual Box: <br/>
<img src="https://imgur.com/GJsFqRc.png" height="80%" width="80%" alt="Lauch Virtual Box"/>
<br />
<br />
Select approriate network interface cards (Note: One internal, one NAT)  <br/>
<img src=https://imgur.com/H425Orh.png,  height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configure Internal NIC with private IP address<br/>
<img src=https://imgur.com/zreozSO.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Install Active Directory Domain services, DHCP, and Remote Access <br/>
<img src=https://imgur.com/ywleQcg.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Check the Routing box to allow domain controller to act as router<br/>
<img src=https://imgur.com/tHyw7KN.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Once Installed Promote server to domain controller by configuring a new forest and restart<br/>
<img src=https://imgur.com/fe0KFjr.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create a OU and a admin account with full privlages and make sure password never expires<br/>
<img src=https://imgur.com/SUQhf7W.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Add user to Admin group and login to the new user<br/>
<img src=https://imgur.com/b0R1YKA.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configure Routing and remote access<br/>
<img src=https://imgur.com/Prgf2JI.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configure DHCP<br/>
<img src=https://imgur.com/oT8ZITL.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Rename the Server and restart<br/>
<img src=https://imgur.com/byVhCqG.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Develop and Execute Script to create 1000+ users
<img src=https://imgur.com/kekvKCB.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src=https://imgur.com/gQ0HiUT.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
