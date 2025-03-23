<h1>Active Directory Home Lab Project</h1>

<h2>Overview</h2>
This personal project involved the creation of a fully functional Active Directory home lab environment using Hyper-V. 
The goal was to gain hands-on experience with Active Directory, Windows Server administration, and network configuration, simulating a real-world enterprise network to enhance practical skills relevant to IAM and IT roles.


<h3>Tasks performed</h3>

- <b>Designed and implemented a fully functional Active Directory environment from scratch using Hyper-V.</b>
  
- <b>Installed and configured Windows Server 2019 as a domain controller, establishing a secure and centralized user and resource management system.</b>
  
- <b>Configured essential network services, including DHCP, to automate IP address assignment within the lab environment.</b>
  
- <b>Utilized PowerShell scripting to efficiently create and manage a large number of user accounts within the Active Directory domain.</b>
  
- <b>Successfully joined a Windows 10 client machine to the domain, demonstrating a practical understanding of domain join processes and user authentication.</b>

- <b>Gained hands-on experience with key Active Directory concepts, Windows networking, and virtualization technologies, enhancing skills relevant to IAM Analyst/Engineer roles.</b>

<h2>Environments Used</h2>

- Hyper-V
- Window Server 2019
- WIndow 10 client
 
<h2>Walk-Through</h2>

<p align="center">

Installed and configured Windows Server 2019 as a domain controller <br/>
<img src="https://i.imgur.com/4XdF5sg.png" height="80%" width="80%" alt=""/> 
<br />
<br />
Created an External and Internal NIC to the domain controller<br/>
<img src="https://i.imgur.com/70sulj0.png" height="80%" width="80%" alt=""/> 
<br />
<br />
Created a RAS/NAT to control the flow of traffic to the internet. All internal clients would be directed through the DC to the internet <br/>
<img src="https://i.imgur.com/76rn1Nx.png" height="80%" width="80%" alt=""/>
<br />
<br />
Installed DHCP Server on DC to auotmate IP address within a selected scope <br/>
<img src="https://i.imgur.com/RjsQ9eN.png" height="80%" width="80%" alt=""/>
<br />
<img src="https://i.imgur.com/ch1YlMo.png" height="80%" width="80%" alt=""/>
<br />
<br />
Using PowerShell script to create and manage user accounts within AD<br/>
<img src="https://i.imgur.com/Qm5VXLN.png" height="80%" width="80%" alt=""/>
<br />
<br />
Joined a Windows 10 client machine to the domain<br/>
<img src="https://i.imgur.com/AX3pNKj.png" height="80%" width="80%" alt=""/>
<br />
<img src="https://i.imgur.com/afuMsst.png" height="80%" width="80%" alt=""/>
<br />
<br />
</p>

