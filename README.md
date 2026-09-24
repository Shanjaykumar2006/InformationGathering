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

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:

<img width="525" height="342" alt="image" src="https://github.com/user-attachments/assets/d174f23a-c229-489b-9be9-f125de802e5c" />



## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
##output

<img width="516" height="297" alt="image" src="https://github.com/user-attachments/assets/9aa55559-94bc-4c1a-947d-7f7d5d6c25cf" />

## Finding Hosting Company
get further detail by using ip2location.com website.
##output

<img width="1422" height="810" alt="image" src="https://github.com/user-attachments/assets/93c14c16-1c92-486f-8cd1-6187bcd6e860" />




## History of the website:
## output
https://web.archive.org/

<img width="1919" height="1026" alt="image" src="https://github.com/user-attachments/assets/41669dbb-bc1a-4a15-a1fa-6cc0ee77aae0" />



# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com

<img width="286" height="252" alt="image" src="https://github.com/user-attachments/assets/fb1efec6-8444-4b7b-a62b-025e96b5535c" />


## nmap:
###output
<img width="417" height="231" alt="image" src="https://github.com/user-attachments/assets/6b18193f-4e3f-4680-993a-77130c2fac75" />


## Whatweb
### output
<img width="423" height="245" alt="image" src="https://github.com/user-attachments/assets/569a147d-2132-44f4-a120-86403ddf76af" />


## httprint
### output


<img width="270" height="227" alt="image" src="https://github.com/user-attachments/assets/c40ace5c-4344-4f4a-a3b2-2c267c16eeb2" />


# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output
<img width="266" height="207" alt="image" src="https://github.com/user-attachments/assets/e15dbc50-6316-4a95-9f61-c74c4a907227" />


## UDP Traceroute:
sudo traceroute -U www.google.com
## output

<img width="231" height="210" alt="image" src="https://github.com/user-attachments/assets/6e16ae4a-7078-4344-a4b3-738259c532bb" />



## RESULT:
The information gathering techniques tools/procedure were  identified successfully
