# Twiga
A tool that enumerates Android devices for information useful in understanding its internals and for exploit development. It supports android 4.2 to Android 7.1.1 

##Requirements
1. The most current ADB must be in your path and fully functional
* The report name must not have any whitespace 

##Limitations
1. Some information and files cannot be pulled higher up the SDK version due to strict SELinux policies and android hardening. 
* Can only run on one device at a time for now

##To Do
1. Pull device info, file and binaries from a device in multiple devices at a time
* Support for enumeration on a rooted device
* Support enumeration on multiple devices at a time 
* Generate PDF report on the enumartuon data 

##Inpired by:
* LinEnum - https://github.com/rebootuser/LinEnum
* linuxprivchecker - https://www.securitysift.com/download/linuxprivchecker.py
* unix-privesc-check - https://github.com/inquisb/unix-privesc-check 
* Basic Linux Privilege Escalation - https://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/

