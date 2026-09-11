<h1>Set Up a Windows Server VM in Azure</h1>

In this project I’ll present to you how to set up a Windows Server 2022 VM in Azure, how to connect to that Windows server using Azure Bastion, to set up a static IP and install key features for practicing some tasks in Active Directory. So those features will be: Active Directory, DNS and DHCP. 
<br />


<h2>Utilities Used</h2>

- <b>For this project you need an active Azure account with "pay-as-you-go" subscription preferably. The cost for using Azure resources will be pretty low if you delete used resources after finishing your lab. </b> 

<h2>Environments Used </h2>

- <b>Microsoft Azure</b>

<h2>Project walk-through:</h2>

<p align="center">
From the main page of your Azure account choose "Create a resource". Then choose "Virtual machine"<br/>
 <img width="1920" height="844" alt="1 (1)" src="https://github.com/user-attachments/assets/c1b2a050-6a83-4245-a50c-a6cb21a52560" />

<br />
<br />
Create a new resource group, name your virtual machine and fill out all fields:  <br/>
<img width="1920" height="837" alt="1 (9)" src="https://github.com/user-attachments/assets/f191abb1-c18f-4794-9e92-e5dce2928967" />

For sizes it is enough to choose Standard E2ds v7. Something with 1 vcpu and 1 or 2 GiB of memory is way too slow. <br/>
<img width="1920" height="837" alt="1 (2)" src="https://github.com/user-attachments/assets/99c830da-f7b2-4bb9-b398-6be43ee4947e" />

<img width="1920" height="832" alt="1 (3)" src="https://github.com/user-attachments/assets/a2d1334b-35c8-43f0-8d17-d52fab36e469" />

When all of this is complete choose "Review And Create"

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
