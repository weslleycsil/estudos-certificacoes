# Compute

## Introduction

* Virtual Machines
* Bare Metal Server
* Dedicated Host

Characteristics:

* Scalability
* Hig Performance
* Lower Princing

Instances Types

* Burstable instances

are virtual machine (VM) instances that provides a baseline level of CPU performance with the ability to burst to a higher level to support occasional spikes in usage. For more information [Burstable Instances](https://docs.oracle.com/en-us/iaas/Content/Compute/References/burstable-instances.htm#burstable-instances)

* Shielded instances

harden the firmware security on bare metal hosts and virtual machines (VMs) to defend against malicious boot level software. For more information [Shielded Instances](https://docs.oracle.com/en-us/iaas/Content/Compute/References/shielded-instances.htm#shielded)

OCPU -> 1 core 2 Threads

Shapes Type

* Standard

Designed for general purpose workloads and suitable for a wide range of applications and use cases. Standard shapes provide a balance of cores, memory, and network resources. Standard shapes are available with Intel, AMD, and Arm-based processors.

* DenseIO

Designed for large databases, big data workloads, and applications that require high-performance local storage. DenseIO shapes include locally-attached NVMe-based SSDs.

* GPU

Designed for hardware-accelerated workloads. GPU shapes include Intel or AMD CPUs and NVIDIA graphics processors.

* High performance computing (HPC) and optimized

Designed for high-performance computing workloads that require high frequency processor cores. Bare metal HPC and optimized shapes support cluster networking.

## Flexible Shapes

OCPU x Memory

Right Machine Type

* Flexible Shapes
* Sizing
    * Small
    * Medium
    * Large

Platforms

* AMD
* Intel
* Ampere (ARM)

Capacity Types

* On-demand capacity

Pay for only the compute capacity that you use. With on-demand capacity, you pay for compute capacity by the second, and depending on the shape, you pay only for the seconds that your instances are running. Capacity availability is not guaranteed when launching large workloads.

* Preemptible capacity
 
Preemptible capacity allows you to save money by using preemptible instances to run workloads that only need to run for brief periods or that can be interrupted when the capacity is reclaimed. Preemptible instances behave the same as regular compute instances, but the capacity is reclaimed when it's needed elsewhere, and the instances are terminated. For more information, see Preemptible Instances.

* Reserved capacity

Reserve capacity for future usage, and ensure that capacity is available to create compute instances whenever you need them. The reserved capacity is used when you launch instances against the reservation. When these instances are terminated, the capacity is returned to the reservation, and the unused capacity in the reservation increases. Unused reserved capacity is metered differently than used reserved capacity. For more information, see Capacity Reservations.

* Dedicated capacity

Run VM instances on dedicated servers that are a single tenant and not shared with other customers. This feature lets you meet compliance and regulatory requirements for isolation that prevent you from using shared infrastructure. You can also use this feature to meet node-based or host-based licensing requirements that require you to license an entire server.




Preemptible VM's

* Low Cost
* Short Lived VM's
* Batch Jobs
* Fault Tolerance Workload
* 50% Cheaper

## Instances

<img src="images/compute-01.png" width="700"/>

## Components for Launching Instances

The components required to launch an instance are:

* Availability Domain (AD)
* Virtual Cloud Network (VCN)
* Key Pair (for Linux instances)
* Password (for Windows instances)

## Scale

Vertical Scalling

* Scale-up scale-down instance shape
* Downtime required
* Stop the instance before scale

Horizontal Scalling

* enable large-scale deployment of VM's
* Scale-out (+) scale-in (-)
* Match traffic demand, add or remove VM's
* Dimension and High Availability
* No extra Cost

First -> Runing Instance -> Generate Config
* OS Image
* Metadata
* Shape
* vNic
* Storage
* subnets

Second -> Config -> Create Instance Pool
* Manage all Together (start, stop, terminate)
* Different AD's

Third -> Instance Pool -> Scalling Rule
* Initial Size
* Maximum Size

eg. IF CPU or Memory > 70% ADD Instances


## OS Management

OSMS -> Helps Sysadmin automate instances management
(**NO Charge**)

* Automated Patch Management (Oracle Linux, Windows)
* Simplified Package Management
* Common Vulnerabilities and Exposure Lookup (Only Linux)

Automated Patch Management

* Fix Bug
* Improvement Performance
* Add Features

Simplified Package Management

* Installing
* Patching
* Removing

# Questions

You have a web application that receives 10X more traffic on the weekends than weekdays. You need to automatically match capacity to demand, keep the application always up and running, and save cost.

Which OCI compute feature can be used to meet these requirements?
- Parallel Scaling
- Manual Scaling
**Autoscaling** -> Autoscaling automatically scales up or down to meet the capacity requirements.
- Vertical Scaling

Which is NOT a valid compute shape option within the OCI compute service?
- Bare Metal
**Container Instance** -> You can run containers in OCI, but the service doesn’t offer a managed container instance.
- Dedicated Virtual Machine Host
- Virtual Machine

Which statement is true about OCI Compute Service?
- It doesn’t support Windows workloads.
- It provides a single size for different types of workloads.
- **It provides options to create Bare Metal or a Virtual Machine instance.** -> Oracle Cloud Infrastructure offers both Bare Metal and virtual machine instances.
- It is used only for running databases.

Which parameter is NOT modifiable?
- Number of OCPUs
- Amount of Memory
- Fault Domain
- **Primary Private IP address** -> Once allocated, the primary private IP for the instance is not editable.

Which is a feature of the OCI OS Management Service?
- Cost Management
- **Automated Patch Management** ->  OS management can be used for automating patches, simplifying package management and managing CVE (Common Vulnerability Exposure)
- Disk Encryption
- Autoscaling
