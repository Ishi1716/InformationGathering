# Ex-02 InformationGathering
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

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:

### Whois

<img width="1914" height="1136" alt="Screenshot 2025-08-18 091953" src="https://github.com/user-attachments/assets/a9366f5f-634e-44bd-b4b0-2f466c406839" />

### Finding Hosting Company :

<img width="1917" height="1139" alt="Screenshot 2025-08-18 092100" src="https://github.com/user-attachments/assets/4a072067-c02c-43ca-9f51-12c567e980d7" />

### History of the website :

<img width="1919" height="1141" alt="Screenshot 2025-08-18 092252" src="https://github.com/user-attachments/assets/c6ca299c-ff52-43d1-8a04-b08594372a57" />

### ping command :

![ping](https://github.com/user-attachments/assets/fee10e8f-2545-4799-8e59-27ef66a451bd)

### netcat :

![netcat](https://github.com/user-attachments/assets/94398316-d691-43c0-af8f-7decd80e2ad7)

### nmap :

![nmapppp](https://github.com/user-attachments/assets/1e491f89-32b4-4784-8189-b39034fac82c)

### whatweb :

![whatweb](https://github.com/user-attachments/assets/84702f82-f530-41e4-9e1d-4b785be81977)


### httprint :

![httprint](https://github.com/user-attachments/assets/ba19cd03-95f6-4a7b-80d4-562753f56d91)


### TCP traceroute & UDP traceroute :

<img width="1920" height="1057" alt="traceroute" src="https://github.com/user-attachments/assets/87e87259-4d35-476f-91e1-61c1a286f46c" />

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
