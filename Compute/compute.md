* Compute power is a critical component in running applications efficiently. GCP provides a comprehensive range of services designed to handle varied workload requirements.

## Services
* Compute Engine
* Cloud Functions
* Cloud Run 
* App Engine
* GKE
* Google Cloud VMware Engine
* Bare Metal Solution
* Cloud GPUs
* Workflows
* Distributed Cloud
* Container Optimized OS

## Compute Instance
* A compute instance is a virtual machine that powers your application. You can customize these instances by configuring parameters such as CPU, RAM, and storage options. 
* Unlike physical servers in a data center, compute instances are managed by GCP, meaning you have limited direct access to the underlying hardware.

## Persistent Disks
* These are durable network storage devices that your instances can access like physical disks in a desktop or a server
* They host your operating system, applications, logs, and vital data. Depending on your workload requirements, you can choose from various disk types such as HDD or SSD, offering a balance between performance and cost.

## VPC Firewall Rules
* VPC firewall rules help manage and secure network access to your compute instances and the applications running on them. 
* These rules define which ports are accessible and restrict connections based on IP ranges. 
For example, configuring a firewall rule with the source range of 0.0.0.0/0 exposes your instance to all IP addresses, which is typically not recommended. Instead, it is best practice to limit access to specific IP ranges, such as those of your office network or approved VPN configurations.

## Effective Compute Scaling:

* How do you horizontally scale your compute resources during traffic surges?
* What strategies and GCP services can be leveraged to handle growth efficiently?

## Traffic Distribution:

* How do you balance incoming traffic across multiple instances to prevent overload?
* Which load balancing techniques and tools provided by GCP can assist in ensuring smooth traffic flow?


 ## Instance Group ( Auto Scaling Group In AWS)
 * Instead of launching multiple virtual machines (VMs) independently, you can deploy them under a single instance group. This approach allows you to manage multiple VMs as one entity

 ### Managed Instance Groups
 * These groups consist of identical VMs that are automatically created and maintained. Features such as autoscaling, automated updates, self-healing, and high availability make Managed Instance Groups ideal for production environments
 * In unmanaged instance groups, VMs are created independently and require separate management. Lacking built-in autoscaling and self-healing capabilities, they are less suited for scenarios where high availability and scalability are critical.

### Instance Template: 
* An instance template defines the configuration of the virtual machines within the group, including machine type, disk space, and other settings.

### The Role of Load Balancing
* Load balancing is the process of distributing incoming network traffic across multiple backend instances. 

#### This is essential for:

* Optimizing resource utilization
* Maximizing throughput
* Minimizing response times
* commerce-lb-HCPreventing any single server from being overwhelmed

## Network Models: TCP/IP vs. OSI
Understanding network communication begins with layered models. Two of the most common models include:

* TCP/IP Model: Consists of four layers—Application, Transport, Network, and Network Interface.
* OSI Model: Divides communication into seven layers—Application, Presentation, Session, Transport, Network,  Data Link, and Physical.

Each protocol operates at specific layers:

* HTTP functions at the Application layer.
* Ethernet operates at the Network Interface (or Data Link) layer.
* TCP works at the Transport layer.
