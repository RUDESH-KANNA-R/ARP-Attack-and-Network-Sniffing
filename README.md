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
![image](https://github.com/user-attachments/assets/3eedebe5-ea85-4d86-9811-4318cc09f7da)


From kali linux issue the command :
```
sudo arpspoof -i eth0 -t <target system> <gateway>
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/9d6803e6-f6a8-431b-83bd-9fe9b83d0c7b)

## dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![436639640-f8ffa4a7-9b3d-4b74-b641-2c392b78a74f](https://github.com/user-attachments/assets/c1599420-84ca-4704-add9-52e69692fa88)

In Kali issue the following commands:
```
sudo dsnifff
```
m![436639819-70052e7a-ef74-4ec9-a46f-2fefd915f6af](https://github.com/user-attachments/assets/73b502c3-d13d-4fff-924e-960ce5b2cdaf)

## OUTPUT:
![436639819-70052e7a-ef74-4ec9-a46f-2fefd915f6af](https://github.com/user-attachments/assets/dda12a47-167e-4d6e-ade1-39a15df3426e)

Invoke the wireshark and examine the various menus  and controls of the tool:
![436639966-60ccccfa-a535-494e-bf93-30bdf93523dc](https://github.com/user-attachments/assets/d7f9d637-39c0-48c4-bacd-0ed31cf6c708)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
