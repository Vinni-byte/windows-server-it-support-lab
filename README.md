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
<img width="605" height="492" alt="{616BD6F0-D432-47D2-8A82-6BC74ADCDD49}" src="https://github.com/user-attachments/assets/ef95f39f-9a2e-4da5-9381-ab36975bebc2" />

