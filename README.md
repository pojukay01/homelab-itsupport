Project Summary: IT Support & Cybersecurity Home Lab
Objective: Build a simulated small-business IT environment to develop hands-on skills in systems administration, virtualization, and troubleshooting — supporting a transition into IT Support/Help Desk roles, backed by CompTIA A+/Tech+ and an MS in Cybersecurity (in progress).
Environment Built

Hypervisor: Oracle VirtualBox
VM 1 — Windows Server 2025 (Standard, Desktop Experience): 4GB RAM, 2 CPUs, 60GB disk, EFI boot
VM 2 — Ubuntu 26.04 LTS (Desktop): 4GB RAM, 2 CPUs, 30GB disk, EFI boot
Documentation: Public GitHub repository (homelab-itsupport) tracking progress day-by-day with screenshots

Milestones Completed
Foundation Setup

Verified host system requirements (RAM, 64-bit OS, CPU virtualization support)
Installed VirtualBox and downloaded both target OS images
Built and configured both virtual machines from scratch

Troubleshooting: VM Boot Failure

Encountered a persistent "No bootable medium found" error and black-screen hangs on Windows Server, despite correct ISO attachment and boot order
Diagnosed the root cause as a Hyper-V / Virtual Machine Platform conflict — Windows' built-in virtualization features were competing with VirtualBox for hardware-level virtualization access
Resolved by disabling Hyper-V, Virtual Machine Platform, Windows Hypervisor Platform, and WSL via Windows Features, then rebuilding the VM using EFI boot mode
Successfully installed Windows Server 2025 (Desktop Experience)

Windows Server Configuration

Applied Windows Server security updates
Installed VirtualBox Guest Additions to resolve display scaling issues and enable proper auto-resize

Ubuntu Installation

Completed full interactive installation (disk erase/setup, account creation, no encryption for lab purposes)
Installed Guest Additions via terminal — resolved a missing bzip2/tar dependency mid-install, compiled kernel modules manually
Confirmed working display auto-resize

In Progress: Active Directory Domain Services

Currently installing the AD DS role on Windows Server 2025 via Server Manager, working toward promoting the server to a domain controller

Skills Demonstrated So Far

Virtual machine provisioning and hardware allocation (CPU, RAM, storage, boot configuration)
Operating system installation (Windows Server and Linux)
Root-cause troubleshooting of low-level virtualization conflicts
Command-line package management and dependency resolution (Linux/apt)
Technical documentation and version control practices (Git/GitHub)
Working knowledge of EFI vs. BIOS boot processes

Next Steps

Complete AD DS installation and promote server to domain controller
Create Organizational Units, user accounts, and Group Policy Objects
Join Ubuntu/Windows client to the domain
Introduce a ticketing system (osTicket) to simulate help desk workflows

# IT Support & Cybersecurity Home Lab

Documenting a self-built home lab to practice IT support, systems 
administration, and security fundamentals — built alongside 
CompTIA A+/Tech+ and an MS in Cybersecurity (in progress).

## Day 1
- Verified system requirements (RAM, 64-bit OS, virtualization support)
- Installed Oracle VirtualBox
- Downloaded Windows Server 2025 evaluation ISO and Ubuntu Desktop ISO
- Created a Windows Server 2025 virtual machine in VirtualBox 
  (4GB RAM, 2 CPUs, 60GB virtual disk)
- Set up GitHub repository to document the project
<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/c22bf2bb-aeb5-4986-857b-6441d13a3366" />



## Day 2
- Diagnosed and resolved a VM boot failure caused by Hyper-V/Virtual 
  Machine Platform conflicting with VirtualBox on the host machine
- Disabled Hyper-V, Virtual Machine Platform, Windows Hypervisor 
  Platform, and WSL in Windows Features
- Successfully booted and completed Windows Server 2025 installation 
  (Desktop Experience) using EFI boot mode
- Server Manager is up and running
- Applied Windows Server security updates
<img width="1026" height="858" alt="image" src="https://github.com/user-attachments/assets/d01e24ce-20e6-41f8-9425-c6f09e962bdf" />
<img width="1026" height="858" alt="image" src="https://github.com/user-attachments/assets/4d90269f-235b-4d3c-b6a2-09092ac238ef" />
- Installed VirtualBox Guest Additions to enable proper display 
  scaling and resolution auto-resize
  <img width="1919" height="1036" alt="image" src="https://github.com/user-attachments/assets/dd740ca4-bd29-43e4-a677-d01093ad9e26" />

## Day 3
- Created Ubuntu 26.04 LTS VM in VirtualBox (4GB RAM, 2 CPUs, 30GB disk, EFI boot)
- Completed Ubuntu installation and initial setup
- Installed VirtualBox Guest Additions via terminal (resolved missing 
  bzip2/tar dependency, compiled kernel modules manually)
- Confirmed display auto-resize working correctly on both VMs
<img width="1267" height="903" alt="image" src="https://github.com/user-attachments/assets/109ff36c-d53c-446a-b928-564193e27bf6" />

<img width="1919" height="1028" alt="image" src="https://github.com/user-attachments/assets/e0ddcb46-a178-43c7-85f0-10958428c7d9" />

