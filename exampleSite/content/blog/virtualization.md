---
author: Hugo Authors
title: Virtualization
date: 2021-01-08
description: Virtualization lab coming soon
tags: ["virtualization","networking", "HomeLab", "VMware", "ESXi"]
categories: ["virtualization", "HomeLab"]
math: true
ShowBreadCrumbs: false
draft: false
---
# Virtualization
I have been around virtualization since 2009. I worked in a technical control facility that used Dell servers for many services. This was and is considered on premises or "On Prem" capabilites. We received a visit from a contractor that brough a bunch of RAM to upgrade all the servers. It was then that I learned the benefits of virtualization in regards to maximizing server capacity, maximizing the investment in the infrastructure. Although now the advantages of technology are much more thanks to advances in technology. 

### Virtualization major benefits:
	- Equipment cost reduction
	- Energy/ power reduction
	- Space reduction
	- Increased agility
	- Reduced downtime due to disaster recovery strategies (Cold, Warm, Hot sites)

### Hypervisor
Hypervisor is the program between the user and computer resources. 
- Type I Hypervisor
	- This type of hypervisor is installed as bare metal or directly as the main Operating System (OS) for a computer. Type I hypervisors make the best use of resources because it does not have to share them with an OS
- Type II Hypervisor
	- This type of hypervisor is installed on top of the main Operating System such as Windows, Linux of Mac. Type II hypervisors share resources with the OS. 
	- Some example of virtualization software are VMware Workstation, Hyper-V, Proxmox, and VirtualBox. 

Being in the military and working with our equipment my experience with virtualization equipment has been strictly with VMware vSphere. Almost all my experience has been with ESXi especifically. 

I used VMware Workstation in my computer at home to create a learning lab. This lab allowed me to have many more repetitions with the software allowing me to create, destroy or configure it for many uses. This helped my build my proficiency with it. In addition to, I was able to play around with some Linux distributions in preparation for my CompTIA Security Plus certification. I used Kali Linux to become familiar with some of the tools of the trade. Although not a requirement for the test, it game me a much better undertanding of some passive vs active attacks. Darril Gibson CompTIA Security+ Get Certified Get Ahead: SY0-601 Study Guide has great labs. 

### Unable to run virtualization software on my desktop
The first time I attempted to run VMware Workstation on my computer, I was presented with an error displaying that virtualization was not turned-on on my computer. 

![](./Virtualization/AMD-V%20disabled.png)

As an Amateur Radio Operator I want to be able to analyze the current signal propagation. There are tools like VOACAP that allow for some calculations but there is a program called Ham Clock. This useful tool can gather current solar conditions and many other parameters to provide a fairly accurate prediction of successful contact based on geografical location, time of day and frequencies. The problem is that I don't have a Rasberrypie to run it. I had the idea to try running it on my VMware Workstation. I installed Linux Debian distro. I was then able to run Raspberry Pi Desktop to then launch Ham Clock. :Smile: 
