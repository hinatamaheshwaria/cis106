---------
Name: kInjal Maheshwaria
cis106
--------------

Lecture 2 Introduction to Linux Notes (this is the tittle of the document - Heading 1 formatting please!)

1.  ### What is an Operating System?
    An operating system provides all fundamental software features of a computer. An OS enables you to use the computer's hardware providing you the basic tools that make the computer useful. 

2.  ### What is a kernel? 
    An OS kernel is a software component that's responsible for managing low-level features of the computer. including the following managing system hardware, memory allocation, CPU time, and program to porgram interaction. 

3.  ### Which other parts aside from the kernel identfy an OS?
    * **command-LInes shells**
        * this was the de facto way of using computer before the graphical interface was invented. CMDs work by typing command in a shell. In linux, the entire system can be control via the CLI.
    * **Graphical User interfaces**
        * GUIx rely on icons, menus, and a mouse pointer for the user interaction. LInux relies on a GUI known as the X window system in combination with desktop environment program suites. 
    * **Utility and productivity programs**
        * tools like web browsers, document processors and text editors. 
    * **Libraries**
        * Libraries are collections of programming functions that can be used by a variety of programs. 

4.  ### What is linux?
    Linux is a *Unix-Like-Operating system* popular in academic and business environments.

5.  ### What is a linux distribution?
    A Linux distribution (often called a distro) is an operating system that is based on the Linux kernel, bundled with software, tools, libraries, and a package manager to provide a functional and user-friendly computing environment.

6.  ### List at least 4 linux characteristics:
    ***Open Source***
    Linux is open source, meaning its source code is freely available for anyone to view, modify, and distribute under licenses like the GNU General Public License (GPL).

    ***Multitasking and Multiuser:***
    Linux can handle multiple tasks simultaneously and allows multiple users to work on the system at the same time without interference.

    ***Portability:*** 
    Linux is portable and can run on a wide range of hardware, from PCs and servers to mobile devices, embedded systems, and supercomputers.

*   **Security***:
    Linux is known for its strong security model. It has built-in user permissions, access controls, and tools like firewalls, making it less vulnerable to malware and unauthorized access..  


7.  ### What is Ubuntu?
   
   
    Ubuntu is a popular, open-source Linux distribution based on Debian. It is designed to be user-friendly, making it a great choice for beginners, as well as for developers and advanced users.


8.  ### What is Debian?

    Just like ubuntu Debian is a free and open-source Linux distribution that serves as the foundation for many other distributions, including Ubuntu. It is one of the oldest and most stable Linux distributions, known for its robustness, security, and extensive software support. Debian is developed and maintained by the Debian Project, a community-driven initiative.


9.  ### List and define the different types of licensing agreements

    Proprietary Licenses are...

    A proprietary license restricts users from freely modifying, distributing, or sharing the software. The source code is not made public, and users only receive permission to use the software under specific terms.
    Example: Microsoft Windows, Adobe Photoshop.
    GNU General Public License (GPL)

    A widely used free software license that ensures users have the freedom to run, study, modify, and distribute the software and its source code. Any derivative work must also be licensed under the GPL.
    Example: Linux Kernel, GNU Utilities.
    MIT License

    A permissive free software license that allows users to freely use, modify, and distribute the software, even for commercial purposes, with minimal restrictions. The only requirement is to include the original copyright notice.
    Example: React.js, jQuery.
    Apache License 2.0

    A permissive license similar to the MIT License, but it includes explicit grant of patent rights to users. It allows software to be used, modified, and distributed freely, even commercially.
    Example: Apache HTTP Server, Android.

10. ###  What is Free Software? Define the 4 freedoms.
    Free Software refers to software that gives users the freedom to run, study, modify, and share it. It does not necessarily mean "free of cost" but emphasizes freedom. Free Software promotes user control and collaboration, following principles set by the Free Software Foundation (FSF).


11. ###  What is virtualization?

    it is an idea that to make a computer inside another computer.

12. ###  List 3 benefits of virtualization
    you don't have to worry about bracking your computer ever again while working inside the virtualmachine. 
    1. resoruce optimization - that allows multiple vms to run inside a computer.
    2. cost saving - Fewer physical machines also reduce data center space requirements.
    3.Scalability and Flexibility: Virtualization makes it easy to scale resources up or down as needed, enabling quick deployment of new servers or applications.



13. ###  What is a hypervisor? Include definitions of the 2 types
    A hypervisor is software or firmware that creates and manages virtual machines (VMs) by allowing multiple operating systems (OS) to run simultaneously on a single physical hardware system. It abstracts and allocates physical resources (CPU, memory, storage, etc.) to the virtual machines.
        * VMware ESXi
        * Xen
        * Microsoft Hyper-V


14. ###  What is the difference between Guest OS and Host OS?
    ***Host OS***

    The Host Operating System (Host OS) is the primary operating system that runs directly on the physical hardware of a computer or server. It provides the environment in which the virtualization software (hypervisor) operates and manages the system's resources.
    It is responsible for controlling hardware resources and allocating them to virtual machines (VMs).
    Examples: Windows, Linux, macOS (as the main OS running on the computer).

***Guest OS***

The Guest Operating System (Guest OS) is an operating system that runs inside a virtual machine (VM), managed by a hypervisor. The Guest OS runs as if it were installed on physical hardware but is actually running within the virtual environment provided by the hypervisor.

It uses resources allocated by the Host OS and cannot directly control hardware.
**Examples**: A virtual machine running Windows 10 on a Linux host or running Ubuntu inside a Windows environment.

15. ###  What is virtualbox?
    VirtualBox is a free and open-source virtualization software developed by Oracle. It allows you to run multiple virtual machines (VMs) on a single physical computer, each with its own operating system (OS). VirtualBox supports various guest operating systems, including Windows, Linux, macOS, and others, all running simultaneously on a host OS.

