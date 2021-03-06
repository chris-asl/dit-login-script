dit-login-script
================

Login script for the GNU/Linux based machines at my university
###Usage:  
**1. {ditlog} username timeout  
2. {ditlog} timeout username**  
Accepts timeout interval (in seconds) and username arguments  
You can set the default values by editing the script  
*Default values are:*  
 - Time-out: 20 seconds
 - Username: **don't forget to change it to yours**
 
###Changelog:  
- v. (1.2) - User can set the timeout interval (in seconds) for the ssh command
- v. (1.1) - script now accepts username as parameter, if no parameter given a default username is used
- v. (1.3) - Dynamic checking of linux machines

###Probable features:
- [x] set username with an argument
- [x] add time-out option
- [x] dynamically get the available number of the GNU/linux machines
- [ ] probably an installation script that set the environment for passwordless ssh login, as described [here](http://www.aslanoglou.me/blog/performing-ssh-login-without-typing-your-password-via-ssh-keygen-ssh-copy-id/)
 
**You can find full description [here](http://www.aslanoglou.me/blog/greek-post-dit-gnulinux-login-script/) (in Greek).**
