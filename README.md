## NAME:Swetha N
## REG.NO:212222110050
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
![image](https://github.com/user-attachments/assets/8c122a1d-cfb6-4bc2-a733-c172e88d49d9)



From kali linux issue the command :sudo arpspoof -i eth0 -t

## OUTPUT:
![image](https://github.com/user-attachments/assets/d1ea74ef-8e44-43b4-ac4f-64abe939fc1a)


In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/user-attachments/assets/c95600ba-cfa0-4cc2-9b8a-ffabf94462aa)

In Parrot issue the following commands: sudo dsniff
## OUTPUT:
![image](https://github.com/user-attachments/assets/1c1ea2ef-9190-44e2-b3b7-a653ba1c6ba8)


Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/user-attachments/assets/670b430a-4bb6-44b0-a5c8-c05e6dbdfb18)



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
