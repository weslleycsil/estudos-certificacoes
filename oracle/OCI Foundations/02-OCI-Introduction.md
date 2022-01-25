# OCI Architecture

## Regions

A region is a localized geographic area, composed of one or more Availability Domains. Oracle Cloud Infrastructure resources are either region-specific, such as a virtual cloud network.

## Availability Domain (AD)

One or more data centers located within a region. **A region is composed of one o more Availability Domains**.
    (Contigência Geográfica)

## Fault Domain

Structure within an Availability Domain. Each AD contains three FD's, and each FD's has its own link, thus establishing high availability between FD's

## Compartment

A compartment is a collection of related resources (such as instances, virtual cloud networks, block volumes) that can be accessed only by certain groups that have been given permission by an administrator.
    
Compartments allow you to organize and control access to your cloud resources. 

Oracle creates your tenancy, which is the root compartment that holds all your cloud resources. You then create additional compartments within the tenancy (root compartment) and corresponding policies to control access to the resources in each compartment. When you create a cloud resource such as an instance, block volume, or cloud network, you must specify to which compartment you want the resource to belong.

# Questions

Which statement accurately describes an OCI Region?
* Each region has a single Fault Domain.
* **Each Availability Domain has three Fault Domains.**
* Each Fault Domain has multiple Availability Domains.
* Each Availability Domain has a single Fault Domain.

Which statement is true about OCI architecture and its core components?
* Each fault domain has three availability domains.
* **Each availability domain has three fault domains.**
* Fault domains act as physical data centers within an availability domain.
* All OCI regions have three availability domains.

You have subscribed to an OCI region, which has one a single availability domain. You want to deploy a highly- available application with two web servers and a 2-Node database.
How would you place the components to maintain high- availability of the application?
* **Place one server and a DB node in one fault domain, and the second server and DB node in another fault domain.**
* High availability is not possible because there is only one availability domain in the region.
* Place all the components in the same fault domain.
* Place the servers in one fault domain and the database nodes in another fault domain.

Which statement is true about OCI?
* Availability domains share infrastructure such as power, cooling, or internal availability domain network within a region.
* **An OCI region is a localized geographic area.**
* A single fault domain can be associated with multiple availability domains within a region.
* An availability domain is a logical data center.

Which OCI construct protects against failures within an availability domain?
* Compartments
* Load Balancer
* **Fault Domain**
* Tenancy
* Regions
