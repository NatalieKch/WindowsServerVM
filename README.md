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

For image choose Windows Server 2022 Datacenter Azure Edition Hotpacht x64. For sizes it is enough to choose Standard E2ds v7. Something with 1 vcpu and 1 or 2 GiB of memory is way too slow. <br/>
<img width="1920" height="837" alt="1 (2)" src="https://github.com/user-attachments/assets/99c830da-f7b2-4bb9-b398-6be43ee4947e" />

Create your administrator account for this VM. For public inbound ports select "None". 

<img width="1920" height="832" alt="1 (3)" src="https://github.com/user-attachments/assets/a2d1334b-35c8-43f0-8d17-d52fab36e469" />
<br />

When all is complete choose "Review And Create" -> "Create". It will take a little bit of time. <br/>

<img width="1920" height="836" alt="1 (4)" src="https://github.com/user-attachments/assets/5818be45-000c-4a7d-a4b3-80cad669cb6a" />
<br/>
<br />
As you see there will be created virtual network interface, network security group, virtual network and public IP. <br/>
<img width="1920" height="832" alt="1 (5)" src="https://github.com/user-attachments/assets/45b1f40c-803f-4b18-9f38-c79fc8ffe1b4" />
Click on your VM. In my case it is "lab-vm" -> Connect via Bastion <br/>
<img width="981" height="722" alt="1 (6)" src="https://github.com/user-attachments/assets/821caa61-03bd-4d6f-912d-adc9ae12fcc1" />
Deploy Bastion. It will take some time. During this process it will ask you to put your username and password that you create before. <br/>
<img width="1233" height="832" alt="1 (10)" src="https://github.com/user-attachments/assets/75464d2f-3a4f-497e-af48-287d8b8bcd3f" />



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
