# NetPractice

The aim of the project:

To configure small-scale networks.

Basic information:

The first IP address of the subnet is the address of the network.

The last IP address of the subnet is the broadcast.

IP addresses of neighboring networks must not overlap.

IP-addresses for communication with itself:

from 127.0.0.1 to 127.255.255.254.

Private IP addresses (without access to the Internet):

from 10.0.0.0 to 10.255.255.255

from 172.16.0.0 to 172.31.255.255

from 192.168.0.0 to 192.168.255.255.

Other IP addresses are public (with access to the Internet).

In the routing table, default or 0.0.0.0/0 matches everything.

The router has a different mask for each subnet.

# Useful websites:

https://www.techtarget.com/searchnetworking/definition/TCP-IP

https://avinetworks.com/glossary/subnet-mask/

https://www.practicalnetworking.net/stand-alone/vpn-overlapping-networks/
