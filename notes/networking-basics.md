# Basic Computer Networking Notes

A summarized guide to key networking concepts for cybersecurity and general IT knowledge.

---

## Network Layers (Simplified OSI/TCP Model)
- **Application Layer**: Interfaces with end-user applications (e.g., HTTP, DNS, SMTP).
- **Transport Layer**: Handles data delivery using TCP (reliable) or UDP (faster but unreliable).
- **Internet Layer**: Responsible for logical addressing and routing via IP (IPv4/IPv6).
- **Network Access Layer (Link Layer)**: Deals with physical connections and MAC addresses.

## Common Protocols
- **HTTP/HTTPS**: Protocols used for browsing websites (HTTP is insecure, HTTPS is secure).
- **DNS**: Resolves domain names to IP addresses.
- **SMTP**: Used to send emails.
- **FTP/SFTP**: Transfers files between systems (SFTP is secure).
- **SSH**: Secure remote login to systems.
- **DHCP**: Automatically assigns IP addresses to devices on a network.

## Transport Protocols
- **TCP (Transmission Control Protocol)**: Reliable, connection-based protocol with error checking and flow control.
- **UDP (User Datagram Protocol)**: Faster, connectionless protocol with no guarantee of delivery.

## Internet Protocol (IP)
- **IP Address**: Unique identifier for a device on a network (IPv4: 192.168.1.1, IPv6: longer format).
- **Public IP**: Globally unique and accessible over the internet.
- **Private IP**: Used within local networks (e.g., 192.168.x.x).
- **Subnet Mask**: Defines network and host portions of an IP address.
- **Default Gateway**: Routes traffic from a local network to other networks (e.g., the internet).

## Packets & Data
- **Packet**: Unit of data sent across a network, containing headers and payload.
- **Header**: Contains metadata like source/destination IP and port.
- **Payload**: The actual data being transmitted.

## Routing & Switching
- **Router**: Directs data between different networks.
- **Switch**: Connects devices within the same network (LAN) and forwards data based on MAC addresses.
- **NAT (Network Address Translation)**: Translates private IPs to public IPs for internet access.

## LAN vs WAN
- **LAN (Local Area Network)**: Small network within a home, school, or office.
- **WAN (Wide Area Network)**: Large-scale network, like the internet, that connects multiple LANs.

## Tools
- **ping**: Tests connectivity between two devices.
- **tracert/traceroute**: Shows the path packets take to a destination.
- **ipconfig/ifconfig**: Displays network configuration info.
- **nslookup**: Looks up DNS info for a domain.
- **netstat**: Shows current network connections and listening ports.
