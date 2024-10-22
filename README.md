### REG.NO:212222110050
### NAME:SWETHA N
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
![image](https://github.com/user-attachments/assets/a8ae50cc-6534-4d16-97a1-b3cec8fa7adf)

From kali linux issue the command : sudo arpspoof -i eth0 -t
## OUTPUT:
![image](https://github.com/user-attachments/assets/07d72b2d-3701-4784-a048-747b5dc0736f)


 dsniff:In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

## OUTPUT:
![image](https://github.com/user-attachments/assets/ebc17a33-534d-4321-bff2-b6bec9054cde)

In Kali issue the following commands:sudo dsnifff
## OUTPUT:
![image](https://github.com/user-attachments/assets/76eaa89c-e1ac-474b-882d-5105d4ab96bc)


Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/user-attachments/assets/7fda6261-d6d4-4585-8fc4-8286e90215f4)



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
