tools that helps with network troubleshooting
apt-get install dnsutils
apt-get install net-tools
apt-get install bridge-utils

ip route
route -n
brctl show
sudo iptables -L
ip -d -4 addr show cni0
ip neigh show 10.244.2.0
bridge fdb show | grep 22:68:9b:b2:f3:36
ip -d link show flannel.1


ARP - Address Resolution Protocol
NAT - Network Address Translation
DNAT -- Destination Network Address Translation
