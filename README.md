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

# Cloud Concepts
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

# Often used Linux Commands
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

# Ubuntu Directories
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
