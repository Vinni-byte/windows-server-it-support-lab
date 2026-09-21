# Network Configuration

## Goal

DC01 uses two virtual network adapters:

1. NAT adapter for Internet connectivity.
2. Internal Network adapter for communication with lab clients.

## DC01 Internal Network

Interface: Ethernet 2
Network: IT-LAB

IPv4 address: 192.168.56.10
Subnet mask: 255.255.255.0
Default gateway: None
Preferred DNS: 192.168.56.10

The internal interface uses a static IP because the Domain
Controller needs a predictable address for services such as
Active Directory and DNS.

## Connectivity Test

I verified Internet connectivity using PowerShell:

`Test-NetConnection 8.8.8.8`

Result:

`PingSucceeded: True`

The connection used the NAT interface with source address
10.0.2.15.
