# Networking
- We can assign multiple IP's to same ethernet interface but not the same IP to multiple interface
  > `sudo ip addr add 172.16.239.10/24 dev eth0`
  > `sudo ip addr add 172.16.238.15/24 dev eth0` --Possible
  > `sudo ip addr add 172.16.238.15/24 dev eth1` --Not possible
