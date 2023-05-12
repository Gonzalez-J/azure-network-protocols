
<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Step 1 Go to Whatismyipaddress.com" and take note of it,<h2>24.162.159.186</h2> 
- Step 2 Create a Windows 10 Virtual Machine (VM) named "vpn-practice"
         While creating the VM, select the previously created Resource Group
         While creating the VM, allow it to create a new Virtual Network (Vnet) and Subnet

- Step 3 Create a Linux (Ubuntu) VM
- Step 4 Observe Your Virtual Network within Network Watcher

<h2>Actions and Observations</h2>

 <p>
<img src="https://i.imgur.com/g4eBC3y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://https://i.imgur.com/sPQbyYe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>        
(Sign up for ProtonVPN and test the VPN connection)
On your actual computer, sign up for the free version of Proton VPN https://account.protonvpn.com/signup?plan=free&language=en I used my own Nord VPN Subscription for this lab, you can use the VPN of your choice.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Back within your VM, download the VPN client of your choice
Login to the VPN and choose a VPN server in yet another country (such as Japan)
Browse to https://whatismyipaddress.com/  and take note of this in a text file
Try browsing to Google, Disney, and/or Amazon and see if there is anything different about the sites in relation to the location of your VPN server. For example, the language or URL may be different

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
(Clean up Azure resources)
Delete the resource group you created in Step 2
Ensure the resources/Resource Group has been deleted so that you don't rack up charges.

</p>
<br />
