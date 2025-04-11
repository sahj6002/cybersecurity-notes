# Basic Computer Networking Notes

A summarized guide to key networking concepts for cybersecurity and general IT knowledge.

---

## OSI Model – 7 Layers
1. **Application Layer**: Interfaces with the user and applications (e.g., web browsers, email clients).
2. **Presentation Layer**: Translates, encrypts, and compresses data for the application layer.
3. **Session Layer**: Manages sessions or connections between devices (start, maintain, end).
4. **Transport Layer**: Ensures reliable data transfer with TCP or faster delivery with UDP.
5. **Network Layer**: Handles logical addressing and routing using IP addresses.
6. **Data Link Layer**: Manages MAC addresses and node-to-node communication in the same network.
7. **Physical Layer**: Transmits raw bits over physical media like cables, switches, and radio signals.

---

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
