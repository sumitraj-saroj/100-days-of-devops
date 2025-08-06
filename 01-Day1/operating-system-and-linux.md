## 2 - Operating Systems & Linux Basics

### Virtualization & Virtual Machines

You need a hypervisor to run multiple virtual machines using a physical Host OS
Most popular hypervisor is VirtualBox (Used this in the past but sinds I switched to M1 I needed to use UTM because
VirtualBox does not support M1 )
VMs are isolated Type 2 vs Type 1 Hypervisor: Type 1 installed directly on hardware for servers, Type 2 uses host OS on
personal computer

- Benefits Type 2: learn & experiment, don’t endanger main OS, test app on different OS
- Benefits Type 1: efficient usage of hardware resources, abstraction of OS from hardware via VMI (Virtual Machine
  Image) with backups/snaphots

### Linux File System

Everything in Linux is a file(In MAC / Windows it is not the case)
A root user has its own home directory. This directory can be different in different oses (In MAC it is /Users/username)

#### Linux folder structure

* /home/{Username} dir of non-root users (If the user is created with a home directory)
* /bin executables for essential system cmd
* /sbin system binaries, need super user privileges to execute
* /lib shared lib that execs from /bin or /sbin use
* /usr was used for user home dir (histroic reasons due to storage limitations)
* /usr/local programs that YOU install on computer (3rd party apps) available for all users
* /opt 3rd party programs you install that DONT split its components
* /boot files required for booting
* /etc system config
* /dev device files (webcam, mouse, keyboard etc)
* /var stores logs
* /var/cache
* /tmp temporary resources required for processes
* /media removable media
* /mnt temporary mount points

Hidden files (starts with a dot)

### Commands

* pwd = show current dir
* ls = list contents
* cd = change dir (cd / = change to root dir and empty cd is go to home)
* mkdir = make dir
* touch = create file
* rm = delete file
* rm -r = delete non-empty dir with files in it
* rmdir = delete empty dir
* clear = clears terminal
* mv <old-name> <new-name> = rename file to new name
* cp -r <dir> <new-dir> = copy contents folder to new folder
* ls -R = list all folders and files in each
* history = lists all recent cmd in terminal
* ls -a = display hidden files
* ls -l = print files in long list format (ls -la for listing hidden files)
* cat = show contents file
* uname -a = show system & kernel
* cat /etc/os-release = show release version
* lscpu = cpu info
* lsmem = memory info
* sudo = grants super user privileges for cmd
* su - <username> = become user
* | = pipe, passes output of one cmd as input of next cmd
* <input> | less = displays reader friendly format for info in CLI
* <input> | grep <pattern> = filter input based on pattern search
*  > = redirect, takes output from previous cmd and sends it to file that you give (overrides contents file)
* > > = appends text to end of file
* > > Can pass multiple cmd in one line separated by ;
