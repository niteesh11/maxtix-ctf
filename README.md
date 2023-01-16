Hack the  Maxtrix Vul Lab  

To download the Lab using This Link 

https://drive.google.com/file/d/132c9QkbhP_Bffn8afwdYAh_sNJXlKej2/view?usp=share_link

import using virtualbox


Goal:

	The goal is to exploit a file upload vulnerability and escalate privileges in order to find two
	flags that are stored in the Neo user's directory ('flag1.txt' and 'flag2.txt').


Penetration Methodology:

Network Scanning

	  ● Nmap
  
	  ● Netdiscover
  
Enumeration

	● Dirb
  
Bruteforce

 	 ● Burp suite
  
Exploitation

 	 ● Msfvenom
  
  	● Msfconsole
  
Privilege Escalation

	  ● ssh
  
	  ● python hijacking
  
  
  
The Steps:

	The summary of the steps required in solving this CTF are given below:


1. Get the target machine IP address by running Netdiscover.

2. Scan open ports by using the Nmap scanner.

3. Enumerate HTTP service with Dirb.

4. Brute-force on the admin page with burp.

5. Exploit file upload vulnerability.

6. Gain access to ssh.

7. Escalation privilege to get root access.
