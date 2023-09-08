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

### OUTPUT:

![image](https://github.com/Poojithamanohar/ARP-Attack-and-Network-Sniffing/assets/119423592/48171bbc-3dac-4dd4-8dd7-b291c2d7bd34)



From kali linux issue the command : sudo arpspoof -i eth0 -t

### OUTPUT:

![image](https://github.com/Poojithamanohar/ARP-Attack-and-Network-Sniffing/assets/119423592/15f0d2aa-77e8-480c-a1ea-829cfe507cee)



In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
### OUTPUT:



![image](https://github.com/Poojithamanohar/ARP-Attack-and-Network-Sniffing/assets/119423592/2864d64b-7d5e-4458-ae6d-ff2cc0e5ec35)

In Kali issue the following commands: sudo dsnifff


### OUTPUT:


![image](https://github.com/Poojithamanohar/ARP-Attack-and-Network-Sniffing/assets/119423592/27f255e2-e499-49cf-bc3a-b9d2b9a1e7e4)



Invoke the wireshark and examine the various menus and controls of the tool:

![image](https://github.com/Poojithamanohar/ARP-Attack-and-Network-Sniffing/assets/119423592/6dec4daf-227e-4e29-a544-e98eee4e86c0)

### RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully




