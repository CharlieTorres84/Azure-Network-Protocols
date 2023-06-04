# Azure-Network-Protocols<p align="center">
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

- Creating and Building (VM's) in Azure Portal (Windows 10) and Linux (Ubuntu)
- Step 2
- Step 3
- Step 4

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/wspvaJT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this tutorial, were going to be performing some activities on the network between the 2 "Virtual Machines" (VM's) that we're going to create in "Azure Portal" in which will be a "Windows" and "Linux" (Ubuntu) Virtual Machines (VM'S). We are also going to be working with "Azure Network Security Groups" which are "Firewalls" in Azure. Each "Virtual Machine" has it's own "Network Security Group" and were going to test and play with it a bit. The software and tools that were going to be using is "Wireshark" which is a (protocol analyzer), this let's us see the actual raw traffic that's being transmitted between the 2 "Virtual Machines" (VM'S). Were also going to be using a bunch of random "Command Line" tools to generate traffic between the 2 "Virtual Machines" (VM's). So, first we need to log into the "Azure Portal" at (portal.azure.com) so that we can get started with this tutorial.
</p>
<br />

<p>
<img src="https://i.imgur.com/2YVAvx3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<p>
<img src="https://i.imgur.com/NEciWuZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First, we need to create a "Resource Group" so click on the "Resource Group" icon to create.
</p>
<br />

<p>
<img src="https://i.imgur.com/Z7roQc7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
So we can type in a "Resource Group" name here and then click on "Review and Create" to create our "Resource Group".
</p>
<br />


