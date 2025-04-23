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
![Screenshot 2025-04-23 194721](https://github.com/user-attachments/assets/82128970-72fd-4e04-af9b-96aa540a81c5)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![434629295-208f35fb-13f8-4e8c-af7c-f007d8515033](https://github.com/user-attachments/assets/0ea65081-faec-418d-ae12-807e8417344b)


 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![434629353-a0f3370d-7ebc-442a-be4c-3e918a03c507](https://github.com/user-attachments/assets/ede97145-920f-45b2-8087-0c772258d212)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![Screenshot 2025-03-15 141657](https://github.com/user-attachments/assets/50b93264-f9ee-4311-a6be-5bd22b4ade25)


Invoke the wireshark and examine the various menus  and controls of the tool:
![Screenshot 2025-04-23 195840](https://github.com/user-attachments/assets/e3c69d96-f14b-42af-bdc0-91c14d5fa0c7)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
