# Definition of operating system virtualization     
1. OS-level virtualization is a type of virtualization technology which work on OS layer Here the kernel of an OS allows more than one isolated user-space instances to exist. Such instances are called containers or virtualization engines.   
2. OS kernel will run a single operating system & provide that operating system's functionality to replicate on each of the isolated partitions.  
  
# hardware virtualization        


# Definition of deployment  
application run and operate in a specific environment. It involves installation, configuration, testing and making changes to optimize the performance of the application. 

# container security   
An enterprising hacker will find a way to create container-to-container, container-to-host, and host-container vulnerabilities,   similar to what we see in the virtual machine world.  
For example    
container orchestrator unsecured console/dashboard Recent attacks on [Tesla, Shopify, and Aviva](https://redlock.io/blog/cryptojacking-tesla).In the case of Tesla, the Kubernetes console was left configured without a password and hackers were able to take control and find the credentials to AWS cloud.   
Another Example   
unsecured API Docker API to create new rogue containers on container hosts with the community images and malware for cryptocurrency mining.  
# Basic of chroot  

A chroot is a way of isolating applications from the rest of your computer .This is particularly useful if you are testing an application which could potentially alter important system files, or which may be insecure.  

 * Definition
Creating new root file system inside existing file system known as change root or chroot. A process/command that is run in this new environment cannot access files outside the root directory. This modified environment is commonly known as jailed directory or chroot jail.  

* Uses of chroots
The following are some possible uses of chroots:   
Isolating insecure and unstable applications    
Running 32-bit applications on 64-bit systems    
Testing new packages before installing them on the production system    
Running older versions of applications on more modern versions of Ubuntu    
Building new packages, allowing careful control over the dependency packages which are installed.     
       
# Namespaces
Namespaces are a feature of the Linux kernel that partitions kernel resources such that one set of processes sees one set of resources while another set of processes sees a different set of resources. 
For example 
If the house is the host then the namespace is a room which is given to your child. It is providing privacy to each child. Each child has to see their own room and not see the other's room.only parents have visibility to see all the room and other areas inside the house. If you wish to establish connectivity between two rooms inside the house. 

When create container it’s isolated and create room inside room is called namespace 
  
 # Cgroup 
Control Groups (cgroups), which provide a mechanism for easily managing and monitoring system resources, by partitioning things like cpu time, system memory, disk and network bandwidth, into groups, then assigning tasks to those groups.
    
# Discretionary Access Control (DAC)
Discretionary Access Control (DAC) which enforces security by ownership. If a user owns a file, he is allowed to set the read, write, and execute permissions for that file. In this model, users control the data at their discretion. The owner of the system does not have total control over the system; the users do.  

# Mandatory Access Controls (MAC)   
 MAC model, access is controlled strictly by the administrator. The administrator sets all permissions. Users cannot set their own permissions, even if they own the object. Because of this, MAC systems are considered very secure. This is because of the centralized administration.  
 
 #  service oriented architectures(SOA)
  service oriented architectures  A service-oriented architecture is essentially a collection of services. These services communicate with each other. The communication can involve either simple data passing or it could involve two or more services coordinating some activity. Some means of connecting services to each other is needed.  
  
 # Platform as a service (PaaS)
Platform as a service (PaaS) is a complete development and deployment environment in the cloud, 

