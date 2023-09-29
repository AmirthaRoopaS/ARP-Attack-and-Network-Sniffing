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
![image](https://github.com/AmirthaRoopaS/ARP-Attack-and-Network-Sniffing/assets/143496311/2e9153fe-de97-4f5c-9269-a429705f1cf5)



From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/AmirthaRoopaS/ARP-Attack-and-Network-Sniffing/assets/143496311/3ee07b80-32ff-449f-966d-2a98c1e3124a)



 ## dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/AmirthaRoopaS/ARP-Attack-and-Network-Sniffing/assets/143496311/70fbcc9b-0c36-44ef-aa9f-ff6fe43c9f07)





In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/AmirthaRoopaS/ARP-Attack-and-Network-Sniffing/assets/143496311/e650e1b0-e833-4495-8ccc-5c9cd20c91a4)




Invoke the wireshark and examine the various menus  and controls of the tool:

## OUTPUT:
![image](https://github.com/AmirthaRoopaS/ARP-Attack-and-Network-Sniffing/assets/143496311/c33dac15-1c86-47e4-83fe-38bd598c1c79)

## Ettercap
Ettercap supports active and passive dissection of many protocols (even encrypted ones) and includes many feature for network and host analysis.
Ettercap can be used as sniffing tool as illustrated below:

## OUTPUT:
![image](https://github.com/AmirthaRoopaS/ARP-Attack-and-Network-Sniffing/assets/143496311/1b9b94c4-def8-4b38-b97b-be1e88b91c9a)





## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
