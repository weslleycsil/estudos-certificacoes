Which set of components are part of the Virtual Infrastructure Layer in the software-defined data center?

- [ ] vSphere, NSX, and Aria Automation
- [ ] Aria Operations, vSAN, and NSX
- [x] vSphere, vSAN, and NSX
- [ ] vSphere, vSphere Replication, and NSX


What is a difference between vSphere and vSphere+?

- [ ] vSphere allows access to cloud services from a cloud console.
- [ ] vSphere consists of vCenter and ESXi hosts.
- [x] vSphere+ manages on-premises workloads from a cloud console.
- [ ] vSphere+ lets you provision VMs for on-premises workloads.


Which two statements are true about vSphere virtualization? (Choose two)

- [ ] Virtual machines are encapsulated into files and are dependent on the physical hardware on which they run.
- [ ] Virtualization provides a one-to-one relationship between a physical computer and the software that it runs.
- [x] A virtualized host interacts with the hardware through a layer known as the hypervisor.
- [ ] Virtualization is software emulation that provides portability across different types of hardware.
- [x] Virtual machines share CPU, memory, network, storage, and GPU resources on a physical host


Which two tasks can you perform from the DCUI? (Choose two)

- [x] Enable SSH and ESXi Shell.
- [ ] Configure the host's firewall.
- [ ] Add the host's license.
- [x] Change the host's IP address.
- [ ] Configure NTP for the host.


Which two tasks are best practices for managing user accounts on ESXi hosts? (Choose two)

- [ ] Use only local user accounts to manage the ESXi hosts.
- [x] Strictly control root access to the ESXi hosts.
- [x] Manage ESXi hosts centrally using the vSphere Client.
- [ ] Connect to the ESXi host using SSH and perform daily operations as user root.
- [ ] Do not use Active Directory users with administrator privileges to manage ESXi hosts.


Which one of the following tasks do you perform during an interactive ESXi installation?

- [ ] Set the host name.
- [ ] Assign the IP address.
- [ ] Configure the memory size.
- [x] Set the root password.


Which two tasks are performed during Stage 1 of the vCenter Server Appliance installation? (Choose two)

- [x] Define networking settings for the appliance.
- [ ] Create a vCenter Single Sign-On domain.
- [ ] Join the Customer Experience Improvement Program.
- [ ] Configure the time synchronization mode for vCenter.
- [x] Connect to the target ESXi host or vCenter system.


Which vCenter log level should you use to troubleshoot complex issues?

- [ ] Warning
- [ ] Error
- [ ] Info
- [x] Verbose


Which two components are part of vCenter Server Appliance 8.0? (Choose two)

- [ ] Platform Services Controller
- [x] PostgreSQL
- [x] Photon OS
- [ ] vSphere Client
- [ ] MySQL


Which statement is true about data center inventory objects?

- [ ] An ESXi host can belong to more than data center at the same time.
- [ ] They only appear in the Hosts and Clusters inventory view.
- [ ] A vSphere cluster object contains a data center object in the inventory.
- [x] vCenter can have more than one data center in its inventory.


The vCenter inventory contains a folder named Production. This folder contains three VMs: VM01, VM02 and VM03.
What two steps do you perform to give a user read-only access to VM01 and VM02, and administrator access to VM03? (Choose two)

- [ ] Give the user read-only access to the Production folder, and do not propagate to children.
- [x] Give the user administrator access to VM03.
- [x] Give the user read-only access to the Production folder and propagate to children.
- [ ] Give the user read-only access to VM01.
- [ ] Give the user administrator access to the Production folder.


Which two networking features can only be used with a distributed switch? (Choose two)

- [ ] Outbound traffic shaping
- [ ] IPv6 support
- [ ] VLAN segmentation
- [x] Network I/O Control
- [x] Inbound traffic shaping


Which networking policy option can you enable to help you detect a network failure?

- [x] Link state monitoring
- [ ] Explicit failover order
- [ ] NIC teaming
- [ ] Switch notification


Which security policy setting allows you to use software to analyze network traffic for malicious activity?

- [ ] Forged Transmits set to Accept
- [ ] Forget Transmits set to Reject
- [ ] Promiscuous Mode set to Reject
- [x] Promiscuous Mode set to Accept


Which type of virtual switch connection is used for management traffic only?

- [ ] VM port
- [x] VMkernel port
- [ ] Distributed port
- [ ] Uplink port


What advantage does a distributed switch have over a standard switch?

- [ ] Use of load balancing techniques for VM traffic
- [ ] Ability to create networks for vSAN and vSphere Replication
- [x] Centralized administration of virtual networks
- [ ] Ability to configure NIC teaming and failover policies


On which two storage protocols can VMFS datastores be created? (Choose two)

- [ ] RDM
- [x] FCoE
- [x] DAS
- [ ] vSAN
- [ ] NFS


Which two tasks must be performed to configure multipathing for dependent hardware iSCSI? (Choose two)

- [x] Connect each NIC to a separate VMkernel port.
- [ ] Bind the iSCSI target server to the virtual switch.
- [ ] Bind each independent iSCSI hardware adapter to a VMkernel port.
- [x] Bind each VMkernel port to the iSCSI initiator.
- [ ] Configure the software iSCSI adapter on the ESXi host.


What are two methods to dynamically increase the size of a VMFS datastore? (Choose two)

- [ ] Place the datastore in maintenance mode and add the extent.
- [x] Add another extent to the datastore.
- [ ] Unmount the datastore and add the extent.
- [x] Expand the extent on which the datastore is located.
- [ ] Unmount the datastore and expand the datastore's extent.


What are two features that NFS 4.1 provides? (Choose two)

- [ ] VMware proprietary file locking
- [ ] CHAP security
- [x] Kerberos authentication
- [x] Native multipathing
- [ ] Multipathing managed by ESXi


What is one way to add an OVF template to a content library?

- [ ] Export a VM to an OVF template.
- [ ] Convert a VM to a template.
- [x] Clone a VM as a template in the library.
- [ ] Create a content library subscription.


What task must you perform to allow a content library to share its contents with other content libraries?

- [ ] Enable publishing on the subscribed content library.
- [x] Enable publishing on the local content library.
- [ ] Configure Enhanced Linked Mode.
- [ ] Configure the content libraries on the same vCenter instance.


How many versions of a VM template does the content library maintain at any time?

- [ ] 1
- [x] 2
- [ ] 3
- [ ] 4


What are three benefits of VMware Tools? (Choose three)

- [ ] Encapsulation of VMs into a set of files for ease of management
- [ ] Isolation of VMs from other VMs for better security
- [x] Use of the VMXNET3 driver for improved network performance
- [x] Ability to shut down a VM remotely
- [x] Use of the balloon driver for improved memory management


What are two pieces of information that you set in the VM customization specification? (Choose two)

- [ ] Network driver type
- [ ] Storage adapter type
- [x] DNS server information
- [x] Computer name
- [ ] Virtual hardware version


VM 1, VM 2, and VM 3 are single-CPU VMs that are powered on. CPU shares are set as follows: VM 1 has 400 shares, VM 2 has 1000 shares, and VM 3 has 1600. If all three VMs are in contention for the same CPU resource, approximately how much of the CPU resource is allocated to VM 2?

- [x] 33%
- [ ] 73%
- [ ] 13%
- [ ] 53%


What migration type should you use to migrate a running VM to a new cluster, when the target cluster does not have access to the source cluster's storage? 

- [ ] Change storage only
- [ ] Change compute resource only
- [x] Change both compute resource and storage
- [ ] Cross vCenter Server export


You have a VM running on a host in a cluster in your on-premises data center. You want to migrate this VM to a data center in the public cloud, but you do not know which CPUs are used in the hosts in the public data center.
What approach should you take to migrate this VM?

- [x] Enable EVC CPU mode on the virtual machine.
- [ ] Enable EVC graphics mode on the cluster.
- [ ] Use the vSphere vMotion TCP/IP stack.
- [ ] Perform a long-distance vSphere vMotion migration.


Which two requirements must be met to perform a successful vSphere vMotion migration? (Choose two)

- [ ] The VM must not be located on an NFS datastore.
- [ ] The source and target hosts must be connected to the same subnet.
- [x] The CPU feature sets of both the source and target host must be compatible.
- [ ] The VM must not have a device attached through a remote console.
- [x] A VMkernel port enabled for vSphere vMotion must exist on the source and target host.


What happens when you perform a Snapshot Consolidation?

- [ ] The delta disk files are compressed to reduce storage space.
- [ ] All snapshots are committed to the VM before the snapshots are removed.
- [x] Delta disk files that do not have a snapshot associated with them are removed from the datastore.
- [ ] The virtual machine is reverted to the latest snapshot and older snapshots are removed.


What are two tasks that you can perform with Cluster QuickStart? (Choose two)

- [x] Add hosts to the cluster.
- [x] Select the image to use for managing hosts in the cluster.
- [ ] Assign user permissions to access the cluster.
- [ ] Create standard switches on the hosts in the cluster.
- [ ] Create the cluster.


What vSphere DRS setting should you configure if you want to have control over placing the VM whenever a migration occurs?

- [x] Set Automation Level to Partially Automated
- [ ] Set Migration Threshold to Aggressive
- [ ] Set Automation Level to Automated
- [ ] Set Migration Threshold to Conservative


Which one of the following DRS scores indicates that the VM is experiencing mild resource contention?

- [x] 15%
- [ ] 45%
- [ ] 75%
- [ ] 95%


Which one of the following features protects against storage failures such as permanent device loss and all paths down?

- [ ] vSphere Fault Tolerance
- [ ] Proactive HA
- [x] VM Component Protection
- [ ] vSphere HA Orchestrated Restarts


Which Admission Control setting allows you to specify the amount of CPU and memory capacity to reserve in the cluster for failover purposes?

- [ ] Performance degradation VMs tolerate
- [x] Cluster resource percentage
- [ ] Host failures cluster tolerates
- [ ] Slot Policy (powered-on VMs)


You run several VMware products in your vSphere environment, and one of them is VMware Horizon version 2203.0. 
What action should you take to verify that the version of VMware Horizon that you are using is compatibility with the current version of your vCenter instance?

- [ ] Perform a compliance check on the vSphere cluster.
- [ ] Check for updates in the vCenter Management Interface.
- [x] Generate a vCenter interoperability report.
- [ ] Check for recommended images in the cluster's Updates tab.


What two actions can help speed up the remediation process and minimize the time that the hosts spend in maintenance mode? (Choose two)

- [x] Remediating in parallel
- [ ] Checking hardware compliance first
- [x] Staging patches and extensions
- [ ] Running an image compliance check
- [ ] Performing a remediation pre-check


Which VMware Tools status is a VM given when VMware Tools is installed and supported in the VM, but a newer version is available on the ESXi host? 

- [ ] Guest Managed
- [ ] Version Unsupported
- [x] Upgrade Available
- [ ] Up to Date


What are two functions of vSphere Lifecycle Manager? (Choose two) 

- [x] Upgrade the hardware of one or more VMs to match the hardware version on the host.
- [ ] Update VM templates in a content library.
- [x] Check the compliance of ESXi hosts in the cluster against an image.
- [ ] Generate interoperability reports for VMware products.
- [ ] List available updates and upgrades for vCenter.