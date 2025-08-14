# NMAP-scanning-projrct
This project is aimed at identifying devices in a network, uncovering open ports, and checking for  Vulnerabilities

### Step 1
To scan our devioce (host) for open ports, we need to identify its IP address
**Procedures**
* Start NMAP from the CMD terminal
* tyoe "ipconfig". This will display all IP addressess: select the interface you are using, in this case, the wireless interface

  <img width="1640" height="425" alt="image" src="https://github.com/user-attachments/assets/eda2734d-4ca8-4b8a-bb85-df6750bf698a" />
---------

### Step 2 - Finding Your Network Range
To find your network range and determine all the IP addresses that are currently connected to the same network(subnet). Type map -sn  10.174.239.0/24. Since the host IP is  10.174.239.73, then the network is 10.174.239.0

<<img width="1908" height="680" alt="image" src="https://github.com/user-attachments/assets/adcb1376-f630-4b89-92ac-98cbfd5a6344" />

-----------
### Step 3 - Scan for open ports
This step involves identifying opem ports on the host machine that can lead to an attack or security breach 
**Procedures**
* Select any of the IP address in the network
* Use this map conmand to identify open ports (Nmap< HostIPAddress >).

<img width="1813" height="270" alt="image" src="https://github.com/user-attachments/assets/e12c90e3-56af-44f4-9f37-477d29b5c9a7" />
  
--------

### Step 4 - Identify services
This step involves identifying services on the host machine (Target).
To Acheive this with Nmap, we used the following command: nmap -sV <TargetIPAddress>

<img width="1472" height="300" alt="image" src="https://github.com/user-attachments/assets/361d17f2-effa-41e3-90b6-508fb3dfeb51" />

----------

### Step 5 - Doiscoverind Service Version Vulnerabilities 
We sellected one of the identified services ans searched for the version's vulnerabilities:Microsoft Windows RPC
Below are the result and mitigration recommendation

<img width="1058" height="563" alt="image" src="https://github.com/user-attachments/assets/76e8e640-e595-4eb7-9bb5-b93877cfa30f" />

