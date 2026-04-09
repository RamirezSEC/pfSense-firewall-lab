# Virtual Network Security Lab
<p align="center">
Virtualized network security lab using pfSense firewall and Suricata IDS/IPS

## Description 
<p align="center">
Designed and deployed a virtualized network security lab using pfSense firewall and Suricata IDS/IPS within an Oracle VirtualBox environment. Implemented WAN/LAN segmentation, firewall rule enforcement, DHCP/DNS services, and real-time threat detection to simulate enterprise-level network security operations.

## Lab Architecture 
<p align="center">
The lab architecture simulates a segmented enterprise network using a pfSense firewall with WAN and LAN interfaces in a VirtualBox environment. Internal systems reside on a private subnet and communicate through the firewall, which enforces security policies and monitors traffic using Suricata IDS/IPS:  <br/>
<img src="https://i.imgur.com/mFXMYyC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

## Technologies Used
- pfSense Firewall
- Suricata IDS/IPS
- Oracle VirtualBox
- Windows Server 2022
- PowerShell

## Key Features 
- WAN/LAN network segmentation
- Firewall rule configuration
- DHCP and DNS services
- Intrusion detection and prevention using Suricata
- Log monitoring and threat analysis

## Results
- Successfully deployed a segmented network environment
- Detected and analyzed network threats using Suricata
- Configured secure communication between internal systems
- Implemented firewall rules to control traffic flow

## Screenshots
<p align="center">
pfSense firewall dashboard displaying system status, interface activity, and real-time network traffic within the virtual lab environment:  <br/>
<img src="https://i.imgur.com/kaGv0Ms.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Interface assignments within pfSense showing WAN (em0) and LAN (em1) network mappings used to establish network segmentation in the virtual lab environment:  <br/>
<img src="https://i.imgur.com/bcKT6zx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/FgiuxJ7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/d24WDdg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>  
<br />
<br />
pfSense dashboard displaying system status, including CPU and memory utilization, interface activity, and real-time network traffic within the virtual lab environment: <br/>
<img src="https://i.imgur.com/jZB2O7I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/TgJ0SCe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/8VXk08f.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>  
<br />
<br />
WAN firewall rules demonstrating a default deny posture, where all unsolicited inbound traffic is blocked to protect the internal network:  <br/>
<img src="https://i.imgur.com/Ls0brfT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Default LAN firewall rule allowing internal network devices to initiate outbound connections, enabling controlled communication to external networks:  <br/>
<img src="https://i.imgur.com/Z42ZQQ3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Suricata IDS/IPS alerts displaying detected network activity on the WAN interface, including source and destination traffic data, demonstrating real-time threat monitoring within the lab environment:  <br/>
<img src="https://i.imgur.com/2yCjEDO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Connectivity test from internal Windows Server to external network, demonstrating successful routing through the pfSense firewall:  <br/>
<img src="https://i.imgur.com/5HGHQWj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

## Documentation
Full lab documentation available here:

[pfSense Virtual Firewall Outline](https://1drv.ms/w/c/37fc7e4738a514b3/IQAxzHLj6dMWQ4XdclPyzeqHAVEBVNM3LYMbEGwkpVHwJ78?e=zI3UDq)


## What I Learned
<p align="center">
Through this lab, I gained practical experience building a virtualized network security environment using pfSense and Suricata. I configured WAN/LAN segmentation, DHCP services, and firewall rules, while monitoring traffic and interpreting IDS/IPS alerts. The lab reinforced my understanding of network segmentation, secure traffic flow, and intrusion detection, and gave me hands-on insight into how internal servers interact with firewall policies in a controlled enterprise-style network.
