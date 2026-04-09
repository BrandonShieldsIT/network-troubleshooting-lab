# 🌐 Network Troubleshooting & Connectivity Lab

##  Overview
This project simulates common network-related issues encountered in a help desk environment. The lab focuses on diagnosing and resolving connectivity problems using standard networking tools and troubleshooting methodologies.

---

##  Scenario

A user reports they are unable to access the internet or internal network resources from their workstation. This lab demonstrates how a help desk technician would systematically diagnose and resolve the issue.

---

##  Tools & Technologies Used

- Windows 10 Client Machine
- Command Prompt
- Networking tools:
  - ipconfig
  - ping
  - tracert
  - nslookup

---

##  Lab Setup

- Configured a local network environment
- Simulated connectivity issues by:
  - Misconfiguring IP settings
  - Disrupting DNS resolution
  - Testing gateway connectivity

---

##  Problem

The client machine is unable to reach external websites or internal network resources due to incorrect network configuration.

---

##  Troubleshooting Process

1. Verified physical/network connection
2. Checked IP configuration using `ipconfig`
3. Identified incorrect or missing IP address
4. Tested connectivity to localhost (127.0.0.1)
5. Tested connection to default gateway using `ping`
6. Tested external connectivity (e.g., 8.8.8.8)
7. Used `nslookup` to diagnose DNS resolution issues
8. Identified root cause (DHCP/DNS misconfiguration)

---

##  Resolution

- Renewed IP address using:
  ```bash
  ipconfig /release
  ipconfig /renew
  Corrected DNS settings
Verified connectivity to:
Local network
Default gateway
External websites
📸 Screenshots



Output of ipconfig showing incorrect configuration
Failed ping results
DNS lookup failure
Successful connectivity after resolution
🛠️ Skills Demonstrated
Network troubleshooting methodology
TCP/IP configuration analysis
DNS and DHCP troubleshooting
Command-line diagnostic tools
Identifying and resolving connectivity issues
💡 What I Learned
How to systematically isolate network issues
The importance of verifying each layer of connectivity
How DNS and DHCP misconfigurations impact user access
🚀 Future Improvements
Expand lab to include VLAN and subnetting scenarios
Simulate firewall-related connectivity issues
Automate diagnostics using PowerShell scripts
