## Computation
1. **Host**
- Bare Metal (Server with no OS)
  
2. **VM**
- Virtualization
   - Type 1 (Runs on bare metal)
   - Type 2 (Runs on OS)
     
3. **Container**
- Docker
- LXC
  
4. **Orchestrator**
- K8S, Docker Swarm, Mesosm EKS, ECS

5. **Computing Units**
- CPU (ALU), DPU, GPU, SOC, FPGA, ASICS
- Silicon
   - Fab
      - Intel
      - Samsung
- Photonic

## Networking 
1. **OSI Layers**
   - Physical, Data Link, Network, Transport, Session, Presentation, and Application

2. **Load Balancer**
- Application Load Balancer
- Network Load Balancer
- Classic Load Balance(Rarely Used)

3. **Proxy**
   - gateway between users and the internet

4. **Reverse Proxy**
   - behind the firewall in a private network and directs client requests to the appropriate backend server 

5. **Network Address Translation**
   - map multiple private addresses inside a local network to a public IP address

6. **Routing**
- Route53
  - DNS
  - TCP & UDP
  - VETH
  - Tunnels
     - TAP
     - OVS
     - VPP (Vector Packet Processing)
       
7. **Switch**
- OVS Switch
  
8. **CNI**
    - Loopback plugin
    - Bridge plugin
    - PTP plugin
    - MACvlan plugin
    - IPvlan plugin
    - 3rd party plugin
9. **CNDP** (Replacing DPDK, SR-IOV)
    - Accelerates Packet Processing
10. **DPDK**
11. **SR-IOV**
12. **Network Topologies**
    - physical and logical arrangement of nodes and connections in a network
    - Point to Point, Bus, Ring, Star, Tree, Mesh, Hybrid
      
13. **CIDR Notation**
    -  represents an IP address and a suffix that indicates network identifier bits in a specified format. For example, you could express 192.168.1.0 with a 22-bit network identifier as 192.168.1.0/22
    -  Classes
       - Class A (IPv4 address has 8 network prefix bits)
      - 
14. **Subnetting**
    - The practice of dividing a network into two or more networks
   
15. **Public Network**
16. **Private Network**
17. **Static IP**
    - 32 bit number assigned to a computer as an address on the internet
18. **Dynamic IP**
    - IP address that an ISP lets you use temporarily. If a dynamic address is not in use, it can be automatically assigned to a different device.
   
19. **Firewall**
    - Network security device that monitors incoming and outgoing network traffic and decides whether to allow or block specific traffic based on a defined set of security 
20. **Public DNS**
    - A Public DNS Server is one that has a lot of information about which website is hosted on which IP
21. **Private DNS**
    -  prevents your queries from being tracked, modified or surveilled by third-parties
22. **VPN**
    - protects its users by encrypting their data and masking their IP addresses
23. **IPV4 Protocol**
    - IPv4 is composed of 32-bit address length and is the fourth version of the Internet Protocol (IP)
24. **IPV6 Protocol**
    - IPv6 is composed of 128-bit address length and is the latest updated version of the Internet Protocol (IP)
## Storage
1. **CEPH**
   - provides object storage, block storage, and file storage
     
3. **RAID**
   -  manage hard disk drives in a storage array
     
5. **Data Centre** (Racks, Servers, Switches)
   - Hyperscaling
   - HCI
   - Private
   - Public
     - YOTTA
6. **Block**
   - controls data storage and storage devices
    - EBS
8. **Object**
   -  handle large amounts of unstructured data
    - S3
  
## Caching
