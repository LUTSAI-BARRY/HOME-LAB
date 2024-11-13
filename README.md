# 🏠 Home-Lab
Personal Cybersecurity Home Lab Setup for Hands-On Learning and Experimentation.

## 🔍 Overview
This repository documents the creation and configuration of my personal cybersecurity home lab. The lab is designed to help me practice various security tools and techniques in a controlled environment.

### 🔧 Tools and Technologies Used
- **Virtual Machines**: Kali Linux, Ubuntu Server, Windows Server
- **Network Devices**: pfSense (Firewall), Virtual Routers
- **Security Tools**:
  - **SIEM**: Splunk, Wazuh
  - **IDS/IPS**: Snort
  - **Vulnerability Scanners**: OpenVAS, Nessus
  - **Packet Analysis**: Wireshark
  - **Penetration Testing**: Metasploit, Nmap
  - **Web Security Testing**: Burp Suite

## 📂 Structure of the Lab
The lab is organized into different components, each serving a specific purpose:
1. **Firewall (pfSense)**: Provides network protection and monitors traffic.
2. **SIEM (Splunk/Wazuh)**: Collects and analyzes logs from various sources.
3. **Penetration Testing Environment**: Using Kali Linux for ethical hacking practices.
4. **Monitoring Tools**: Snort IDS for intrusion detection.

## 🛠️ Setup Instructions
### Step 1: Setting Up Virtual Machines
- Use VMware or VirtualBox to create the following VMs:
  - **Kali Linux** for penetration testing
  - **Ubuntu Server** for hosting applications
  - **Windows Server** for AD and network simulations

### Step 2: Installing pfSense
- Download the ISO from the [pfSense website](https://www.pfsense.org/download/).
- Set up pfSense as a VM and configure it as your main firewall.

### Step 3: Installing Splunk and Wazuh
- Follow the installation guide for [Splunk](https://docs.splunk.com/Documentation/Splunk/latest/Installation) and [Wazuh](https://documentation.wazuh.com/).

### Step 4: Configuring Snort IDS
- Install Snort on a dedicated VM or on your firewall VM.
- Configure Snort rules to detect malicious activities and integrate it with Splunk/Wazuh.

### Step 5: Testing and Experimentation
- Use tools like **Nmap** for network scanning, **Metasploit** for exploitation, and **Wireshark** for traffic analysis.

## 📊 Network Diagram
(You can add an image here if you create a diagram using tools like Lucidchart, Draw.io, or Visio)
![Network Diagram](network-diagram.png)

## 🚀 Next Steps
- Set up advanced monitoring with honeypots.
- Explore cloud integration for scalability.

## 🔗 Resources
- [Splunk Documentation](https://docs.splunk.com)
- [Wazuh Documentation](https://documentation.wazuh.com)
- [Kali Linux](https://www.kali.org/)
- [OpenVAS](https://www.openvas.org/)
