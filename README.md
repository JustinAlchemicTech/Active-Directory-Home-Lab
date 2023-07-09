<h1>Active Directory Home Lab</h1>

 ### 

<h2>Description</h2>
In this home lab I walked through how to create an Active Directory Environment using Oracle Virtual Box. Configuring and running this lab helped develop my understanding of how active directory and windows networking works.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>[Oracle Virtual Box](https://www.virtualbox.org/wiki/Downloads)</b>

<h2>Environments Used </h2>

- <b>[Windows 10](https://www.microsoft.com/en-us/software-download/windows10)</b> (21H2)
- <b>[Server 2019](https://www.microsoft.com/en-us/evalcenter/download-windows-server-2019)</b>

<h2>Program Walk-through:</h2>

<p align="center">
Active Directory Lab Overview <br/>
 
<img src="https://i.imgur.com/Kysr2zD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<p align="center">   
Creating Domain Controller and Client VMs <br/>

<img src="https://i.imgur.com/N3KXisK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
   
<p align="center">
<img src="https://i.imgur.com/b0Zq5Gc.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h2> Lab Setup Overview: </h2> 

- Setting up the Virtual Environment: The initial step involves setting up the virtual environment using Oracle VirtualBox. This process includes creating a new virtual machine, allocating necessary resources such as memory and storage, and installing Windows Server 2019 as the operating system.

- Configuring Windows Server 2019: Once the operating system is installed, the next phase is to configure Windows Server 2019 to function as an Active Directory server. This configuration involves setting up the server roles and features, configuring networking settings, and setting up the Active Directory Domain Services role.

- Creating the Active Directory Environment: With the server configured, the next step is to create the Active Directory environment. This process involves creating a new forest and domain, setting up organizational units (OUs), and creating user accounts and groups.

- Bulk Adding Users with PowerShell: After setting up the Active Directory environment, I demonstrate how to bulk add users using a PowerShell script. This includes creating a script to automate the creation of multiple user accounts, setting up permissions, and managing user groups. This automation significantly reduces the time and effort required to add multiple users manually.

Testing and Troubleshooting: The final step is to test the Active Directory environment and troubleshoot any issues. This involves logging in with different user accounts, testing permissions, and ensuring that Group Policy settings were applied correctly.

<h2> Lessons Learned: </h2> 
Through this project, I gained a deeper understanding of how Active Directory and Windows networking works. I learned how to set up and manage an Active Directory environment, how to use PowerShell for bulk user creation, and how to troubleshoot common issues.



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
