# Description
This repository contains a network topology demonstrating the configuration of Network Address Translation (NAT) for two offices in different VLANs. The setup includes one router enabled with NAT, a web server, three switches interconnecting the networks, and four PCs serving as endpoints. This configuration showcases how NAT can be used to manage IP addressing and enable communication between devices in different VLANs and the internet.

# Topology Overview
- Router: Configured with NAT to translate private IP addresses to a public IP address for internet access.
- Web Server: Connected to the router, serving web pages to internal and external clients.
- Switches: Three switches providing interconnectivity between the router, web server, and PCs.
- PCs: Four PCs acting as endpoints located in different VLANs, simulating two separate office networks.

# Features
- NAT Configuration: Demonstrates the use of NAT to allow devices in different VLANs to access external networks and services.
- Inter-VLAN Communication: Shows how a single router can manage traffic between multiple VLANs.
- Sample Configuration Files: Includes configuration files for the router, switches, and PCs.
- Network Topology Diagram: Visual representation of the network layout.

# Advantages of NAT
- IP Address Conservation: NAT allows multiple devices on a local network to share a single public IP address, conserving the number of public IP addresses required.
- Enhanced Security: By hiding internal IP addresses from external networks, NAT provides an additional layer of security, making it harder for attackers to directly access internal devices.
- Simplified IP Management: NAT simplifies the management of IP addresses within a network by allowing private IP addresses to be used internally, while handling translation to public IP addresses externally.
