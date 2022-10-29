# Networking basics #1

## General
* What is localhost/127.0.0.1
* What is 0.0.0.0
* What is /etc/hosts
* How to display your machine’s active network interfaces


## Resources
**Read or watch:**

- [What is localhost](https://en.wikipedia.org/wiki/Localhost)
- [What is 0.0.0.0](https://en.wikipedia.org/wiki/0.0.0.0)
- [What is the hosts file](https://www.makeuseof.com/tag/modify-manage-hosts-file-linux/)
- [Netcat examples](https://www.thegeekstuff.com/2012/04/nc-command-examples/)

**man or help:**
- ifconfig
- telnet
- nc
- cut


## Important lesson
- Learnt about how to find host files in linux with `sudo vi /etc/hosts`
- how to modify host files, block host files and create shorcut for host files by assigning it a host name.
	
	* block host file by changing ip address to a loopback address(127.0.0.1) e.g - `127.0.0.1        wikipedia.org`
- Learnt about Linux Netcat NC Commands, how to perform port listening for incoming connections, transfer files and others.
- Learnt the default route for IPv4 and IPV6 respectively - `0.0.0.0` && `::0`
- Learnt the local host for IPv4 and IPV6 respectively - `127.0.0.1` && `::1`
- **NB** - In IPv4, the loopback IP addresses are from 127.0.0.0 - 127.255.255.255. But 127.0.0.1 is most often used.

