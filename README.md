<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


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

- Created Virtual Machines
- Installed Wireshark
- Observed ICMP Traffic
- Added a Security Rule in VM2

<h2>Actions and Observations</h2>

![image](https://github.com/cedhorton/azure-network-protocols/assets/173581553/23cca5de-826b-4720-b6cc-13ee6a73d53c)

<p>
Created two virtual machines in Azure. One meachine running Windows, and the other running Linux.
</p>
<br />

![image](https://github.com/cedhorton/azure-network-protocols/assets/173581553/8d43bf5b-5058-45c0-9ebb-7f32c6d80a1f)

<p>
Wireshark installation. 
</p>
<br />

![image](https://github.com/cedhorton/azure-network-protocols/assets/173581553/cd35f9ca-9965-4bc7-8110-b6d13e632a79)

<p>
Observing ICMP traffic between VM1 and VM2. Used Powershell to ping VM2.
</p>
<br />

![image](https://github.com/cedhorton/azure-network-protocols/assets/173581553/49ef6422-c7a2-447b-976d-6d93c27db766)

<p>
Went into VM2's firewall settings to block incoming ICMP pings.
</p>
<br />
