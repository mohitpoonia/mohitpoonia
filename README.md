- 👋 Hi, I’m @mohitpoonia
- 👀 I’m interested in Cloud Computing
Here are some keywords 🗝️:
# BASIC KEYWORDS
1. **CISC** - Complex Instruction Set Computer- Closed source - intel, AMD
2. **RISC** - Reduced Instruction Set Computer- Closed source - ARM
3. **RISC-V**  - It is an ISA based on reduced instruction set computer (RISC) principles. It is Open Source unlike the parent RISC.
4. **Kernel** - programm to manage communication between software i.e. user-level applications and hardware i.e., CPU and disk memory  
- Kernel Programming Languages
  - C
  - Rust
  - C++

| Kernel Space  | User Space |
| ------------- | ------------- |
| System Interface  | Application Code  |
| Generic Services  | C Library  |
| Device Drivers  | -  |

5. **DNS** - turns domain names into IP addresses, which allow browsers to get to websites and other internet resources.
- How DNS Work



### DNS Record Names

<img width="539" alt="Screenshot 2023-09-01 182634" src="https://github.com/mohitpoonia/mohitpoonia/assets/142895350/2186fbfa-e058-4b8d-b750-4ba0a04ec790">

6. **ISA** - Instruction Set Architecture - hardware interaction - input-outputs, registers, data types
7. **IP Addresss**- Internet Protcol (IPv4,IPv6)
 - Public IP - B/W Internet and Device, assigned by internet service provider to the device
 - Private IP - in a private network [starts with 10., 172.16, 192.168
 - Local IP - [starts with 127.00.0
9. **Port No.** - a way to identify a specific process to which an internet or other network message is to be forwarded when it arrives at a server.[for http - 80
 - SSH(Secure Shell) - 22
 - SMTP - 25  
 - Telnet - 23
 - https - 443
10. **SSL**- Secure Socket Layer - IP Address + Port Number
11. **Seven Layers Of OSI**(Open Systems Interconnection)
 - L7 - Application
 - L6 - Presentation
 - L5 - Cryptography
 - L4 - Port Number(16 Bits)
 - L3 - IP Address (32 Bits) : Router
 - L2 - Hardware Address - NIC, MAC Address(48 Bits) : Ethernet :*SWITCH*
 - L1 - Digital (1 and 0)


12. **Switch** - connects devices in a network to each other, enabling them to talk by exchanging data packets.
13. **Virtual Machine** - created by using Hypervisor
14. **FPGA** - Field Programmable Gate Arrays  - Configurede after manufacturing
15. **Socket** - Software structure within a network node of a computer network that serves as an endpoint for sending and receiving data across the network
16. **TCP** - Transmission Control Protocol (TCP) is a standard that defines how to establish and maintain a network conversation by which applications can exchange data
17. **MAC Address** - Media Access Control address is a unique identifier assigned for use as a network address in communications within a network segment.
18. **Protocol**- It is a standardized set of rules for formatting and processing data.
19. **Firmware** - It is a microcode or program that is embedded into the memory of hardware devices to help them operate
20. **TLS** - Transport Layer Security encrypts data sent over the Internet : Version 1.3
21. **Cache** - a cache is a high-speed data storage layer which stores a subset of data (temporary mermory)
22. **STACK** - Stack is a linear data structure that follows a particular order in which the operations are performed. **LIFO** (Last In First Out)

23. Von Neuman Architecture **VS** Harvard Architecture 

![MergedImages](https://github.com/mohitpoonia/mohitpoonia/assets/142895350/0c89419c-74ba-4024-94e4-f751d391bb8d)


25. **Debian** - Linux Software/OS Family
26. **VMware Workstation** - IT is a line of Desktop Hypervisor products which lets users run virtual machines, multiple OS
27. **VPN** - It establishes a digital connection between your computer and a remote server owned by a VPN provider, creating a point-to-point tunnel that encrypts your personal data, masks your IP address, and lets you sidestep website blocks and firewalls on the internet.
28. **Cryptography** - It is the practice and study of techniques for secure communication in the presence of adversarial behavior. It is about constructing and analyzing protocols that prevent third parties or the public from reading private messages. 
29. **Hypervisor** - It is a type of computer software, firmware or hardware that creates and runs virtual machines.

| Type I  | Type II |
| ------------- | ------------- |
| Native (bare metal)  | Hosted  |
| Directly on hardware and runs guest OS  | Runs on previously installed OS  |
| acts as light weight as it runs directly  | runs as software like other computer programs  |

29. **BareMetal**- Fresh Servers
30. **IAM** - Identity and access management
31. **nginx** - proxy server

32. **apache** - client server - uses httpd(d stands for dameon:continuously runs in background) that creates a pool of child processes or threads to handle requests.
33. **ASICs** - *(Application-Specific Integrated Circuits)* are computer chips that combine several different circuits all on one chip – it's a "system-on-a-chip" (SoC) design – allowing it to be custom programmed to combine several related functions that together carry out a specific overall task.
34. **UDP** - User Datagram Protocol, is a communication protocol used across the Internet for especially time-sensitive transmissions such as video playback or DNS lookups
35. **Packets** - a packet is a small segment of a larger message. Data sent over computer networks, such as the Internet, is divided into packets, recombined by te client computer
36. **Load Balance** - Load balancing is the method of distributing network traffic equally across a pool of resources that support an application.
37. **Server** - a computer program or device that provides a service to another computer program and its user, also known as the client.
- *Client Server* - A relationship in which one program, the client, requests a service or resource from another program, the server. **EX** - email, network printing, and the World Wide Web
- *Proxy Server* - A server that acts as an intermediary between the request made by clients **EX** - an HTTP proxy intercepts web access, and an SMTP proxy intercepts email

| Forward Proxy  | Reverse Proxy |
| ------------- | ------------- |
| It accepts connections from computers on a private network and forwards those requests to the public internet.   | Public access point for users to access data and information that is stored on servers that reside in a private, isolated subnet.  |
| Acts as single point of exit for subnet users who want to access resources outside of their private network.  | Acts as a single point of entry for external systems to access resources on a private subnet.  |
| Banks and insurance companies, and government agencies use it to protects corporate computers from outside attacks from this isolation  | Large websites and content delivery networks to balance the load between internal servers.  |

<img width="770" alt="Screenshot 2023-09-09 184801" src="https://github.com/mohitpoonia/mohitpoonia/assets/142895350/c6604204-12f3-4cc4-955e-b5fc58581324">


# ▶️Cloud Concepts
### Use Cases
1. Fraud Detection and Prevention
2. Personalized Treatments
3. Online Games
### Some Terms related to Cloud Computing
- Infrastructure as a Service **(IaaS)** : Amazon Web Services (AWS), Microsoft Azure, Google Compute Engine (GCE), IBM Cloud
- Platform as a Service **(PaaS)** :  Windows Azure, Google App Engine, AWS Lambda, Azure Functions.
- Software as a Service **(SaaS)** : Salesforce, Shopify, MailChimp, Dropbox, Hubspot
### Types of Cloud
1. Public Cloud - Anywhere on the internet : Cloud Service Provider provides the infrastructure(AWS, Azure) :: *Multi-Tenant*
2. Private Cloud - Inside the Organisation Network : Organisation solely responsible for infra :: *Single-Tenant*
3. Hybrid Cloud - Inside Organisation or Anywhere on te internet :: *Multi Tenant + Single Tenant*
## Characterics of Cloud Computing
- On demand Self-service
- Broad Network Access
- Resource Pooling
- Rapid Elasticity
- Measured Service
### Benefits of CLoud Computing
1. pay as you go
2. scalability
3. Accessibility
4. Cost effective
5. Go global in minutes
### OOPs Concept
![xa drawio](https://github.com/mohitpoonia/mohitpoonia/assets/142895350/abde0c1e-9e1e-4765-8a40-d2ef0c4a0b4e)

# ▶️Often used Linux Commands
1. **ls** - List directory content
2. **cd** - Change directory
3. **mkdir** - Make a new directory
4. **rm**- Remove Files/Directories
5. **mv** - Move or rename files or directories
6. **chmod** - Change files or Directories permission 
- chmod *777* command gives read, write and execute permissions
7. **cp** - Copy Files or Directories
8. **chown** - Change file or directory ownership
9. **top** - Display system process
10. **cat** - Concatenate and siplay files
11. **tar** - Create or extract archieve files
12. **ps** - Display running Processes
13. **kill** - Terminate Processes
14. **pwd** - Present working Directory
15. **sudo** - Execute Command as a superuser
16. **ping** - Test Network Connectivity b/w hosts
17. **du** - Estimate File Space Usage
18. **vi & nano** - File editor
19. **touch** - Create new File
# Computing Basics
1. **SSL Certificate** - Certificate which is statndard for all the domains *X.509*
   - Certifying Authority like Godaddy, Hostinger, Namecheap
   - Signing Certificate Algo is Cryptography : RSA, Elliptic Curve
- *OpenSSL* is an open-source command line tool that is commonly used to generate private keys, create CSRs, install your SSL/TLS certificate, and identify certificate information. 
2. **NAT** - Network Address Translation : Convert Private IP Address to public IP Address & vice-versa
3. **Router** - a device that connects two or more packet-switched networks or subnetworks.
4. **Compiler** - computer software that translates (compiles) source code written in a high-level language (e.g., C++) into a set of machine-language instructions that can be understood by a digital computer's CPU
5. **Interpreter** - A computer program that directly executes instructions written in a programming or scripting language, without requiring them previously to have been compiled into a machine language program.
6. **Scheduling** - It is the action of assigning resources to perform tasks. The resources may be processors, network links or expansion cards. The tasks may be threads, processes or data flows.

# ▶️Ubuntu Directories
- */bin* - user Binaries
- */sbin* - System Binaries
- */etc* - Configuration Files
- */dev* - Device Files
- */proc* - Process Information
- */var* - Variable Files
- */tmp* - Temporary Files
- */usr* - User Programs
- */home* - Home Directories
- */boot* - Boot Loader Files
- */lib* - System Libraries
- */opt* - Operational Application
- */mnt* - Mount Directory
- */media* - Removable Devices 
- */srv* - Service Data
## Blockchain
- Satoshi Nakamoto is the creator of Blockchain
- Blockchain technology is an advanced database mechanism that allows transparent information sharing within a business network.
- Blockchain helps in the verification and traceability of multistep transactions needing verification and traceability.
- Blockchain uses the three principles of cryptography, decentralization, and consensus to create a highly secure underlying software system that is nearly impossible to tamper with.
#### Currency
- Cryptocurrencies are digital currencies that use cryptography to secure and verify transactions in a network. Cryptography is also used to manage and control the creation of such currencies : *Bitcoin and Ethereum*
- Virtual currencies are a form of digital currency. They are issued by private parties, such as a group of developers or organizations, and are intended only for online use
 - *ICO* - An initial coin offering (ICO) is the cryptocurrency industry's equivalent of an initial public offering (IPO) used in order to raise capital

38. ▶️**Types of Computing**
- *Desktop Computing* - Desktop computing devices include workstations, personal computers, and network computing devices. A workstation or desktop personal computer does not have many resource restrictions when connected to a fixed network.
- *Centralised Computing* - System where all processing and data storage is handled by a single, central device or system which is responsible for processing all requests and managing all data, and all other devices in the system are connected to it.
  - Used in Traditional Mainframe (data repository, or hub connected through terminals) systems, Network Servers
- *Decentralised Computing* - In decentralized systems, every node makes its own decision. The final behavior of the system is the aggregate of the decisions of the individual nodes. There is no single entity that manages request
  - Blockchain, Decentralized databases – Entire databases split into parts, Cryptocurrency
- *Distributed Computing* - It is a collection of computer programs that utilize computational resources across multiple, separate computation nodes to achieve a common, shared goal. It relies on separate nodes to communicate and synchronize over a common network.
  - SOA-based systems(service-oriented-architecture) {CRM, ERP}, Multiplayer online games
- *Edge Computing* - It allows smart applications and devices to respond to data almost at the same time which is important in terms of business ad self-driving cars.It has the ability to process data without even putting it on a public cloud, this ensures full security.
  - Use Cases - In-hospital patient monitoring, Virtualised radio networks and 5G (vRAN), Cloud gaming
39. **Port Forwarding** - It allows computers or services in private networks to connect over the internet with other public or private computers or services.

<img width="954" alt="imgonline-com-ua-twotoone-j5RFVzct9Fdm6jp" src="https://github.com/mohitpoonia/mohitpoonia/assets/142895350/a30d5771-4f90-404f-8ffc-cab40cc8f98a">

39. **Cluster** - a group of inter-connected computers or hosts that work together to support applications and middleware (e.g. databases). each computer/host referred as node and each node is assigned same task which help in efficiency and load balancing
40. **Design Patterns** - A design pattern systematically names, motivates, and explains a general design that addresses a recurring design problem in object-oriented systems. It describes the problem, the solution, when to apply the solution, and its consequences. It also gives implementation hints and examples.
41. **REST API**
    
| REST is a set of architectural constraints, not a protocol or a standard. API developers can implement REST in a variety of ways.|
| ------------- |
| When a client request is made via a RESTful API, it transfers a representation of the state of the resource to the requester or endpoint. This information, or representation, is delivered in one of several formats via HTTP: JSON (Javascript Object Notation), HTML, XLT, Python, PHP, or plain text.|

42. **HTTPS 1** vs **HTTP 2**

  | HTTP/1.1  | HTTP/2 |
  |--------------|--------------|
| It works on the textual format.	 | It works on the binary protocol. |
| There is head of line blocking that blocks all the requests behind it until it doesn’t get its all resources.	 | It allows multiplexing so one TCP connection is required for multiple requests. |
| It uses requests resource Inlining for use getting multiple pages	  | It uses PUSH frame by server that collects all multiple pages  |
| It compresses data by itself.	  | It uses HPACK for data compression. |

43. **etcd** - It is an open source distributed key-value store used to hold and manage the critical information that distributed systems need to keep running. Most notably, it manages the configuration data, state data, and metadata for Kubernetes, the popular container orchestration platform.
44. **Ceph** - Ceph is an open-source software-defined storage platform that provides object, block, and file storage. It's designed to be self-healing and self-managed, and it can run on any hardware Ceph is maintained by RedHat. It's built on a common distributed cluster foundation. The clusters are designed to run on any hardware with the help of an algorithm called CRUSH (Controlled Replication Under Scalable Hashing).
45. **OvS** - Open vSwitch (OVS) is an open-source, virtual multilayer switch that provides a switching stack for hardware virtualization environments. OVS is a software switch that turns a Linux server into a switch. It's designed to enable network automation through programmatic extension.
46. **Rancher** - Rancher is an open-source software platform that allows organizations to run containers in production. Rancher can be used to:
- Run containers in production
- Operate Docker in production
- Deploy and run clusters anywhere and on any provider
- Divide a cluster into separate "virtual clusters" that each have their own access control and resource quotas
47. **Cilium** - Cilium is a highly scalable Kubernetes Container Network Interface (CNI). It provides cloud-native networking connectivity, security, and observability for container-based workloads, such as in Kubernetes and Docker. It provides visibility and control over network traffic, and offers advanced security features.
48. **Proxmox** - Proxmox Virtual Environment (Proxmox VE) is an open-source server management platform for enterprise virtualization.Proxmox VE offers the ability to: 
- Manage two virtualization technologies: KVM for virtual machines and LXC for containers
- Manage virtual server (VPS) technology with the Linux OpenVZ and KVM technologies
- Install different operating systems on a single computer or a cluster built by grouping computers together
49. **XEN** - Xen is a free and open-source hypervisor that allows multiple operating systems to run on the same hardware at the same time. Xen inserts a virtualization layer between the system hardware and the virtual machines. Xen is a type-1 hypervisor, which means it can be installed directly on hardware without the need for a host operating system. It controls, monitors, and manages hardware, peripheral, and I/O resources directly.
  - AWS is believed to be the only major service provider working at scale that uses Xen.

**APIs**
![6b437484-1fd8-4b59-ba05-46bb3352b053_2904x2559](https://github.com/mohitpoonia/mohitpoonia/assets/142895350/80e009f8-092b-4c12-883c-b2513eb92b78)

**LXC** - 
LXC stands for Linux Containers. It's an open-source container platform that allows users to create and run multiple isolated Linux virtual environments (VEs) on a single control host. LXC uses a single Linux kernel to run these isolated systems, or containers. 

50. **GreenField** vs **Brownfield Application**

| Greenfield | Brownfield|
|--------------|--------------|
| greenfield applications are applications that are not yet made or are in the early stages of development | brownfield applications are existing applications |
| Greenfield applications are new developments with no prior work done that poses constraints on the solution. | Brownfield applications are existing applications that utilize previously developed land to make better use of existing sites.  |

51. **Web3 Decentralisation** - Web3 is a decentralized version of the internet that allows users to own their own data. It's also known as the decentralized web or the third generation of the internet. 
- Blockchain, which is a decentralized digital ledger of transactions that uses cryptography to secure and verify each transaction
- Decentralized applications (dApps), which are interconnected blockchain-based applications that enable users to interact with each other without the need for intermediaries
Web3 is designed to be: 
- Permissionless (no centralized gatekeepers)
- Trustless (no need to place trust in a third party)
- Open to all (little-to-no censorship of individuals/ideas)
52. **Digital Identities** - Digital identities allow people to identify themselves and facilitate transactions in the digital world. They can be set up once and reused whenever someone is asked to prove their identity. 
Digital identities can raise important questions about: 
- The balance between privacy and security
- The rights of individuals to control their own data
- The impact on social relationships
53. **VectorDB** - VectorDB is a Python package that stores and retrieves text using chunking, embedding, and vector search techniques. It's designed for use cases where low latency is essential. 
VectorDB provides an easy-Hyper-converged infrastructure (HCI) is a software-defined IT infrastructure that combines servers and storage into a single cluster. HCI uses intelligent software to create flexible building blocks that replace legacy infrastructureto-use interface for: 
- Saving, searching, and managing textual data with associated metadata
- Managing, querying, and retrieving high-dimensional vector data efficiently
- Working with vector data just like how you work with regular Python objects
- A comprehensive suite of CRUD (Create, Read, Update, Delete) operations
- Robust scalability options
54. **eBPF** - BPF stands for Extended Berkeley Packet Filter. It's a lightweight virtual machine that runs sandboxed programs in a Linux kernel. eBPF allows programs to run without modifying the kernel source code or installing any additional modules. 
It's used to: 
- Extend the capabilities of the kernel
- Control, monitor, and analyze system behavior
- Attach small, efficient programs to various kernel hooks
- Run programs upon triggering of an event
55. **HCI** - Hyper-converged infrastructure (HCI) is a software-defined IT infrastructure that combines servers and storage into a single cluster. HCI uses intelligent software to create flexible building blocks that replace legacy infrastructure.
  HCI includes: 
- Virtualized computing (a hypervisor)
- Software-defined storage
- Virtualized networking (software-defined networking)
- Direct-attached storage media (HDDs, SSDs, NVMe)
HCI unifies the datacenter stack elements into an abstracted layer of available IT resources.
56. **DHCP** - Dynamic Host Configuration Protocol (DHCP) is a network protocol that automatically assigns IP addresses to devices on a network. DHCP uses a client-server architecture to provide configuration information such as: IP address, Default route, DNS server addresses, Subnet mask, Default gateway. 
57. **Terraform** - Terraform is an open-source tool that automates infrastructure tasks. It's used by DevOps teams to provision cloud resources.
Terraform allows users to: 
- Build infrastructure through code
- Manage infrastructure, platforms, and services
- Build, change, and version infrastructure safely and efficiently
- Automatically manage configuration, plugins, and state
- Add all config files into a VCS to safely manage and track changes
### ▶️ NETWORK
58. **TAP** - A network tap (TAP) is a hardware device that allows you to monitor and access data that is transmitted over a network. TAP stands for "Traffic Access Point" or "Test Access Point".
Network taps are typically used in network security applications to: 
- Monitor traffic
- Identify malicious activity or security threats
- Enable monitoring and analysis without interrupting data transmission
59. **CNI** - Container Network Interface (CNI) is a framework that configures networking resources dynamically.It enables communication and connectivity between containers and external networks. 
CNI uses a group of libraries and specifications written in Go. The plugin specification defines an interface for: 
- Configuring the network
- Provisioning IP addresses
- Maintaining connectivity with multiple hosts
60. **Flannel** - Flannel is an open source CNI plugin that: 
- Creates and manages subnets
- Assigns a separate subnet to each Kubernetes cluster node
- Assigns an internal IP address
61. **Overlay** - Overlay networking is a method of using software to create layers of network abstraction on top of a physical network. These layers can be used to run multiple separate, virtualized network layers.
The purpose of an overlay network is to: 
- Add missing functionality without a complete network redesign
- Provide new applications or security benefits
- Deploy flexible services based on ever-changing connectivity and mobility demands of the endpoints and applications
62. **Tunnel** - a tunnel is a connection between two computer networks that allows data to be sent from one network to another through an encrypted link. Tunneling works by encapsulating packets, or wrapping packets inside of other packets. 
Tunneling is used to: 
- Transfer data securely from one network to another
- Transport data across a network using protocols that are not supported by that network
- Allow private network communications to be sent across a public network, such as the Internet
- Have data authenticated, or authenticated and encrypted
63. **TUN** - TUN stands for network TUNnel. It's a virtual interface that simulates a network layer device. TUN operates on layer 3 of the OSI model
TUN can tunnel data packets of varied nature, including: 
- Raw TCP - Raw TCP/IP is an insecure communication protocol. It's used to: 
  - Open a TCP socket-level connection over Port 9100
  - Stream a print-ready file to the printer input buffer
- UDP - a communication protocol used across the Internet for especially time-sensitive transmissions such as video playback or DNS lookups.
- SCTP -  a transport-layer protocol that ensures reliable, in-sequence transport of data
- Encapsulated packets such as PPP, PPTP, AH/IPSEC
64. **OSI Model**
  ![osi model](https://github.com/mohitpoonia/mohitpoonia/assets/142895350/fd698805-5ade-4644-b014-ca4c762b3fc6)
65. **Load Balancing Algorithms**
  ![lb-algorithms](https://github.com/mohitpoonia/mohitpoonia/assets/142895350/4432276d-5f25-4630-a6e0-ac69a6112167)
66. **KubeVirt** - KubeVirt is an open-source project that allows virtual machines (VMs) and containerized workloads to coexist within Kubernetes clusters.
  KubeVirt allows you to: 
- Provision, manage, and control VMs simultaneously with container resources
- Integrate with existing Kubernetes deployments seamlessly
- Run VMs within regular Kubernetes pods
- Access standard pod networking and storage
- Manage VMs using standard Kubernetes tools such as kubectl
- Run full virtual machines on Kubernetes alongside regular containers
