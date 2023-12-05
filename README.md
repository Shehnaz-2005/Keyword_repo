# Keyword_repo
- Hey there! I'm Shehnaz and this is my keyword repository.
- This repo is to record new keywords and technical terms.

1. **CISC(Complex Instruction Set Computer)**- Intel, AMD - Closed source
2. **RISC(Reduced Instruction Set Computer)**- ARM - Closed source
3. **RISC-V**- Open source, based on RISC principles
4. **Kernel**- An operating system component which forms an interface between computer hardware and processes running on it
   - Kernel Space: Memory space to run kernel
   - User Space: Memory space to run user processes
   - Kernel programming languages: C, C++, RUST 
6. **ISA(Instruction Set Architecture)**- Defines how CPU is controlled by a software
7. **Cloud**- Shareable server over the internet
   - Private, Public cloud
   - Eg: AWS(Amazon Web Services), Microsoft Azure, GCP(Google Cloud Platform)
9. **ISP(Internet Service Provider)**
10. **Network- Internet(WAN), Intranet(LAN)**
11. **DNS(Domain Name Server)**- Maps Domain names with their IP addresses
12. **NIC(Network Interface Card)**- Hardware which connects a computer to a network
13. **IP(Internet Protocol)**- IPv4, IPv6
    - Private: 10., 172., 192. (LAN)
    - Public (WAN)
    - Local: 127.
14. **Bare Metal**- Fresh server without an OS/applications.
15. **Hypervisor**- A software which creates virtual machines
    - Type 1: Directly installed on bare metal
        - Eg: KVM(Kernel-based virtual machine)
    - Type 2: Installed over a host OS
        - Eg: VMware(closed source), Virtual Box(open source)
16. **Virtual Machine**- Acts like computer within a computer, virtualization of a computer.
17. **SSL(Secure Socket Layer)/Tunnel**- IP address + Port number
18. **Port Number**
    - FTP: 20, 21
    - HTTP: 80
    - HTTPS: 443
    - SMTP: 25
    - DNS: 53
    - Telnet: 23
      
19. **Seven Layers Of OSI**(Open Systems Interconnection)
 - L7 - Application
 - L6 - Presentation
 - L5 - Cryptography
 - L4 - Port Number(16 Bits)
 - L3 - IP Address (32 Bits) : Router
 - L2 - Hardware Address - NIC, MAC Address(48 Bits) : Ethernet :*SWITCH*
 - L1 - Digital (1 and 0)

20. **Switch** - connects devices in a network to each other, enabling them to talk by exchanging data packets. [ layer 2 of OSI]
21. **Virtual Machine** - created by using Hypervisor
22. **FPGA** - Field Programmable Gate Arrays  - Configurede after manufacturing
23. **TCP** - Transmission Control Protocol (TCP) is a standard that defines how to establish and maintain a network conversation by which applications can exchange data
24. **Debian** - Linux Software/OS Family
25. **VMware Workstation** - IT is a line of Desktop Hypervisor products which lets users run virtual machines, multiple OS
26. **VPN** - It establishes a digital connection between your computer and a remote server owned by a VPN provider, creating a point-to-point tunnel that encrypts your personal data, masks your IP address, and lets you sidestep website blocks and firewalls on the internet.
27. **Cryptography** - It is the practice and study of techniques for secure communication in the presence of adversarial behavior. It is about constructing and analyzing protocols that prevent third parties or the public from reading private messages. 
28. **Hypervisor** - It is a type of computer software, firmware or hardware that creates and runs virtual machines.
    - TYPE 1 : hypervisor runs directly on the host machine's physical hardware
    - TYPE 2 : hypervisor is typically installed on top of an existing OS.
    - **kvm** : Kernel-based Virtual Machine is a free and open-source virtualization module in the Linux kernel that allows the kernel to function as a hypervisor.
    - **xen** : Xen is a free and open-source type-1 hypervisor, providing services that allow multiple computer operating systems to execute on the same computer 
          hardware concurrently.

30. **BareMetal**- Fresh Servers
31. **IAM** - Identity and access management
32. **nginx** - proxy server
33. **apache** - client server - uses httpd(d stands for dameon:continuously runs in background) that creates a pool of child processes or threads to handle requests.
34. **OOPS** - "object oriented programming systum/structue", It is a programming model based on the concept of “objects,” which can contain data and code to manipulate that data.
 -The 4 pillers of **OOPS** :
  -**Encapsulation** :refers to the bundling of data, along with the methods that operate on that data, into a single unit.
  -**Abstraction**  :is the process of hiding the internal details of an application from the outer world.
  -**Inheritence** :one class inherits the attributes and methods of another class.
  -**Polymorphism** :is the method in an object-oriented programming language that performs different things as per the object's class, which calls it.
35. **Certificate Authority** - (CA) is a trusted entity that issues Secure Sockets Layer (SSL) certificates
36. **Certificate X.509** - The certificate is typically used to manage identity and security in computer networking and over the internet. For the internet, it is used in numerous protocols to ensure a malicious website doesn't fool a web browser. The X. 509 certificate is also used to secure email, device communications and digital signatures. 
  - (CA) ex:- GoDaddy , Let's Encrypt(open) etc.
  - Signing Certificate algorithm is Cryptography : RSA, Elliptic Curve
37. **Load Blanacer** - is a device that acts as a reverse proxy and distributes network or application traffic across a number of servers.
     -Algorithm is **ROUND ROBIN**
38. **Round Robin** - Round Robin is a CPU scheduling algorithm where each process is assigned a fixed time slot in a cyclic way. It is basically the preemptive version of First come First Serve CPU Scheduling algorithm. Round Robin CPU Algorithm generally focuses on Time Sharing technique.
39. **NAT** - ( network address translation ) It's a way to map multiple private addresses inside a local network to a public IP address before transferring the information onto the internet.<translates privete ip to publice ip and vica verse>
40. **ASIC** - ( App specific integrated ckt. ) is an integrated circuit chip customized for a particular use, rather than intended for general-purpose use, such as a chip designed to run in a digital voice recorder or a high-efficiency video codec. ex- ***BITCOIN MINER***
41. **containers** - Containers are packages of software that contain all of the necessary elements to run in any environment. In this way, containers virtualize the operating system and run anywhere, from a private data center to the public cloud or even on a developer's personal laptop.
42. **dockers** - Docker is a platform designed to help developers build, share, and run container applications. We handle the tedious setup, so you can focus on the code.
43. **LXC(liinux containers)** - Linux Containers is an operating-system-level virtualization method for running multiple isolated Linux systems on a control host using a single Linux kernel
44. **centralized computing** - Centralized computing is computing done at a central location, using terminals that are attached to a central computer.
45. **decentralized computing** - Decentralized computing is the allocation of resources, both hardware and software, to each individual workstation, or office location
46. **distributed computing** - Distributed computing is the method of making multiple computers work together to solve a common problem.
47. **pointers** - A pointer is a variable that stores the memory address of an object.
48. **API(Application Programming Interface)** - An application programming interface (API) is a way for two or more computer programs to communicate with each other.
                                               - rest api(representational state transfer architectural style)
                                               - grpc(Remote Procedure Calls)
                                               - graphql

49. **qiskit** - Qiskit helps users schedule and run quantum programs on a variety of local simulators and cloud-based quantum processors.
50. **AES ENCRYPTION** - The algorithm described by AES is a symmetric-key algorithm, meaning the same key is used for both encrypting and decrypting the data.
51. **PKI** - PKI, or public key infrastructure, encompasses everything used to establish and manage public key encryption.
52. **fourier series** - A Fourier series is an expansion of a periodic function f(x) in terms of an infinite sum of sines and cosines
53. **fast fourier transformer** - It converts a signal into individual spectral components and thereby provides frequency information about the signal
54. **NUMA(Non Uniform Memory Access)** - Non-uniform memory access (NUMA) is a computer memory design used in multiprocessing, where the memory access time depends on the memory location relative to the processor. Under NUMA, a processor can access its own local memory faster than non-local memory (memory local to another processor or memory shared between processors).
55. **eBPF** - Extended Berkeley Packet Filter (eBPF) is a Linux kernel technology enabling engineers to build programs that run securely in kernel space.
56. **k8s(Kubernetes)** - Kubernetes automates operational tasks of container management and includes built-in commands for deploying applications, rolling out changes to your applications, scaling your applications up and down to fit changing needs, monitoring your applications, and more—making it easier to manage applications.
57. **huge pages** - HugePages optimizes the memory configuration of the Linux operating system.
58. **openstack** - OpenStack is a free, open standard cloud computing platform. It is mostly deployed as infrastructure-as-a-service in both public and private clouds where virtual servers and other resources are made available to users.
    - ***neutron***- Neutron is an OpenStack project to provide "networking as a service" between interface devices (e.g., vNICs)
    - ***nova***- A compute service responsible for creating virtual machine instances and managing their life cycle, as well as managing the hypervisor of choice.
    - ***horizon**- A dashboard that creates a GUI for users to control the OpenStack deployment. This is an extensible framework to which vendors can add features
    - ***swift***- An object and Binary Large Object (BLOB) storage service responsible for managing object-based storage
    - ***Keystone***- An identity management system responsible for user and service authentication. 
59. **proxmox** - Proxmox VE is an open-source platform for server virtualization that offers robust capabilities for managing both KVM (Kernel-based Virtual Machine) hypervisors and Linux Containers (LXC). It's used by organizations large and small.
    
61. **HA(high availability)** - High availability (HA) is the ability of a system to operate continuously without failing for a designated period of time.

62. **IAC** - Infrastructure as code (IaC) uses DevOps methodology and versioning with a descriptive model to define and deploy infrastructure, such as networks, virtual machines, load balancers, and connection topologies.
    
63. **Brown field app** - Brownfield application development usually happens when you want to develop or improve upon an existing application, and compels you to work with previously created code.
    - ***monolithic*** - A monolithic application is built as a single unified unit
      
64. **Green field app** - Greenfield software development refers to developing a system for a totally new environment and requires development from a clean slate – no legacy code around.
      -***microservices*** - microservices architecture is a collection of smaller, independently deployable services.
      - For a lightweight application, a monolithic system often suits better. For a complex, evolving application with clear domains, the microservices architecture will be the better choice.
        
65. **backend** -- ***caching*** :
 Caching is the process of storing copies of files in a cache, or temporary storage location, so that they can be accessed more quickly.
 ex: redis(Redis is an open-source in-memory storage, used as a distributed, in-memory key–value database, cache and message broker, with optional durability.)
  -- ***VCS*** : Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time.
        ex: github , gitlab, bitbucket
  -- ***Database*** : -1. vector db (
Vector databases are typically used to power vector search use cases like visual, semantic, and multimodal search. More recently, they're paired with generative artificial intelligence (AI) text models to create intelligent agents that provide conversational search experiences.)
-2. sql(Structured query language (SQL) is a programming language for storing and processing information in a relational database.)
-3. NoSQL, (also referred to as “not only SQL”, “non-SQL”, is an approach to database design that enables the storage and querying of data outside the traditional structures found in relational databases. ex(mongodb))
    
66. **ddos** - A distributed denial-of-service (DDoS) attack is a malicious attempt to disrupt the normal traffic of a targeted server, service or network by overwhelming the target or its surrounding infrastructure with a flood of Internet traffic.
    
68. **cgroups** - cgroups (abbreviated from control groups) is a Linux kernel feature that limits, accounts for, and isolates the resource usage (CPU, memory, disk I/O, etc.) of a collection of processes.
    
70. **namespace** - create isolated environments for processes, separating them from the host system and other processes.
71. 
72. **borg** - Google created cgroups around 2006 to enable their Borg infrastructure, an app clustering system that is a spiritual precursor to Kubernetes.
    -***mesos*** : Apache Mesos is an open-source project to manage computer clusters.

73. **hyperscalers** - A hyperscaler is a type of large-scale data center that offers massive computing resources, typically in the form of an elastic cloud platform. Organizations use them to deploy and manage large-scale applications and services. ex: Amazon AWS, Microsoft Azure, Google GCP, Alibaba AliCloud, IBM, and Oracle
    
74. **HCI**- Hyperconverged infrastructure (HCI) is a software-defined, unified system that combines all the elements of a traditional data center: storage, compute, networking and management.
    
75. **pods** - Pods are the smallest deployable units of computing that you can create and manage in Kubernetes(specially made for deploying and managing containarized apps)
    
72.**kata containers**- Kata Containers is an open source community working to build a secure container runtime with lightweight virtual machines that feel and perform like containers, but provide stronger workload isolation using hardware virtualization technology as a second layer of defense.

73.**kubevirt** - KubeVirt is a virtual machine management add-on for Kubernetes. The aim is to provide a common ground for virtualization solutions on top of Kubernetes

74.**overlay network**- An overlay network is a network that is built on top of another network and is supported by its infrastructure. An overlay network decouples network services from the underlying infrastructure by encapsulating one network packet inside of another packet.

75.**underlay network** -the underlay network means all the physical infrastructure that enables frames and packets to be forwarded from o one point to another. In other words, we can understand the underlay networks as the “place” on which it is possible to connect and communicate with networking devices.

76.**cni**- CNI stands for container network interface and it's a specification to configure network interfaces in Linux containers. And it is concerned mainly with adding, connecting and deleting disconnecting containers to networks.

77.**funnel**-Flannel, a project developed by the CoreOS, is perhaps the most straightforward and popular CNI plugin available. It is one of the most mature examples of networking fabric for container orchestration systems, intended to allow for better inter-container and inter-host networking. Flannel is a simple and easy way to configure a layer 3 network fabric designed for Kubernetes.

78.**TUN && TAP**- In computer networking, TUN and TAP are kernel virtual network devices. Being network devices supported entirely in software, they differ from ordinary network devices which are backed by physical network adapters.
-***TUN*** :carries ip packets 
-***TAP*** :carries ethernet frames 

79.**veth**- The veth devices are virtual Ethernet devices. They can act as tunnels between network namespaces to create a bridge to a physical network device in another namespace, but can also be used as standalone network devices

80.**libvirt** - libvirt is an open-source API, daemon and management tool for managing platform virtualization.[3] It can be used to manage KVM, Xen, VMware ESXi, QEMU and other virtualization technologies. These APIs are widely used in the orchestration layer of hypervisors in the development of a cloud-based solution

81.**daemon** - Daemons are processes that run unattended. They are constantly in the background and are available at all times. Daemons are usually started when the system starts, and they run until the system stops. A daemon process typically performs system services and is available at all times to more than one task or user.

82.**ovirt** - oVirt is a free, open-source virtualization management platform. It was founded by Red Hat as a community project on which Red Hat Virtualization is based.

83.**virsh** - With virsh , you can control the state of a VM, edit the configuration of a VM or even migrate a VM to another host

84.**virt-manager** - Virtual Machine Manager allows users to
  - create, edit, start and stop VMs
  - view and control each VM's console
  - see performance and utilization statistics for each VM
  - view all running VMs and hosts, and their live performance or resource utilization statistics.
  - use KVM, Xen or QEMU virtual machines, running either locally or remotely.
  - use LXC containers
85. **Socket** - Software structure within a network node of a computer network that serves as an endpoint for sending and receiving data across the network
86. **MAC Address** - Media Access Control address is a unique identifier assigned for use as a network address in communications within a network segment.(48 bits)
87. **Protocol**- It is a standardized set of rules for formatting and processing data.
88. **Firmware** - It is a microcode or program that is embedded into the memory of hardware devices to help them operate
89. **TLS** - Transport Layer Security encrypts data sent over the Internet
90. **Cache** - a cache is a high-speed data storage layer which stores a subset of data (temporary mermory)
91. **STACK** - Stack is a linear data structure that follows a particular order in which the operations are performed. **LIFO** (Last In First Out)
92. **TLS(Transport Layer Security)**- A secure tunnel between user and web server.
93. **UDP(User Datagram Protocol)**- A communications protocol used to send messages to other hosts on an IP network. Within an IP network, UDP doesn't require prior communication to set up communication channels or data paths.
94. **IAM(Identity and Access Management)**-
