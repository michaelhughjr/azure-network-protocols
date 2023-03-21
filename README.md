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

- Step 1. Creating Resource Group
- Step 2. Creating Virtual Machines
- Step 3. Using Remote Desktop for Windows
- Step 4

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/8qu75v7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Created a resource group called "RG-Lab-02" in Azure to contain or hold the related resources. This allows for easy deployment, updating, and deleting of resources as a group. 
</p>
<br />

<p>
<img src="https://i.imgur.com/JHTXM1i.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Using Microsoft Azure to create two virtual machines called VM1 and VM2 within the resource group named RG-Lab-02. Each virtual machine is running seperate and different operating systems, VM1 is running on a Windows operating system and VM2 is running on a Linux operatig system.
</p>
<br />

<p>
<img src="https://i.imgur.com/R6t0myZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here within Azure each virtual machine is given a public and private IP address, disk space, virtual network (vnet), network interface card (NIC), and a network security group (aka  firewall).
</p>
<br />
