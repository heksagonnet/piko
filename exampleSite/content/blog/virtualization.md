---
author: Jean Burgos
title: Virtualization
date: 2023-01-08
description: Check out some of my home virtualization journey
tags: ["virtualization","networking", "HomeLab", "VMware", "ESXi"]
categories: ["virtualization", "HomeLab"]
math: true
ShowRelated: true
ShowToc: true
ShowBreadCrumbs: true
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

## Unable to run virtualization software on my desktop
The first time I attempted to run VMware Workstation on my computer, I was presented with an error displaying that virtualization was not turned-on on my computer. 
![](/blog/Virtualization/IMG_6089.jpeg "Dusty... I know")
![](/blog/Virtualization/AMD-V%20disabled.png)
I was able to turn this feature of my MSI B550 motherboard in the bios.
![](/blog/Virtualization/IMG_6104.JPEG)
Select Over Clocking or (OC) and Advanced CPU Configuration
![](/blog/Virtualization/IMG_6105.JPEG)
Select SVM form disable to enable.
![](/blog/Virtualization/IMG_6106.JPEG)
Save the changes.
![](/blog/Virtualization/IMG_6107.JPEG)

Linux Debian runs without any issues. 
![](/blog/Virtualization/rasberrypie.png)
[RaspberryPI OS](https://www.raspberrypi.com/documentation/computers/os.html) runs on top of Debian without issues.

## HamClock
![](/blog/Virtualization/hamclock.png)
![](/blog/Virtualization/hamclock1.png)


As an Amateur Radio Operator [KD2YAE](/blog/amateur-radio/) I want to be able to analyze the current signal propagation. There are tools like VOACAP that allow for some calculations but there is a program called [Ham Clock](https://www.clearskyinstitute.com/ham/HamClock/). This useful tool can gather current solar conditions and many other parameters to provide a fairly accurate prediction of successful contact based on geografical location, time of day and frequencies. The problem is that I don't have a Rasberrypie to run it. I had the idea to try running it on my VMware Workstation. I installed Linux Debian distro. I was then able to run Raspberry Pi Desktop to then launch Ham Clock. :smiley: 

## ESXi
I have installed ESXi Type II on Workstation and a Type I on my Dell R430 server. With a much stronger setup I am not able to install vSphere vCenter to manage not only the ESXi on my R430 server but also the ESXi running on my computer as part of the same cluster. The installation of vCenter was a learning process. Initially I was receiving an error during stage one because I did not assign enough memory to appliance. The second time I ran into another issue, this type on phase two of the installation because I did not have a DNS or a Domain Controller set up. After all of that the installation was finally done. Then I realized that vCenter is resource intensive and it was not a good idea to run it from my computer along with other VMs. 
![](/blog/Virtualization/esxi.png)
This set up has been tremendous help to get some real live hands on experience. VMware provides free Hands on Lab, but I feel like the physcal gear was necessary for my to see all the parts come together. 
![](/blog/Virtualization/server.jpeg "I need to find an affordable cabinet deep enough to house this puppy")

![](/blog/Virtualization/ESXionR430vcenter.png "ESXi on R430")
![](/blog/Virtualization/ESXionR430.png "ESXi on R430")
## vCenter

![](/blog/Virtualization/vcenterinstall.png "vCenter Install on Desk Top as appliance")

## NSX-T Training

![](/blog/Virtualization/NSX-T_Lab.png "NSX-T Underlay")

![](/blog/Virtualization/NSX_intrution_detection.png.png "NSX-T Intrusion Detection")

![](/blog/Virtualization/NSX_traffic_analysis.png "NSX-T Traffic Analysis")

