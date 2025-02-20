# linux-networking


## Links of interest about linux networking.

- [100 Days of DevOps — Day 62-Useful Linux Command for Network Troubleshooting](https://medium.com/@devopslearning/100-days-of-devops-day-62-useful-linux-command-for-network-troubleshooting-920430a2f75f)
- [TCP/IP networking reference guide](http://www.penguintutor.com/linux/basic-network-reference)
- [Part1:  Linux Networking Basics, SSH. Franz Sch ̈afer. Linux LV, WU Wien](http://mond.at/cd/part1.pdf)
- [Part2:  Linux Server, Backup, Boot, LVM, Virtualization. Franz Sch ̈afer. Linux LV, WU Wien](http://mond.at/cd/part2.pdf)

- [Blog about linux networking](https://vincent.bernat.ch/en/blog)
- [Vincent Bernat](https://github.com/vincentbernat)
- [Proper isolation of a Linux bridge](https://vincent.bernat.ch/en/blog/2017-linux-bridge-isolation)

- [nftables is the new packet classification framework that replaces the existing {ip,ip6,arp,eb}_tables infrastructure](https://wiki.nftables.org/wiki-nftables/index.php/Main_Page)
- [nftables: Netfilter hooks](https://wiki.nftables.org/wiki-nftables/index.php/Netfilter_hooks)

- [Network bridge](https://wiki.archlinux.org/index.php/Network_bridge)

- [mytcpip.com/netplan-ubuntu/](https://mytcpip.com/netplan-ubuntu/)

- [archlinux.org systemd-networkd](https://wiki.archlinux.org/title/systemd-networkd)
  
- [nftables book iescierva.net Spanish](https://www.iescierva.net/wp-content/uploads/2024/09/nftables.pdf)

## network bandwidth monitoring
- [network-bandwidth-monitoring-tools](https://www.tecmint.com/linux-network-bandwidth-monitoring-tools/)

```bash
# Option description
# -b, --use-bit
#    Show rates in bits per second instead of bytes per second. 
#  -U, --use-si
#    Use SI unit system (1KB = 1'000 bytes) instead of 1KB = 1'024 bytes.

bmon -b
```

- [IPerf is a CLI tool that determines the bandwidth between 2 points in a network](https://github.com/scc365/guide-network-testing/blob/main/iperf/IPERF.md)

- [hping is an open-source packet generator and analyzer for the TCP/IP protocol](https://en.wikipedia.org/wiki/Hping)

## iftop: display bandwidth usage on an interface

iftop does for network usage what top(1) does for CPU usage. It listens to network traffic on a named interface and displays a table of current bandwidth usage by pairs of hosts. Handy for answering the question "why is our ADSL link so slow?". 

## Netcat 
```
  .       .       
  \`-"'"-'/       
   } 6 6 {        
  ==. Y ,==       
    /^^^\  .      
   /     \  )     
  (  )-(  )/     _
  -""---""---   / 
 /   Ncat    \_/  
(     ____        
 \_.=|____E
```

[https://nmap.org/ncat/](https://nmap.org/ncat/)

Among Ncat’s vast number of features there is the ability to chain Ncats together, redirect both TCP and UDP ports to other sites, SSL support, and proxy connections via SOCKS4 or HTTP (CONNECT method) proxies (with optional proxy authentication as well).

## Some useful commands

```bash
# Show address
# Option description
#  c colors
#  h output statistics with human readable
#  s statistics or some time values.
#  d details Output more detailed information.
ip -c -h -s -d a
```
