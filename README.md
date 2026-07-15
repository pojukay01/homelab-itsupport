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

## Day 2
- Diagnosed and resolved a VM boot failure caused by Hyper-V/Virtual 
  Machine Platform conflicting with VirtualBox on the host machine
- Disabled Hyper-V, Virtual Machine Platform, Windows Hypervisor 
  Platform, and WSL in Windows Features
- Successfully booted and completed Windows Server 2025 installation 
  (Desktop Experience) using EFI boot mode
- Server Manager is up and running
