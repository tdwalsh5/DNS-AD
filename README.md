<h1>Building Intuition for DNS</h1>

<p>
  In this lab, I will explore and experiment with the Domain Name System (DNS) to gain a deeper understanding of how it operates and supports network communication. Through practical exercises, I aim to enhance my knowledge of DNS functionality and the critical role it has in translating domain names into IP addresses. 
</p>
<br>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- DNS


<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- A Virtual Machine with Active Directory
- A Client VM joined to your Network 
<br>

<h2>Lab Steps</h2>
<p>
  Go ahead and log into both the Client-1 and DC-1 virtual machines created in the Active Directory lab as the janeadmin user. Once in the client-1 machine, open Powershell as an administrator and attempt to "ping mainframe". The computer will then first check the local DNS cache (fastest), then the local host (faster), and finally the DNS server (slowest). The ping will fail because "mainframe" will not be located in any of these locations. 
</p>
