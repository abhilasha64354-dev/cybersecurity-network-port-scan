### &#x20;*Cyber Security Internship Task 1*



#### &#x20;Project Title

#### 

###### **Local Network Port Scanning using Nmap**



* &#x20;**Objective**



To scan the local network and identify open ports using Nmap.



* ###### **Tool Used**



\* Nmap



* &#x20;**Command Used**



nmap -sS 192.168.1.0/24 -oN results.txt



* &#x20;**Scan Results**



1. Router (192.168.1.1)



Open Ports:



\* 23/tcp (Telnet)

\* 53/tcp (DNS)

\* 80/tcp (HTTP)

\* 443/tcp (HTTPS)



2\. Xiaomi Device (192.168.1.7)



\* No open TCP ports detected



3\. Local Machine (192.168.1.9)



Open Ports:



\* 135/tcp (MSRPC)

\* 139/tcp (NetBIOS)

\* 445/tcp (Microsoft-DS)



* **Security Analysis**



Open ports expose network services to communication. Services like Telnet may pose security risks if improperly secured.



* &#x20;**Conclusion**



This task helped me understand port scanning, TCP SYN scans, and network reconnaissance using Nmap.



