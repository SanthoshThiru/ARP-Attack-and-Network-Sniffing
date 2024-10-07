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
![Screenshot 2024-10-07 153521](https://github.com/user-attachments/assets/c0dfbff0-a25a-4437-82ae-3a9d57c5d230)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![Screenshot 2024-09-30 154937](https://github.com/user-attachments/assets/e0196d6c-3921-40ee-8f1a-b391bd2f3303)


 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/user-attachments/assets/a8758039-1a76-48ac-aadc-aa1f170879cf)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![image](https://github.com/user-attachments/assets/6d361b52-f005-451c-88e7-6f5489e97179)


Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/user-attachments/assets/7128b672-a90e-437e-b9d2-156725716cfe)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
