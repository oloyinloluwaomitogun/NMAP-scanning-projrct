# NMAP-scanning-projrct
This project is aimed at identifying devices in a network, uncovering open ports, and checking for  Vulnerabilities

### Step 1
To scan our devioce (host) for open ports, we need to identify its IP address
**Procedures**
* Start NMAP from the CMD terminal
* tyoe "ipconfig". This will display all IP addressess: select the interface you are using, in this case, the wireless interface

  <img width="1640" height="425" alt="image" src="https://github.com/user-attachments/assets/eda2734d-4ca8-4b8a-bb85-df6750bf698a" />

### Step 2 - Finding Your Network Range
To find your network range and determine all the IP addresses that are currently connected to the same network(subnet). Type map -sn  10.174.239.0/24. Since the host IP is  10.174.239.73, then the network is 10.174.239.0

<img width="1908" height="1104" alt="image" src="https://github.com/user-attachments/assets/639f2d98-a870-4c7b-bbf0-a5e171a08548" />
