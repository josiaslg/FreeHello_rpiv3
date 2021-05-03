# FreeHello_rpiv3
Base for be used on hellosystem for raspberry pi3b

This is a version of FreeBSD recompiled specifically for raspbery pi 3b. 
It has no SSHD or X server. 
Is a base with only pkg and specific optimizations for SOC_BRCM_BCM2837 (raspberry pi3b). 
In this repository you will find: 

src.conf - Utilities and services excluded from the database. 
make.conf - CFLAGS 
rc.conf - Configuration file 
ttys - Reduced number of active virtual terminals 
hellosystem_0_5alpha_kernel (used to compile the custom kernel). 
config.txt modified for better performance.  

The LLVM was removed, with the possibility of adding via pkg after installation.  
Suggestions for changes, access to the repository will be granted. 
This is just an ALPHA, with the sole purpose of having a functional image of the base system to later receive the additional packages belonging to hello.
