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


