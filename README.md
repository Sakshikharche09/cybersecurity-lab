# cybersecurity-lab
# Task 1 Home base- lab setup & Networking fundamentals

## Objective
To set upp a safe virtual cybersecurity lab using kali linux and metasploitable and verify basic network connectivity

## Tools Used
Oracle VirtualBox
Kali Linux
Metasploitable 2
Host-only network (vboxnet0)


## Actions Taken
1. Set up VirtualBox on Windows
2. Imported Metasploitable and Kali Linux virtual machines
3. BIOS enabled virtualization
4. Set up the host-only adapter for both virtual machines.
5. Confirmed IP address allocation
6. Ping was used to test connectivity

## Network Configuration
Network Type: Host-only Adapter
Kali IP: '192.168.56.102'
Metasploitable IP: '192.168.56.10'

### Kali Linux
ip addr
ping -c 4 <Metasploitable_IP>

### Metasploitable
ifconfig
