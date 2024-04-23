# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:

![1 e](https://github.com/sathyaa22/ARP-Attack-and-Network-Sniffing/assets/140483368/78242b98-467b-409d-b9f2-cda67d8042a7)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![2 e](https://github.com/sathyaa22/ARP-Attack-and-Network-Sniffing/assets/140483368/30eca18f-99ff-4abb-b68e-86d64d2efc06)

dsniff: In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![3 e](https://github.com/sathyaa22/ARP-Attack-and-Network-Sniffing/assets/140483368/b37e7292-9370-4a6e-adeb-0e1601c05a28)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![4 e](https://github.com/sathyaa22/ARP-Attack-and-Network-Sniffing/assets/140483368/15314f77-96e1-4aae-89a1-c90b4f28b61a)

Invoke the wireshark and examine the various menus  and controls of the tool:

![5 e](https://github.com/sathyaa22/ARP-Attack-and-Network-Sniffing/assets/140483368/8710a695-5396-49d4-93a1-a06df8a06e5b)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
