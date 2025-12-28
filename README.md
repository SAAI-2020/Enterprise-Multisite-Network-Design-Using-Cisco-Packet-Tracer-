# Enterprise-Multisite-Network-Design-Using-Cisco-Packet-Tracer-
This project demonstrates enterprise multi-site network design with VLANs, inter-VLAN routing, OSPF, ACL security, NAT/PAT, DHCP, STP, and SSH hardening. Includes configuration files, screenshots, and documentation for end-to-end network implementation and testing.

## 🎯 Objectives
- Implement multiple VLANs and inter-VLAN routing across different sites.  
- Configure ACLs to control traffic between departments (e.g., HR and Finance).  
- Setup DHCP for dynamic IP assignment.  
- Implement NAT/PAT for internet connectivity.  
- Configure OSPF for dynamic routing between sites.  
- Enable STP to prevent network loops.  
- Harden network devices using SSH.  
- Demonstrate enterprise-level network monitoring and troubleshooting.

 ## 📝 Step-by-Step Implementation

### Step 1: VLAN Configuration 🟢 
- Created VLANs for HR, Finance, IT, and Management departments.  
- Assigned ports to appropriate VLANs.  
- Verified VLAN configuration using:

### Step 2: Inter-Vlan Routing 🔄
- Configured router interfaces for each VLAN using Router-on-a-Stick.
- Enabled routing between VLANs.
- Verified connectivity using ping between VLAN's.

### Step 3: DHCP Configuration 💻
- Configured DHCP pools for each VLAN and verified with shoow ip dhcp binding.

### STEP 4: ACL Implementation 🚫
- Implemented ACL to block HR VLAN from accessing Finanace VLAN.
- Tested ACL's using ping command from HR to Finanace.

### Step 5: NAT/PAT Configuration 🌐
- Configured NAT for the internet addresses to access the server.
- Verified NAT transalation using 'show ip nat transalation'.

### Step 6: OSPF Configuration 🛣
- Configured OSPF for dynamic routing between sites 192.168.10.0 to 0.0.0.255
- Sites 192.168.20.0 to 0.0.0.255
- Sites 10.0.0.0 to 0.0.0.255

### Step 7: STP Configuration 🌲
- Enabled Spanning Tree Protocol(STP) on all switches to prevent loops.
- It verifies STP status using show spanning tree.

### Step 8: SSH Hardening 🔐
- Configured SSH for secure device management.
- Verified ssh using a terminal client called putty.

### Step 9: verification and Testing ✅
- Verified network connectivity and configuration.
- Ensured VLAN, ACL's, NAT, OSPF and STP operations.


🛠 Skills Highlighted 

VLAN & Inter-VLAN Routing

DHCP Configuration

ACL Implementation & Security Policies

NAT/PAT & Internet Access

OSPF & Dynamic Routing

STP Configuration

SSH Security Hardening

Enterprise Network Design & Troubleshooting

📚 References
Cisco Packet Tracer Documentation
CCNA & Networking Best Practices

✅ Outcome
Successfully designed a secure, multi-site enterprise network demonstrating advanced networking concepts suitable for professional or academic use.
  
  
 ip address 192.168.20.1 255.255.255.0
