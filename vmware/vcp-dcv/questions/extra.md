What does the status "Upgrade Available" indicate for VMware Tools in a virtual machine?

- [x] The version of VMware Tools installed is older than the version available on the ESXi host.
- [ ] The version of VMware Tools installed is newer than the version available on the ESXi host.
- [ ] The status of VMware Tools has not been checked for the virtual machine.
- [ ] The virtual machine does not have VMware Tools installed.


What does validating an image ensure?

- [ ] Version compatibility with vSphere Lifecycle Manager
- [x] Completeness of the image
- [ ] Removal of conflicting components
- [ ] Compatibility with ESXi hosts


What is the purpose of managing clusters with images in vSphere?

- [ ] To install firmware and driver bundles
- [ ] To create custom OEM images
- [ ] To customize the ESXi base image
- [x] To standardize the software on ESXi hosts


From the main menu, which option should you select to access vSphere Lifecycle Manager?

- [x] Lifecycle Manager
- [ ] Third-Party Software Management
- [ ] ESXi Host Upgrades
- [ ] VMware Tools and VM Hardware


You should plan the VMware Tools upgrade during your maintenance window, especially if a reboot of the VM is required after the upgrade completes. True or False?
- [x] True
- [ ] False


What can you do if some VMware products are undetected in the interoperability report?

- [x] Modify the product list manually
- [ ] Refresh the page
- [ ] Upgrade vCenter to the latest version
- [ ] Export the report in CSV format


Which of the following features does the NFS 4.1 client offer over NFS 3?

- [ ] Native multipathing and session trunking
- [ ] Kerberos authentication
- [ ] Stateful locks with share reservation using a mandatory locking semantic
- [x] All of the above


What NFS protocol versions are supported by vSphere v8?

- [ ] NFS 2 and NFS 4
- [x] NFS 3 and NFS 4.1
- [ ] NFS 3.1 and NFS 4
- [ ] NFS 4 and NFS 5.1


Which of the following is an authentication method supported by ESXi for iSCSI initiators and targets?

- [x] CHAP
- [ ] LDAP
- [ ] SAML
- [ ] QAuth


What is the software iSCSI initiator and how does it communicate with the iSCSI storage system?

- [ ] The software iSCSI initiator is a storage device that contains one or more LUNs and storage processors, and it communicates with the ESXi host over a TCP/IP network
- [x] The software iSCSI initiator is a software-based component that resides in the ESXi host and transmits SCSI commands over the IP network to the iSCSI target
- [ ] The software iSCSI initiator is a Fibre Channel switch that connects the host to the storage array using the Fibre Channel protocol
- [ ] The software iSCSI initiator is a software-based iSCSI HBA that resides in a NIC and transmits SCSI commands over the IP network to the iSCSI target


Which of the following is storage shared over standard TCP/IP networks at the file system level?

- [x] NAS
- [ ] iSCSI
- [ ] FC
- [ ] FCoE


What is a datastore and how does it relate to virtual machine files?

- [ ] A network protocol used to access virtual machine files
- [x] A logical container for holding virtual machine files that hides the specifics of the underlying storage device
- [ ] A physical container for holding virtual machine files
- [ ] A virtual machine file format for storing data on a storage device


An administrator directly change the contents of a subscribed library. True or False?
Question 13 options:
- [ ] True
- [x] False


What is the purpose of swap files (.vswp) in a VMware virtual machine?

- [ ] To store the VMs BIOS or EFI settings
- [ ] To archive old log entries
- [ ] To replace the VM configuration file if it is converted to a template
- [x] To reclaim memory during periods of contention


What type of templates can be synchronized between a published and subscribed library?

- [x] Only OVF templates
- [ ] Only VM templates
- [ ] Both OVF and VM templates
- [ ] None of the above


Can a published library publish both VM templates and OVF templates to its subscribers?

- [x] Yes, all templates are synchronized automatically
- [ ] No, only OVF templates can be published
- [ ] No, only VM templates are pushed to the subscriber
- [ ] Yes, but only OVF templates are synchronized in the subscribed library


What is the file extension of the configuration file for a VMware virtual machine?

- [ ] .nvram
- [ ] .vmdk
- [x] .vmx
- [ ] .vwsp


Can you add or remove VMCI devices?

- [x] No, you cannot add or remove VMCI devices
- [ ] Yes, you can add and remove VMCI devices
- [ ] It depends on the virtualization platform
- [ ] Only the system administrator can add or remove VMCI devices


Virtualized Storage is a partition on the physical drive that is created, forming a space called a Logical Unit Number (LUN).

- [x] True
- [ ] False


Which are the main components of NFS?[Choose 3]

- [x] Client
- [x] Server
- [x] Protocol
- [ ] Operating systems


File Storage concept means Data is bundled together with its metadata (information such as date created, size, and author) and a unique identifier.

- [ ] True
- [x] False


vSAN integration into the ESXi hypervisor simplifies management and removes the need for dedicated hardware and complicated networking.

- [x] True
- [ ] False


APIs Can serve as software intermediaries between the user interface and the server database or website.

- [x] True
- [ ] False


The Virtual Data Plane is delivered through vSAN x86 for hyper-converged storage, or through vSphere virtual volumes for external storages like SAN and NAS.

- [x] True
- [ ] False


Type 2 Hypervisor is called Bare Metal hypervisor like VMware ESXi.

- [ ] True
- [x] False


Types of VMs Virtual Networks are ---------------: [Choose 3]

- [x] Host-only Network
- [x] Bridged Network
- [ ] Bridged Host
- [x] NAT


vMotion is used to move offline virtual machines from one ESXi host to another ESXi host without service interruption (Offline migration only).

- [ ] True
- [x] False


How do VMs access data center storage? [Choose 2]

- [ ] VMs are stored as VMDK (.vmdk) files on Hard disk
- [x] VMs are stored as VMDK (.vmdk) files on datastore
- [ ] VM configuration files (VM settings) are stored as TXT (.txt) files
- [x] VM configuration files (VM settings) are stored as VMX (.vmx) files


With vMotion, you can. [Choose 2]

- [ ] Move offline virtual machines from one ESXi host to another ESXi host without service interruption (offline migration only)
- [x] Move running virtual machines from one ESXi host to another ESXi host without service interruption (live migration)
- [ ] Decreases availability of data and computing resources
- [x] Increase the availability of data and computing resources


The main components of ESXi are ---------: [Choose 2]

- [x] Unix Microkernel
- [ ] Linux Microkernel
- [x] VMware Kernel (VMkernel)
- [ ] VMware OS (VMOS)


How many flash storage devices needed per disk group in Virtualized Storage Area Networks? [Choose 1]

- [ ] at least two
- [x] at least one
- [ ] at least three
- [ ] at least four


How many industry-leading solutions are presented by VMware's HCI? [Choose 1]

- [ ] One
- [ ] Two
- [x] Three
- [ ] Four


Which are the main types of Local Disk Storage? [Choose 3]

- [x] Hard Disk Drives (HDDs)
- [x] Solid State Drives (SSDs)
- [ ] Virtual Volumes (vVOL)s
- [x] Optical Disk Drives (ODDs)


For Storage Concepts in the Data Centers, a complex system or piece of software, focusing on the most relevant details and hiding what can be ignored is called: [Choose 1]

- [ ] Snapshot
- [x] Abstraction
- [ ] Deploy
- [ ] Policy


Virtual Data services applied by the Virtual Data Plane may include-----------. [Choose 1]

- [ ] Replication
- [ ] Snapshots
- [ ] Deduplication
- [x] All of the above


How many types of objects the Virtual Machines contain? [Choose 1]

- [ ] Three
- [ ] Four
- [x] Five
- [ ] Six


VMs can be exported and moved to other hosts.

- [x] True
- [ ] False


ESXi is type 2 Hypervisor.

- [ ] True
- [x] False


Examples of VM files include -----------: [Choose 3]

- [x] <vmname>.log
- [ ] <vmname>.docx
- [x] <vmname>.vmdk
- [x] <vmname>.vmx


In Thin provisioning, Disk space is strategically pre-allocated to a server, or a VM.

- [ ] True
- [x] False

What is Type 1 Hypervisor? [Choose 1]

- [ ] Hosted hypervisor (VMware Workstation)
- [x] Bare metal hypervisor (VMware ESXi)
- [ ] Application software tells your system to execute a task you want
- [ ] System software is necessary for hardware to function


What is a Hypervisor? [Choose 2]

- [x] Software installed on top of hardware that created virtualization layer
- [ ] Operating system controls the hardware
- [x] Application software tells your system to execute a task you want
- [ ] Hosts VMs


What information can be identified about a physical switch using CDP and LLDP in vSphere?

- [ ] None of the above
- [ ] Number of VLANs and associated ports
- [x] Switch name, port number, and port speed/duplex settings
- [ ] Switch IP address and MAC address


What is a trunk port in a vSphere networking environment?

- [ ] A virtual switch port that connects to the physical network
- [x] A port on a physical Ethernet switch that sends and receives packets tagged with a VLAN ID
- [ ] A soft ware-configured broadcast domain
- [ ] A logical network that is not based on the physical topology


What is the purpose of a failover order in NIC teaming?

- [x] To determine which NICs are active during normal operations and in the event of a failover
- [ ] To provide network security for the virtual switch
- [ ] To increase the bandwidth of the virtual switch
- [ ] To determine how network traffic is distributed between physical NICs


Which method can detect failures in a NIC team that link-status monitoring alone cannot?

- [x] Beacon probing
- [ ] Spanning Tree Protocol monitoring
- [ ] VLAN membership monitoring
- [ ] Configuration monitoring


What is the purpose of the vSphere Replication service?

- [ ] To handle incoming replication data on the target replication site
- [x] To handle outgoing replication data from the source ESXi host to the vSphere Replication server
- [ ] To enable the host to advertise itself as the network connection for vSphere vMotion traffic
- [ ] To activate Fault Tolerance logging on the host


What does the Burst size parameter determine when shaping traffic on an ESXi host?

- [ ] The minimum number of kilobytes to allow in a burst, preventing a port from transmitting data too quickly
- [ ] The average number of kilobits per second to allow across a port
- [ ] The maximum number of kilobits per second to allow across a port when sending a burst of traffic
- [x] The maximum number of kilobytes to allow in a burst, allowing a port to temporarily transmit data at a faster speed


Can the NTP and PTP services run simultaneously on an ESXi host?

- [ ] Yes, they can run simultaneously
- [ ] It depends on the hardware configuration
- [x] No, only one of them can be active at a time
- [ ] The ESXi host does not support NTP or PTP services


What type of protocol is NTP?

- [ ] Peer-to-peer protocol
- [ ] Multicast protocol
- [x] Client-server protocol
- [ ] Broadcast protocol


How do virtual machines benefit from time synchronization with the ESXi host?

- [ ] Reduced memory usage
- [ ] Enhanced network connectivity
- [x] Synchronized time for applications
- [ ] Improved storage performance


What does an ESXi host synchronize its time with when configured as an NTP client?

- [ ] A virtual machine running an NTP server software
- [ ] Another ESXi host on the same network
- [x] An NTP server on the Internet or your corporate NTP server
- [ ] A DHCP server providing time synchronization


Which protocol does an ESXi host use for time synchronization as an NTP client?

- [ ] TCP over port 80
- [x] UDP over port 123
- [ ] TCP over port 123
- [ ] UDP over port 80


SSH should only be activated on an ESXi Host for troubleshooting and maintenance purposes and then be immediately deactivated when finished. True or False?

- [x] True
- [ ] False

    
When using the VAMI to set up Log File Forwarding to a remote host, you specify forwarding configuration information for the remote syslog server such as the Server Address, Protocol, and Port. True or False?

- [x] True
- [ ] False


What is the vCenter Serve Appliance?

- [ ] A prepackaged Linux-based VM that is used as a service of vCenter Server, allowing for easier access to it.
- [x] A prepackaged Linux-based VM that is optimized for running vCenter Server and associated services.
- [ ] A prepackaged Windows-based VM that is used as a service of vCenter Server, allowing for easier access to it.
- [ ] A prepackaged Windows-based VM that is optimized for running vCenter Server and associated services.


You have just finished installing a vCenter Server instance and want to assign a new license to it. You have already entered the 25-character license key into your vCenter License Service through the vSphere Client. How do you assign the license key to the vCenter Server instance asset?

- [x] In the vSphere Client, select the vCenter Server from the navigation pane, select "Configure" from the ribbon, select "Licensing" under "Settings" in the middle pane, and then select "ASSIGN LICENSE". From there you select the License Key you entered earlier.
- [ ] You have already entered the License Key into the vCenter Server system, so there is no need to assign it to anything.
- [ ] In the VMware Host Client, right-click the vCenter Server VM from the navigation pane, select "Settings" from the dropdown menu, open the "Licensing" dropdown, and then select "ASSIGN LICENSE". From there you select the License Key you entered earlier.
- [ ] In the VAMI, select "Services" in the navigation pane, select "License Service" from the list, select "EDIT", and then select "ASSIGN LICENSE", then select the vCenter Server. From there you select the License Key you entered earlier.


Using the vCenter Server GUI Installer to deploy vCenter Server, what are some steps that you take in Stage 1: Deploy vCenter Server? Select all that apply.

- [x] Define networking settings.
- [x] Select compute size, storage size, and datastore location (thin disk).
- [x] Connect to the target ESXi host or vCenter Server system.
- [x] Define the vCenter Server Appliance name and root password.
- [x] Accept the EULA.


The virtual provisioning X agent (vpxa) acts as an intermediary between what two deamons to provide communication between vCenter Server and an ESXi Host?

- [ ] vpxb and hosta
- [ ] vpxb and vpxc
- [x] vpxd and hostd
- [ ] hostd and servd


The vCenter Server Appliance package contains what software?

- [ ] vSphere
- [ ] ESXi
- [x] vCenter Server services
- [x] Photon
- [ ] Postgre database
- [ ] SQL server
- [x] PostgreSQL database


What determines whether vSphere DRS makes migration recommendations or automatically places VMs on hosts?

- [ ] The cluster's overall DRS score
- [x] The automation level
- [ ] The need for VM rebalancing across hosts
- [ ] The power-on process of the VM


For CPU usage, the VM boxes are not color-coded because the relationship between consumed memory and entitlement is often not easily categorized. True or False?

- [ ] True
- [x] False


Which vSphere HA setting lets you customize the restart priority for individual VMs?

- [x] VM-Level Restart Priority
- [ ] Default VM Restart Priority
- [ ] Per VM Restart Policy
- [ ] Default VM Restart Policy


You click the "RUN DRS NOW" button to apply all DRS recommendations. True or False?

- [ ] True
- [x] False


Which of the following metrics are displayed on the VM DRS Score page for powered-on VMs in vSphere?

- [ ] Active CPU
- [ ] Used CPU
- [ ] CPU Readiness
- [x] All of the above


What is the purpose of vSphere Fault Tolerance?

- [ ] Data replication between hosts
- [ ] Load balancing between hosts
- [x] Providing fault-tolerant protection for mission-critical VMs
- [ ] Streamlining VM management tasks


What is Enhanced vMotion Compatibility in vSphere, and what does it do?

- [ ] It ensures that all hosts in a cluster present the same CPU feature set to VMs, even if the CPUs on the hosts differ
- [ ] It allows you to migrate VMs among CPUs that otherwise are considered incompatible
- [ ] It enforces vSphere vMotion compatibility among all hosts in a cluster by forcing hosts to expose a common set of CPU features (baseline) to VMs
- [x] All of the above


What mechanism does vSphere provide to allow less, more, or equal access to a defined resource?

- [ ] Resource contention
- [x] Resource allocation
- [ ] Resource overcommitment
- [ ] Resource reservation


What are some use cases for cross vCenter migrations with vSphere vMotion?

- [x] Balancing workloads across clusters and vCenter instances in the same site or in another geographical area
- [ ] Migrating VMs only between development environments
- [ ] Moving VMs between hosts in the same cluster
- [ ] Moving VMs from a public cloud to an on-premises vSphere data center


What is the purpose of the provisioning TCP/IP stack?

- [ ] Provides networking support for the management traffic between vCenter and ESXi hosts
- [x] Supports the traffic for VM cold migration, cloning, and snapshot creation
- [ ] Creates a custom TCP/IP stack to forward networking traffic through a custom application
- [ ] Supports the traffic for hot migrations of VMs


When running a virtual machine, the VMkernel creates a discrete addressable memory space for the VM. True or False?

- [ ] True
- [x] False


When you delete a snapshot one or more levels below the "You are here "level, it and all snapshots below it are committed to the parent snapshot. True or False?

- [ ] True
- [x] False

How does the VMware virtualization layer handle memory in a virtualized environment?

- [ ] It allocates memory pages to virtual machines on first access
- [ ] It handles address translation between virtual and physical memory spaces
- [x] It configures the virtual address space for each VM at startup
- [ ] It assumes ownership of all the physical memory in the system


Which of the following is a challenge posed by the traditional model of running physical servers in a data center?

- [ ] Efficient resource utilization
- [ ] Cost-effective infrastructure planning
- [x] Limited rack space
- [ ] Quick provisioning process


How does the hypervisor handle CPU resources when multiple VMs are running on an ESXi host?

- [ ] VMs compete for CPU resources without any intervention from the hypervisor
- [ ] CPU contention is resolved by adding more physical CPUs to the host
- [ ] Each VM is allocated a physical CPU for exclusive use
- [x] The host time slices physical processors across all VMs


How do VMs communicate with each other in a virtualized environment?

- [ ] Through the spanning tree protocol (STP)
- [ ] Through physical switches connected to the ESXi host
- [ ] By using additional hardware for virtual networking
- [x] By utilizing virtual switches on the same ESXi host


Which datastore type in vSphere uses a clustered fi le system optimized for virtual machines?

- [x] VMFS
- [ ] vSphere Virtual Volumes
- [ ] vSAN
- [ ] NFS


Where can you access the vSphere Client?

- [ ] https://<ESXi_FQDN_or_IP_Address>/ui
- [x] https://<vCenter_FQDN_or_IP_Address>/ui
- [ ] https://<ESXi_FQDN_or_IP_Address>:5480
- [ ] https://<vCenter_FQDN_or_IP_Address>:5480