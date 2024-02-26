# KeeneticOS-4
Small patch to enable netlink_diag ( ss command ) .


Keenetic OS is linux 4.9 kernel based OS with a collection  
of GNU and proprietary software tools. It can be extended by  
EntWare software, which gives shell access.  
  When using a tool "ss" to observe socket information,   
some details are missing due to "protocol not supported" error.  
This happens, because of missing netlink_diag kernel module.  
   Keenetic team provide a build system for the KeeneticOS  
at [https://github.com/keenetic/keenetic-sdk](url) .  

  If you need full ss output, you can apply given patch, enable  
module trought "make menuconfig", and build a custom image. 

 
