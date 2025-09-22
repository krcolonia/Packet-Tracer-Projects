# Scenario: Company Network Simulation

In this lab scenario, I simulated a network typically seen within a company/corporation. The simulaltion would feature a WAN between a Main Office and a Branch Office, each having its own VLANs, and a DHCP Server to dynamically set the IP Addresses of hosts within said network.

### Network Specifications:
- Main Office with 3 VLANs, 1 DHCP Server
- Branch Office with 2 VLANs
- Each subnet should have a VLAN configuration.

### Addressing Plan:
- **Main Office LAN:** 10.0.0.0/8
	- **HR Dept.:** 10.0.1.0/24
	- **IT Dept.:** 10.0.2.0/24
		- **DHCP Server:** 10.0.2.2/24
	- **Finance Dept.:** 10.0.3.0/24
- **Branch Office LAN:** 20.0.0.0/8
	-**Sales:** 20.0.1.0/24
	-**Support:** 20.0.2.0/24
- **WAN:** 192.168.1.0/30
*Main and Branch office IP Addresses are provided by DHCP server from Main office*

### Network Topology:
<img src="https://i.imgur.com/8oHoZ2U.png">
