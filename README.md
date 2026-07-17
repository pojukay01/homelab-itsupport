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

