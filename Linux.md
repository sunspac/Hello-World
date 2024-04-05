# Linux History And Basics Linux Command

# What is Operating System ?
Operating system is an interface between user and the computer hardware. The hardware of the
computer cannot understand the human readable language as it works on binaries i.e. 0's and 1's. Also it
is very tough for humans to understand the binary language, in such case we need an interface which
can translate human language to hardware and vice-versa for effective communication.

# Types of Operating System:
 Single User - Single Tasking Operating System
 Single User - Multitasking Operating System
 Multi User - Multitasking Operating System
 
## Single User - Single Tasking Operating System
In this type of operating system only one user can log into system and can perform only one task at a
time.
E.g.: MS-DOS

## Single User - Multi tasking operating System
This type of O/S supports only one user to log into the system but a user can perform multiple tasks at a
time, browsing internet while playing songs etc.
E.g.: Windows -98,Xp,vista,Seven etc.

## Multi User - Multi Tasking Operating System
These type of O/S provides multiple users to log into the system and also each user can perform various
tasks at a time. In a broader term multiple users can logged in to system and share the resources of the
system at the same time.
E.g.: UNIX, LINUX etc.
## Founder of Linux:
Linus Torvalds, a Finnish computer expert, is famous for starting the creation of Linux and the git system for keeping track of changes in software.

# History of Linux:

Linux is like a cool cousin of Unix, and it's a free computer system made by Linus Torvalds in September 1991.

Back in 1991, Linus was a student at the University of Helsinki in Finland, not the USA.

He made the starting code for Linux 0.01 and shared it on the Minix group on September 17, 1991. 
Because people liked it so much, they cheered him on to make more. 
Linus listened, made new code, and on October 5, 1991, he launched the first "official" Linux, version 0.02.

# What is Linux?:

Linux is a Kernel not OS (Operating System).

Linus distribution is the Linux kernel and a collection of software that together, create on Operating System.

# Why Linux is so important ?:
1. Fresh implementation of UNIX APIs
2. Open source development model
3. Supports wide variety of hardware
4. Supports many networking protocols and Configurations
5. Fully supported
   
1) Linux is a UNIX like OS: Linux is a similar to UNIX as the various UNIX versions are to each
other.
2) Multi-User and Multi-tasking: Linux is a multi-user and multi-tasking operating system.
That means that more than one person can be logged on to the same Linux computer at
the same time. The same user could even be logged into their account from two or
more terminals at the same time; Linux is also Multi-Tasking. A user can have more than
one program executing at the same time.
3) Wide hardware support: Red Hat Linux support most pieces modern x86 compatible PC
hardware.
4) Fully Supported: Red Hat Linux is a fully supported distribution Red Hat Inc. provides
many support programs for the smallest to the largest companies.

# Advantage of Linux:
Open Source.
Secure.
Simplified update for all Install Software.
Light weight.

# Architecture of Window and Linux:
## Window:
Imagine a well-organized skyscraper.

The floors represent different layers of the system.

Windows is designed to work seamlessly within its structured environment.

![image](https://github.com/sunspac/introduction/assets/154580560/002b3326-a006-4fa4-81de-dee81c4dfb20)

## Linux:

Think of a versatile house with different rooms.

You can customize each room as you like.

Linux is adaptable, like having the freedom to rearrange things in your own way.

![image](https://github.com/sunspac/introduction/assets/154580560/1096e273-7988-415d-974a-0ce7aded7cbf)


# FSH(File System Hierarchy) of Linux and Window:
## Window FSH:

![image](https://github.com/sunspac/introduction/assets/154580560/f271388b-3539-4f74-88e3-e2ce6829b2e6)

## Program Files in Windows:

The "Program Files" folder in Windows is where the operating system stores the software applications and programs that you install. Each program typically has its own subfolder within "Program Files," keeping them organized.

## User Files in Windows:

The term "User Files" is a bit general, but it often refers to folders and files associated with a specific user account on a Windows system. This can include documents, pictures, downloads, and other personal files stored in the user's profile.

## Program Files (x86) in Windows:

The "Program Files (x86)" folder is where 32-bit applications are installed on a 64-bit Windows system. The "(x86)" indicates that it's for 32-bit programs. On a 32-bit Windows system, there is no "(x86)" folder because all programs are 32-bit by default.

## PerfLogs in Windows:

"PerfLogs" stands for Performance Logs, and it's a folder where Windows stores performance and reliability monitoring logs. These logs can provide information about system performance, errors, and other events that may affect the overall health and operation of the system. The information in PerfLogs can be useful for troubleshooting and performance analysis.

# Linux FSH:

![image](https://github.com/sunspac/introduction/assets/154580560/7c142db4-9bc6-44b5-8302-5c4ffa408ee1)


/:The base of the Linux directory is the root. This is the starting point of FSH. Every directory arises from the root directory. It is represented by a forward slash (/).

/root: It is home directory for root user.

/mnt: /mnt is for temporarily mounting file systems.

/home: Home directory for other user.

/media: /media is where removable media devices get mounted.

/bin: /bin contains commands used by all the user.

/user: By default software are installed in the directory.

/sbin: It contains command used by root user.

/etc: Directory is a crucial directory that stores system-wide configuration files and settings.

/dev: /dev has device files, such as terminals and USB devices.

/opt: /opt is for optional applications, often from third-party vendors.

/var: /var stores variable files, like log files in /var/log and database files in /var/lib.
