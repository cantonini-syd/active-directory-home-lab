# Part 1: Lab Setup & Windows Server 2022 Installation

## Objective
Establish the foundation for an Active Directory home lab by setting up a 
virtualization environment and performing a clean installation of Windows 
Server 2022. This server will later be promoted to a Domain Controller to 
manage users, groups, and policies for a simulated small business network.

## Lab Environment Overview

| Component | Specification |
|-----------|---------------|
| Hypervisor | Oracle VirtualBox 7.2.8 |
| Server OS | Windows Server 2022 (Desktop Experience) |
| Client OS | Windows 11 (configured in later parts) |
| Server vCPUs | 2 |
| Server RAM | 8 GB |
| Network | NAT (default, will be reconfigured later) |

---

## Step 1: Install Oracle VirtualBox

Downloaded and installed Oracle VirtualBox 7.2.8 from the official site 
(virtualbox.org). VirtualBox is a free, cross-platform hypervisor that 
allows multiple operating systems to run simultaneously on a single host 
machine — ideal for building isolated lab environments without dedicated 
hardware.

---

## Step 2: Download Required ISOs

**Windows Server 2022 ISO**
Downloaded the 64-bit evaluation ISO directly from Microsoft's Evaluation 
Center. The evaluation version is fully functional for 180 days, which is 
more than enough for lab work.

**Windows 11 ISO**
Obtained using the Windows 11 Media Creation Tool from Microsoft, selecting 
the "Create ISO file" option so it can be mounted inside a VM.


---

## Step 3: Create the Server 2022 Virtual Machine
