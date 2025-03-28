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

![WhatsApp Image 2025-03-28 at 22 24 35_458fbad9](https://github.com/user-attachments/assets/7aae80a1-513d-4028-97c0-5891387441cd)

![WhatsApp Image 2025-03-28 at 22 24 49_0a52b363](https://github.com/user-attachments/assets/f1504361-e3cd-46e6-932b-1654bd2c0a5f)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

 dsniff:

![WhatsApp Image 2025-03-28 at 22 24 49_0a52b363](https://github.com/user-attachments/assets/8d9063ea-6f0a-4047-aeb8-fb0e8aa7cf8f)


In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:


![WhatsApp Image 2025-03-28 at 22 25 28_7ffd5260](https://github.com/user-attachments/assets/9a88676a-c8c0-4865-89d7-4ff3409984d3)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![WhatsApp Image 2025-03-28 at 22 25 40_e69afcc7](https://github.com/user-attachments/assets/f3a0c098-2f5b-4b1d-b7fa-8981e75eb068)


Invoke the wireshark and examine the various menus  and controls of the tool:

![WhatsApp Image 2025-03-28 at 22 26 07_a20b6466](https://github.com/user-attachments/assets/8685e1bb-39ba-469e-aa44-922e6628f6be)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
