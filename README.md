Completed by Schevchenko Artem RPZ-23A

Laboratory Work 1
Topic: Introduction to Virtual Machine Environments and Linux Operating System Features

Objective:

To explore different types of hypervisors and their role in operating system virtualization.

To examine contemporary operating systems and their functionalities.

Glossary of Terms:

Hypervisor – A software that enables the creation and management of virtual machines.
Virtualization – A method allowing multiple operating systems to run on a single physical device.
Type 1 Hypervisor – A hypervisor running directly on the hardware without requiring an underlying OS.
Type 2 Hypervisor – A hypervisor operating on top of an existing OS, using its resources to manage VMs.
Virtual Machine (VM) – A software-based emulated computer that can run operating systems in isolation.
Guest OS – An operating system running within a virtual machine.
Host OS – The primary operating system running on the hardware, managing the hypervisor.
KVM (Kernel-based Virtual Machine) – A Linux-integrated hypervisor.
VMware – A widely used virtualization solution supporting both desktop and server environments.
VirtualBox – A cross-platform Type 2 hypervisor developed by Oracle.

Answers to Questions:

Define "hypervisor" and its types: A hypervisor is a software tool that facilitates the creation and management of virtual machines. It assigns system resources to guest OSs while ensuring isolation. Two primary hypervisor types exist:

Type 1 Hypervisors: Operate directly on hardware, eliminating the need for a host OS. Examples: Xen, Microsoft Hyper-V, VMware ESXi.

Type 2 Hypervisors: Run on an existing OS, leveraging its resources to create virtual environments. Examples: VirtualBox, VMware Workstation.

Main Components and Features of the Hyper-V Hypervisor (Variant 15):

Hyper-V, a Type 1 hypervisor from Microsoft, enables virtualization on Windows systems.

Key Components:

Hyper-V Manager – GUI-based tool for managing VMs.

Virtual Machine Monitor (VMM) – Oversees VM execution and resource distribution.

Hyper-V Virtual Switch – Facilitates networking between VMs and external connections.

Integration Services – A suite of utilities and drivers that optimize VM performance.

Storage Migration – Transfers virtual disks between storage mediums without downtime.

Checkpoints (Snapshots) – Saves VM states for quick restoration.

Dynamic Memory – Adjusts RAM allocation based on VM demand.

Live Migration – Allows moving VMs across hosts without interruptions.

Notable Features:

Supports both Windows and Linux guest OSs.

Ensures resource isolation and secure virtualization.

Provides GPU virtualization for improved graphics handling.

Offers high availability and disaster recovery solutions.

Supports nested virtualization for running VMs within VMs.

Compatible with Windows Admin Center for remote management.

Procedure:

Watch the following introduction videos and demonstrations:

Linux - Best Distributions 2023: https://youtu.be/PahmJBU9HKA?si=maxRf0nZlqs2hFGU

Top 5 Reasons for IT Professionals to Switch to Linux: https://youtu.be/bP3_mZKezvM?si=sM3Mpc9JQ_0bY9Yd

Installing Linux via Microsoft Store: https://youtu.be/eEdGl6HvSdM?si=WDbwa71i034D2rQj

Installing Linux via Dual Boot: https://youtu.be/Hfky8TEyXss?si=ilduY167LS-vKl9y

Installing Applications on Linux: https://youtu.be/M8XHJME6cxI?si=L0Koom59jTRnPXnU

Customizing Linux Taskbar: https://youtu.be/9szAz-A4gaM?si=LxaVueluI3tKRb1r

Installing Ubuntu on VirtualBox: https://youtu.be/ADOaHm1VZII?si=hG5kDRsajFn7se8d

The Shell (Linux): https://drive.google.com/open?id=0B0PV0_SM0LoDSVNPWUVRdUxaN2s

Linux Desktop Environments: XFCE vs GNOME vs KDE: https://youtu.be/2JBGQfPR5xQ?si=euswD7IHrODd-6JH

Control Questions:

Compare Type 1 and Type 2 hypervisors. What are their differences and applications?

Define "GNU GPL" and its core principle.

Explain the significance of open-source software.

What is a Linux distribution (distro)? Provide examples.

List key system administration tasks in Linux.

How is Android connected to Linux?

What are the main characteristics and applications of Embedded Linux?

How can you switch between text mode (runlevel 3) and GUI mode (runlevel 5) in Linux? Compare CLI and GUI.

Report Structure:

Title Page

Topic and Objective

Preliminary Preparation Tasks

Key Execution Steps

Answers to Control Questions

Conclusions (mandatory)

Conclusion:

This lab introduced the fundamentals of virtualization, hypervisors, and Linux OS functionalities. Understanding both Type 1 and Type 2 hypervisors is essential for efficiently managing virtual environments. VirtualBox, as a widely adopted Type 2 hypervisor, provides a user-friendly interface for creating and testing virtual machines. Furthermore, Linux-based virtualization solutions, such as KVM, demonstrate the effectiveness of open-source technologies in optimizing system performance and resource allocation. Virtualization is a cornerstone of modern computing, improving efficiency, security, and scalability.
