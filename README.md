# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

# Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

# OUTPUT:
![image](https://github.com/sachinezhilmaran/InformationGathering/assets/128135351/b8fdeef0-fbf3-41bc-9ca3-2ec99bb361cc)

# Finding IP adress:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.

ping saveetha.ac.in

# Output:
![image](https://github.com/sachinezhilmaran/InformationGathering/assets/128135351/38da04b9-a9c4-4650-aa46-aa429e9579ff)

# Finding Hosting Company:
get further detail by using ip2location.com website.

# Output:
![image](https://github.com/sachinezhilmaran/InformationGathering/assets/128135351/4cc21446-6686-4c20-8491-564fa7d03418)

# History of the wbsite:
# Output:
https://web.archive.org/
![image](https://github.com/sachinezhilmaran/InformationGathering/assets/128135351/4ababe18-a4c9-4cfe-95f6-a3d93a6d8cda)

# Web server Fingerprint:
# Netcat:
nc 172.17.52.118 80
# Output:
![image](https://github.com/sachinezhilmaran/InformationGathering/assets/128135351/d2bf1128-3768-47eb-aaf3-effabf123cda)

# nmap:
nmap -p 21 -sV --script=banner ftp.vim.org
# Output
![image](https://github.com/sachinezhilmaran/InformationGathering/assets/128135351/8b940a71-f9af-4d1b-97af-57da2fecb56e)

# Whatweb:
whatweb infosys.com
whatweb zoho.com
whatweb -v -a 3 172.17.52.201
# Output
![image](https://github.com/sachinezhilmaran/InformationGathering/assets/128135351/e9d6f44a-08be-4261-a3e7-c5daf3b18609)
# httprint:
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
# Output
![image](https://github.com/sachinezhilmaran/InformationGathering/assets/128135351/6cc88808-b382-4729-9dc4-42075c12d0c0)
# Tracing the Location:
# TCP Traceroute:
sudo traceroute -T www.saveetha.ac.in
# Output:
![image](https://github.com/sachinezhilmaran/InformationGathering/assets/128135351/3b34f895-be69-430c-b0cc-23d00001f97c)
# UDP Traceroute:
sudo traceroute -U www.saveetha.ac.in
# Output:
![image](https://github.com/sachinezhilmaran/InformationGathering/assets/128135351/d8634523-2106-4de4-a520-ee1665aaae5d)

# ICMP Traceroute:
sudo traceroute  www.saveetha.ac.in
# Output:
![image](https://github.com/sachinezhilmaran/InformationGathering/assets/128135351/1c43d216-0aae-4d8c-8e4b-7e1e9aabf4b0)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
