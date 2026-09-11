<h1>Set Up a Windows Server VM in Azure</h1>

In this project I’ll present to you how to set up a Windows Server 2022 VM in Azure, how to connect to that Windows server using Azure Bastion, to set up a static IP and install key features for practicing some tasks in Active Directory. So those features will be: Active Directory, DNS and DHCP. 
<br />


<h2>Utilities Used</h2>

- <b>For this project you need an active Azure account with "pay-as-you-go" subscription preferably. The cost for using Azure resources will be pretty low if you delete used resources after finishing your lab. </b> 

<h2>Environments Used </h2>

- <b>Microsoft Azure</b> (21H2)

<h2>Project walk-through:</h2>

<p align="center">
From the main page of your Azure account choose "Create a resource". Then choose "Virtual machine"<br/>
 <img width="1920" height="844" alt="1 (1)" src="https://github.com/user-attachments/assets/c1b2a050-6a83-4245-a50c-a6cb21a52560" />

<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
