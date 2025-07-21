# 2.0 Networking (23% of Core 1 Exam)

_Focus: Understanding network protocols, wireless technologies, network services, configuration concepts, hardware devices, SOHO networks, connection types, and network tools_

---

## 2.1 TCP and UDP Ports, Protocols, and Purposes

**Comparison Focus:** You'll need to identify common port numbers, distinguish between TCP and UDP protocols, and understand when each protocol is used.

### Essential Ports and Protocols:

- **FTP (20-21)** - File Transfer Protocol for file transfers
- **SSH (22)** - Secure Shell for encrypted remote access
- **Telnet (23)** - Unencrypted remote terminal access
- **SMTP (25)** - Simple Mail Transfer Protocol for sending email
- **DNS (53)** - Domain Name System for name resolution
- **DHCP (67/68)** - Dynamic Host Configuration Protocol for IP addressing
- **HTTP (80)** - Hypertext Transfer Protocol for web traffic
- **POP3 (110)** - Post Office Protocol 3 for email retrieval
- **NetBIOS (137-139)** - Network Basic Input/Output System
- **IMAP (143)** - Internet Mail Access Protocol for email access
- **LDAP (389)** - Lightweight Directory Access Protocol
- **HTTPS (443)** - HTTP Secure for encrypted web traffic
- **SMB/CIFS (445)** - Server Message Block for file sharing
- **RDP (3389)** - Remote Desktop Protocol for Windows remote access

### TCP vs UDP:

- **TCP** - Reliable, connection-oriented, error checking
- **UDP** - Fast, connectionless, no error checking

_Key Study Point: Memorize the most common ports (22, 23, 25, 53, 80, 110, 143, 443) and understand whether each service requires reliable delivery (TCP) or speed (UDP)._

---

## 2.2 Wireless Networking Technologies

**Explanation Focus:** You'll compare different wireless technologies and understand their appropriate use cases and limitations.

### Wireless Frequencies:

- **2.4GHz** - Longer range, more interference, slower speeds
- **5GHz** - Shorter range, less interference, faster speeds
- **6GHz** - Newest band, highest speeds, shortest range

### Channel Management:

- **Regulations** - Government restrictions on frequency use
- **Channel Selection** - Avoiding interference through proper planning
- **Channel Widths** - 20MHz, 40MHz, 80MHz, 160MHz options
- **Frequency Bands** - ISM band usage and restrictions

### Wireless Standards and Technologies:

- **802.11 Standards** - Wi-Fi protocol evolution (a/b/g/n/ac/ax)
- **Bluetooth** - Short-range personal area networking
- **NFC** - Near Field Communication for proximity data transfer
- **RFID** - Radio Frequency Identification for asset tracking

_Key Study Point: Understand the trade-offs between range, speed, and interference across different frequencies and when to use each wireless technology._

---

## 2.3 Networked Host Services

**Summary Focus:** You'll identify various server roles and network appliances, understanding their functions in enterprise environments.

### Server Roles:

- **DNS** - Domain name resolution services
- **DHCP** - Automatic IP address assignment
- **File Share** - Centralized file storage and access
- **Print Servers** - Network printing management
- **Mail Servers** - Email processing and delivery
- **Web Servers** - HTTP/HTTPS content delivery
- **Syslog** - Centralized logging and monitoring
- **AAA** - Authentication, Authorization, and Accounting
- **Database Servers** - Data storage and retrieval
- **NTP** - Network Time Protocol for time synchronization

### Internet Appliances:

- **Spam Gateways** - Email filtering and protection
- **UTM** - Unified Threat Management for security
- **Load Balancers** - Traffic distribution across servers
- **Proxy Servers** - Content filtering and caching

### Specialized Systems:

- **SCADA** - Supervisory Control and Data Acquisition for industrial systems
- **IoT Devices** - Internet of Things connected devices

_Key Study Point: Match each service type to its primary function and understand how they work together in network infrastructure._

---

## 2.4 Network Configuration Concepts

**Explanation Focus:** You'll configure DNS records, DHCP settings, VLANs, and VPNs while understanding their security and operational implications.

### DNS Record Types:

- **A Records** - Map hostnames to IPv4 addresses
- **AAAA Records** - Map hostnames to IPv6 addresses
- **CNAME** - Canonical name aliases
- **MX Records** - Mail exchanger routing
- **TXT Records** - Text data for various purposes
    - **DKIM** - DomainKeys Identified Mail
    - **SPF** - Sender Policy Framework
    - **DMARC** - Domain-based Message Authentication

### DHCP Configuration:

- **Leases** - Temporary IP address assignments
- **Reservations** - Permanent IP assignments for specific devices
- **Scope** - Range of available IP addresses
- **Exclusions** - IP addresses removed from automatic assignment

### Network Segmentation:

- **VLANs** - Virtual LANs for logical network separation
- **VPNs** - Virtual Private Networks for secure remote access

_Key Study Point: Understand how DNS and DHCP work together to provide seamless network connectivity and how VLANs provide security through network segmentation._

---

## 2.5 Networking Hardware Devices

**Comparison Focus:** You'll select appropriate network devices based on requirements and understand their specific functions and capabilities.

### Core Network Devices:

- **Routers** - Route traffic between different networks
- **Switches**
    - **Managed** - Configurable VLANs, QoS, monitoring
    - **Unmanaged** - Basic switching, plug-and-play
- **Access Points** - Provide wireless network connectivity
- **Patch Panels** - Organize and manage cable connections
- **Firewalls** - Control network traffic based on security rules

### Power and Connectivity:

- **Power over Ethernet (PoE)**
    - **Injectors** - Add PoE to non-PoE switches
    - **PoE Switches** - Built-in power delivery
    - **PoE Standards** - 802.3af, 802.3at, 802.3bt power levels

### Internet Connection Devices:

- **Cable Modem** - Cable internet connectivity
- **DSL Modem** - Digital Subscriber Line connectivity
- **ONT** - Optical Network Terminal for fiber connections
- **NIC** - Network Interface Card with unique MAC address

_Key Study Point: Know when to use managed vs unmanaged switches and understand PoE power requirements for different devices._

---

## 2.6 SOHO Network Configuration

**Scenario Focus:** You'll configure small office/home office networks including IP addressing schemes and basic routing.

### IP Addressing Concepts:

- **IPv4 Private Addresses** - 10.x.x.x, 172.16-31.x.x, 192.168.x.x
- **IPv4 Public Addresses** - Internet-routable addresses
- **IPv6** - Next-generation addressing with 128-bit addresses
- **APIPA** - Automatic Private IP Addressing (169.254.x.x)
- **Static vs Dynamic** - Manual vs DHCP address assignment
- **Subnet Mask** - Defines network and host portions
- **Gateway** - Default route for external network access

_Key Study Point: Memorize the private IP address ranges and understand the difference between static and dynamic addressing in SOHO environments._

---

## 2.7 Internet Connection Types and Network Types

**Comparison Focus:** You'll evaluate different internet connection options and network topologies based on speed, cost, and availability requirements.

### Internet Connection Types:

- **Satellite** - Rural areas, high latency, weather dependent
- **Fiber** - Highest speeds, best reliability, limited availability
- **Cable** - Fast download, shared bandwidth, widely available
- **DSL** - Uses phone lines, distance dependent, moderate speeds
- **Cellular** - Mobile connectivity, data caps, variable coverage
- **WISP** - Wireless Internet Service Provider for rural areas

### Network Type Classifications:

- **LAN** - Local Area Network (building/campus)
- **WAN** - Wide Area Network (geographically dispersed)
- **PAN** - Personal Area Network (individual workspace)
- **MAN** - Metropolitan Area Network (city-wide)
- **SAN** - Storage Area Network (high-speed storage)
- **WLAN** - Wireless LAN implementation

_Key Study Point: Match connection types to appropriate use cases based on geography, speed requirements, and budget constraints._

---

## 2.8 Networking Tools and Purposes

**Explanation Focus:** You'll identify the correct tools for specific network installation, maintenance, and troubleshooting tasks.

### Cable Installation Tools:

- **Crimper** - Attach connectors to network cables
- **Cable Stripper** - Remove cable jacket and insulation
- **Punchdown Tool** - Terminate cables in patch panels/jacks

### Network Testing Tools:

- **Cable Tester** - Verify cable continuity and wiring
- **Loopback Plug** - Test network port functionality
- **Toner Probe** - Trace cables through walls/conduits
- **Wi-Fi Analyzer** - Analyze wireless signal strength and interference
- **Network Tap** - Monitor network traffic for analysis

_Key Study Point: Know which tool to use for specific scenarios - cable installation vs testing vs troubleshooting wireless issues._

---

## Study Tips for Networking Domain

### High-Priority Topics:

- Common port numbers and their protocols
- Private vs public IP addressing
- Wireless frequency characteristics (2.4GHz vs 5GHz vs 6GHz)
- DHCP vs static IP configuration

### Common Exam Scenarios:

- User can't access internal file server (port/protocol issue)
- Wireless connectivity problems (frequency/channel conflicts)
- SOHO network setup with proper IP addressing
- Selecting appropriate internet connection type

### Hands-On Practice:

- Configure SOHO router with proper IP schemes
- Use Wi-Fi analyzer to identify optimal channels
- Practice cable termination with crimping tools
- Set up VLANs on managed switches

---

_Weight: 23% of Core 1 Exam | Estimated Study Time: 25-30 hours_