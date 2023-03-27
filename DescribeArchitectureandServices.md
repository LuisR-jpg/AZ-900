# Describe Azure architectures and services

## Describe the core architectural components of Azure

### What is Microsoft Azure

Azure is a continually expanding set of cloud services that help you meet current and future business challenges.

### Get started with Azure accounts

Many of the Learn exercises use a technology called the sandbox, which creates a temporary subscription that's added to your Azure account.

### Exercise - Explore the Learn sandbox

You can tell you're in a sandbox when there's a <kbd>PS</kbd> at the beginning of each command line.

```shell

Get-date 
az version      # Azure specific command
bash            # Shifts to bash
Get-date        # Won't work because it's PowerShell specific
date            # Does work
pwsh            # Shifts to powershell 
az interactive  # Allows you to interact through arrows, tab and enter
exit            # Leave interactive mode

```

### Describe Azure physical infrastructure

The core architectural components of Azure may be broken down into two main groupings.

#### Physical Infrastructure

The physical infrastructure for Azure starts with datacenters. Datacenters are grouped into Azure Regions or Azure Availability Zones.

##### Regions

A region is a geographical area on the planet that contains at least one, but potentially multiple datacenters that are nearby and networked together with a low-latency network.

Azure balances the workload within each region.

##### Availability Zones

Availability zones are physically separate datacenters within an Azure region. Each availability zone is made up of one or more datacenters equipped with independent power, cooling, and networking.

An availability zone is set up to be an isolation boundary. If one zone goes down, the other continues working. Availability zones are connected through high-speed, private fiber-optic networks.

Availability zones are primarily for VMs, managed disks, load balancers, and SQL databases.

##### Region Pairs

This approach allows for the replication of resources across a geography that helps reduce the likelihood of interruptions because of events such as natural disasters.

When something happens to a region, services automatically fail over to the other region in its region pair.

##### Sovereign regions

Sovereign regions are instances of Azure that are isolated from the main instance of Azure. You may need to use a sovereign region for compliance or legal purposes.

### Describe Azure management infrastructure
### Exercise - Create an Azure resource

## Describe Azure compute and networking services

### Describe Azure Virtual Machines
### Exercise - Create an Azure Virtual Machine
### Describe Azure Virtual Desktop
### Describe Azure Containers
### Describe Azure Functions
### Describe application hosting options
### Describe Azure Virtual Networking
### Exercise - Configure network access
### Describe Azure Virtual Private Networks
### Describe Azure ExpressRoute
### Describe Azure DNS

## Describe Azure storage services

### Describe Azure storage accounts
### Describe Azure storage redundancy
### Describe Azure storage services
### Exercise - Create a storage blob
### Identify Azure data migration options
### Identify Azure file movement options

## Describe Azure identity, access, and security

### Describe Azure directory services
### Describe Azure authentication methods
### Describe Azure external identities
### Describe Azure conditional access
### Describe Azure role-based access control
### Describe zero trust model
### Describe defense-in-depth
### Describe Microsoft Defender for Cloud