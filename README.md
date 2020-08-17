# Netstat to monitor network connections.

# Netstat commands.

### Listing all the listening ports of TCP and UDP connections.

netstat -a


### Listing only TCP port connections.

netstat -at


### Listing only UDP port connections.

netstat -au


### Listing all listening port connections.

netstat -l


### Listing all active listening TCP ports.

netstat -lt


### Listing all active listening UDP ports.

netstat -lu


### Listing all active UNIX listening ports.

netstat -lx


### Shows statistics for each protocol.

netstat -s

Shows statistics of following protocls:

* TCP
* UDP
* SCTP
* IP
* IPv6
* IGMP
* ICMP
* ICMPv6


### Shows statistics of only TCP protocol.

netstat -st


### Shows statistics of only UDP protocol.

netstat -su


### Displays service name with PID no.

netstat -tp


### Display promiscuous mode and refreshing screen every 5 seconds.

netstat -ac 5 | grep tcp


### Display kernel IP routing table with nestat and route command.

netstat -r


### Show network interface packet transactions including transferring and receiving packets with MTU(Maximum Transmission Unit, largest packet or frame size).

netstat -i


### Show Kernel interface table.

netstat -ie


### Displays multicast group membership info. for both IPv4 and IPv6.

netstat -g


### To get netstat info. every few seconds.

netstat -c


### Finding unconfigured address families.

netstat --verbose


### To find out how many listening programs running on a port.

netstat -ap | grep http


### Display RAW network statistics.

netstat --statistics --raw


### Shows network memory's cluster statistics.

netstat -M
