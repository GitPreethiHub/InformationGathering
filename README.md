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


## OUTPUT:
Whois lookup:
![image](https://github.com/user-attachments/assets/cf376bb4-fec6-435e-a13d-077bf198821e)

Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
## output
![image](https://github.com/user-attachments/assets/1c5c2c6b-19c6-4329-aa3b-9329b99eda66)

Finding Hosting Company:
using ip2location.com website.

## output
![image](https://github.com/user-attachments/assets/96ce64ba-31e8-4ae6-abcf-4dc87de0cf25)

History of the website:
https://web.archive.org/

## output
![image](https://github.com/user-attachments/assets/83c99233-b735-446a-b336-3b6f7b2f40cd)

# Webserver Fingerprinting:
## Netcat:
sudo nc saveetha.ac.in 443
GET / HTTP/1.1

### output
![image](https://github.com/user-attachments/assets/f1e48ebe-7899-4a2e-bb7b-ad6d20e5b1f6)

## nmap:
### output
![image](https://github.com/user-attachments/assets/ddc82c31-bd79-455e-ada2-31032bb29b04)

## Whatweb
### output
![image](https://github.com/user-attachments/assets/cf31b800-66b3-41c6-b405-5c72df579065)

![image](https://github.com/user-attachments/assets/4c6cb597-139d-49e2-a59f-8af95af884e2)
## httprint
### output
![image](https://github.com/user-attachments/assets/9f1c87e1-9360-4a8a-9360-b6083173989e)

# Tracing the Location
### TCP Traceroute:
sudo traceroute -T www.google.com
## output
![image](https://github.com/user-attachments/assets/ef89ebb5-f2c4-4f29-b11b-197fa77ae7df)

### UDP Traceroute:
sudo traceroute -U www.google.com
## output
![image](https://github.com/user-attachments/assets/b3cd3908-9f52-4e46-ba35-90f54756052d)


### ICMP Traceroute:
sudo traceroute  www.google.com
## output
![image](https://github.com/user-attachments/assets/70a66535-6b0a-4a7d-a0d0-966a72f9f782)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
