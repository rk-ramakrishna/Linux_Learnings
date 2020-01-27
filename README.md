# Linux for Dummies

## Table of Contents

* [Brief history of Linux](#brief-history-of-Linux)
* [Linux Distributions](#linux-distributions)
* [Linux Standard Base](#linux-standard-base)
* [References](#references)


## Brief history of Linux:

1.	 In the early 1960s, the first computing operating systems were designed to allow only a single user to run one program at a time.
     By the late 1960s, computing was becoming far more common and decided to develop **multi user, multi tasking operating system**. Bell Labs had been involved in a project called **Multics (Multiplexed Information and Computing Service)**.

2.	 Multics was a combined effort of the Massachusetts Institute of Technology [MIT], Bell Labs, and General Electric to create multi user, multi task operating system. 
     However, the Multics project unable to achieve grand goals, and Bell Labs decided to pull out of the project. 
   
3.	 Visionary members in Bell labs **Ken Thompson, Dennis Ritchie, Brian Kernighan, Douglas McElroy, and Joe Ossanna**, decided to develop independent system based on Multics project
     concepts.  
  
4.   As a result, they developed multi user, multi task operating system called **UNIX**. 

5.   Later AT&T, the parent company of Bell labs started to provide the finical support to UNIX.

6.   During that time, all operating systems were written in assembly language. In 1972, UNIX was re-written entirely in the C programming language. Incidentally, C was also
     developed at Bell Labs, by some of the same team members who worked on the UNIX.  
 
7.	 The original name of the project was **_Unics_**, a play on the term Multics. 
  
8.	 AT&T, the parent company of Bell Labs, had been the target of an antitrust case. As part of the court ruling in that case, the company was prohibited from entering into the
     commercial computer business. So Bell Labs had to license the UNIX operating system to anyone who requested it, which led many educational institutions to adopt UNIX.
	 
9.   In the early `1980s`, AT&T broke up into smaller companies, allowing UNIX to become a commercial product.	 
   
10.  Stallman had begun working on his own operating system in 1983. He called this system **GNU (this acronym stands for GNU is Not UNIX)**. His goal was simply to create a free
     version of UNIX. He wanted it to be as much like UNIX as possible, despite the name (GNU is Not UNIX). However, Stallman’s open source UNIX variant did not achieve widespread popularity, and it was soon replaced by other, more robust, variants. 

11.  Open source was first brought to the public forefront by Richard Stallman. In 1985, Richard Stallman published a paper entitled “GNU Manifesto.” This document outlined the
     parameters for open source licensing, thus establishing **Stallman as the father of open source software**

12.	 Stallman’s Free Software Foundation later created the GNU General Public License that is now used for most open source products, including Linux.
	 
	 **Note:**
	 a. General Public License[GPL] explicitly states that the software being released is free and that no one can ever take away these freedoms. 
	    It is acceptable to take the software and resell it, even for a profit; however, in this resale, the seller must release the full source code, including any changes. 
	    Because the resold package remains under the GPL, the package can be distributed for free and resold yet again by anyone else for a profit. 
	    Of primary importance is the liability clause: The programmers are not liable for any damages caused by their software.
	 
	 b. It should be noted that the GPL is not the only license used by open source software developers. Other licenses, such as BSD and Apache, have similar liability clauses but differ in terms of their redistribution. 
	    For instance, the BSD license allows people to make changes to the code and ship those changes without having to disclose the added code.
	    
	 c. More information about licenses, verify **www.opensource.org.**   
	 
13.	 In 1987, a university professor named **Andrew S. Tanenbaum** created another UNIX variant called **Minix**. **Minix** was fairly stable and functional and a reasonably 
     good UNIX clone.Minix was completely written in C by Professor Tanenbaum, who created it primarily as a teaching tool for his students. He wanted them to learn operating systems by being able to study the actual source code for an operating system. 

14.	 The source code for Minix was included in his book Operating Systems: Design and Implementation. Placing the source code in a textbook that was widely used meant a large number
     of computer science students would be exposed to this source code. Coupled with the earlier release of the original UNIX source code, many computer science students learned UNIX and UNIX clones quite thoroughly. This wide exposure to both the original UNIX source code and the source code for UNIX clones is one reason that most open source operating systems are UNIX clones.

15.	 Although Minix failed to gain the popularity of some other UNIX variants, it was an inspiration for the creator of Linux. 

16.	 The **story of the Linux operating system really is the story of Linus Torvalds**. He began his work on Linux when he was a graduate student working toward his Ph.D. in
     computer science. In those days, all computer science students worked with UNIX, as there was no Windows or DOS, and Apple was still very much a hobbyist machine. So Linus Torvalds was quite familiar with the UNIX operating system.
 
17.	 In addition to learning UNIX, Linus Torvalds was also introduced to the Minix operating system. Linus found many things he liked about the Minix operating system, but he
     believed that he could make a better UNIX variant. So he created his own UNIX clone and released it as free software. **He chose the name Linux, as a combination of his first name, Linus, and the end of UNIX, nix.**

18.	 Once his initial Linux project was underway, he had to address the issue of how to get it out to the public. He began by posting the operating system code on an Internet
     discussion board, allowing anyone to use it, play with it, or modify it. 

19.	 Finally, Linus Torvalds released **`Linux 0.01`** on the Internet under a GNU public license. Since it was open source, this meant other computer scientists and programmers 
     had access to the source code. That allowed people all over the world to become involved in Linux and to contribute to its development.

20.	 Over the ensuing years, Linux popularity has grown. It has moved from a hobby operating system for computer enthusiasts to a full-fledged business operating system. 

21.	 Various vendors, including companies and individuals, take the Linux kernel and add their own nuances. These nuances may include additional applications, different installation
     processes, and even different targets. For example, Red Hat works to create a Linux distribution that is well suited to large scale servers, whereas Ubuntu and Kubuntu are both targeted for novice users installing on a single workstation. 

22.	 The Linux mascot, has a funny history behind it. The community was looking for a logo/mascot, and after several suggestions, Linus talked about being bitten by a 
     "ferocious fairy" penguin in an Australian zoo in 1993. Thus it was settled. Larry Ewing made the original drawing. The name Tux came from **T**orvalds **U**NI**X**, and it's also the beginning of the word tuxedo (frequently associated with penguins).

        ![Tux - Linux official logo](images/Tux_Linux_official_logo.jpg)
        


        
        
## Linux Distributions:

1.   Since Linux is open source many people code and released their own versions of Linux. Currently in market there are many Linux distros available. 
     Linux distros rating can be found at  http://distrowatch.com

2.   Linux Distro is set of components required to achieve successful working Linux system

3.   A Linux distro includes the **Linux kernel itself**, the omnipresent **GNU tools**, a lot of small tools that are needed to provide different services, probably a windowing
     system, a desktop environment, and finally a **package management system** with a number of software packages that can be installed by default or according to user preferences.

4.   Linux distros broadly categorized into two groups.
        #### a. commercial distors
        #### a. noncommercial distors 

5.   The commercial distros generally offer support for their distribution—at a cost. The commercial distros also tend to have a longer release life cycle

6.   Examples of commercial flavors of Linux-based distros are **RHEL and SUSE Linux Enterprise (SLE)**.

7.   The noncommercial distros, on the other hand, are free. These distros try to adhere to the original spirit of the open source software movement

8.   They are mostly community supported and maintained—the community consists of the users and developers. 

9.   **Reason behind the existence of so many Linux distributions, because of GNU project, the FSF[Free software foundation]. If GNU project not exist, we mayn't see birth of Linux. 
     That's the reason, so many community members term Linux as GNU/Linux**
	 
10.  Since we have so many Linux distributions, we have to carefully pick suitable Linux distro according to requirements. 
     For example, we shouldn't consider the Elementry Linux used in Embedded systems for desktop or server.  
	 
11.  **Factors to Consider when Choosing a Linux Distro**

		![Linux_distro_selection_criteria](images/Linux_distro_selection_criteria.jpg)
		
12.  Popular General purpose Linux distros are ** Ubuntu, Fedora, Debian, Mint**.  General purpose Linux distros used for daily work at home or office. 

13.  Below are few of Task orientied Linux operating systems. 

			*  Multimedia/Arts:  Ubuntu Studio, ArtistX
			*  Media PC/Home Theater: Kodi (formerly known as XBMC), Mythbuntu
			*  Security/Forensics/Anonymity: Kali, Tails, DEFT
			*  Storage: FreeNAS
			*  Mobile: Android, Tizen, Ubuntu Phone
			*  Cloud Apps: Chrome
			*  Routers: OpenWrt
			*  Gaming: SteamOS
			*  Cloud/Data Center: CoreOS
     

14.  Another important consideration for Linux distro is Enviornment. There are 4 major Enviornments, such as Desktop, Server, cloud/virtualization and embedded 

15.  When you need to serve a database or a web site, you use a Linux distro oriented to the server environment.

### Server 

16.  Server Distro usually lack a graphical environment. Security, performance, and stability are the main features in this category and 
     usually these distros are a bit outdated compared to the desktop distros. 
	 
17.  **These Linux distros are meant to be running on a 365/24 basis and they usually are not rebooted for years at a time.**

18.  Popular and well-recognized distros in server are Red Hat Enterprise Linux, SUSE Linux Enterprise Server, CentOS, 
     and Oracle (the last two are forks of Red Hat) as well as corresponding server versions of the most popular desktop distros like Ubuntu Server or Debian.

### Cloud/Virtualization	 

19.  This is a subcategory or a super-specialization of the server category. 

20.  This distro need to be reliable, secure, scalable, easy to automate and deploy, etc.

21.  Most of the big and popular distros are used in this environment, like Red Hat, CentOS, Ubuntu, and Debian. 

22.  Some offer specialized versions to fit new needs, like Ubuntu Cloud and Amazon AMI (one fork of Red Hat suited to work with AWS), 
     and some even offer their own cloud services like **Red Hat OpenStack or OpenShift.**

23.  **There are also extremely light and minimal Linux distros created especially for this environment like CoreOS, which makes use of new technologies like containers (Docker,
     rocket and Kubernetes).**

24.  **Although virtualization is supported by default nowadays in the kernel, there are some distributions that focus only on it, like Oracle VM Server 
     or Proxmox VE (Debian based), which work like bare-metal hypervisors.**

### Embedded/Mobile
	 
25.  The distros in the embedded/mobile category are very specialized, aimed to fit in mobile devices, consumer electronics, network appliances (routers, firewalls)
     , machine controls, industrial automation, road vehicles, medical instruments, etc.      	 
	 
26.  The best known ones are employed on mobile devices, such as Android, Ubuntu mobile, and Tizen. Others like OpenWrt and Alpine are focused on network devices.	 


### Package Management System

27.  In Linux, you install/update software using a package manager, usually from official repositories on the Internet or directly from a package. 

28.  A package manager is a fantastic, centralized, and secure way to manage the software of your operating system. But, as usual in Linux, there are many different package managers.

29.  RPM:
	 RPM is the acronym for Red Hat Package Manager and is obviously the one used by that distribution and its derivatives. 
	 It was also adopted by SUSE and Mandriva and thus their derivatives. It's the de facto official packaging system, and it's the one most frequently supported by corporate developers. These packages have the .rpm suffix.

30.  Some of the Linux distros that support this system are Red Hat, CentOS, Oracle Linux, Fedora, SUSE, OpenSUSE, Mageia, and PCLinuxOS.

31.  dpkg:
	 The package management system created by Debian is called dpkg, and it is the second most used after rpm. The suffix of these packages is .deb. When corporate developers release a version of their software for Linux, they normally offered .rpm and .deb packages, and sometimes also the source.

32.  Some of the many distros that use this system are Debian, Ubuntu, Mint, and all of the Debian/Ubuntu derivatives.



## Linux Standard Base:

1.  As we noticed there are lot of Linux Distributions with distinct functionalities. Obviously they have a lot in common, but at the same time they have many particularities 
    that make them different from each other. 
   
2.  In order to make this "mess" something bearable and manageable to software developers (and ultimately the users), the LSB was created. 

3.  The Linux Standard Base is a project supported by several Linux distros that aims to offer some common ground between the different distributions.

4.  It provides standards for things like the file system hierarchy, libraries, printing system, run levels, and so on.

5.  The goal of the LSB is to develop and promote a set of open standards that will increase compatibility among Linux distributions and 
    enable software applications to run on any compliant system even in binary form. In addition, the LSB will help coordinate efforts to recruit 
	software vendors to port and write products for Linux Operating Systems.  
	
6.  The project originated in 2001 and the current version of its standards is 5.0. 

7.  But its impact is very small; only a few Linux distros follow it, like the commercial ones: Red Hat, SUSE and Ubuntu. 

8.  So it is currently only a beautiful idea embraced by a small percentage of all Linux distributions. Also, it has been criticized by some distros like Debian over some
    controversial decisions.

9.  Please refer here for LSB   www.linuxfoundation.org/collaborate/workgroups/lsb
 	
	 
## References:

	*  Linux Command Line and Shell Scripting Bible, Third Edition
	*  The Linux Command Line: A Complete Introduction, 2nd Edition
	*  Introduction to UNIX/Linux  			-   Cengage Charles River Media
	*  Linux Distros					-	Jose Dieguez Castro
	
	