# Metasploit-for-reconnaissance
# Metasploit
Metasploit for reconnaissance in pentesting

# AIM:

To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:

Find out the ip address of the attackers system

OUTPUT:

![Screenshot 2025-03-28 135513](https://github.com/user-attachments/assets/12b23cec-0f17-4376-b645-c1d1783a02bc)

Invoke msfconsole

OUTPUT:

![Screenshot 2025-03-28 132126](https://github.com/user-attachments/assets/52e5bfd2-c560-4657-b18b-43cb72032266)

Type help or a question mark "?" to see the list of all available commands you can use inside msfconsole.

![435553906-079b649b-b9c2-434c-ae97-baba1ffe83fc](https://github.com/user-attachments/assets/97e0dea9-819f-4114-af2e-9a0c3139fae8)

PORT SCANNING

msf > nmap -sT 192.168.1.100/24 -p1-1000

![435554409-b7f3d688-974f-481d-9186-a331b1628cbe](https://github.com/user-attachments/assets/9e83208d-025a-49c0-9094-6e4e81b70986)

PORT SCANNING
msf > db_nmap -sT 192.168.1.100/24

![435554907-a1d3fa3c-3e52-439b-9442-33705ae44e73](https://github.com/user-attachments/assets/eca7662a-9f20-4669-aba6-f58bb20a1204)

kali ls -l

![Screenshot 2025-04-21 110944](https://github.com/user-attachments/assets/8c37a892-693c-4170-ba5f-81e28bc84554)

search

![435555364-3bf64e21-323d-410d-adcb-d037146df215](https://github.com/user-attachments/assets/f9f0d621-8165-4484-86d1-7581d9eae13c)

info

![435555583-2e121d08-57c9-4894-971f-bf6800f4cdc7](https://github.com/user-attachments/assets/27bfa8b1-6d77-4824-921a-06c4e1f51538)


MYSQL ENUMERATION

db_nmap -sV -sC -p 3306 <metasploitable_ip_address>

![435555822-9d2428aa-bba5-4783-b322-a658552b5b4e](https://github.com/user-attachments/assets/b5c1389b-5ef9-41e4-b93a-2cf1e8534054)

search

![435555939-d5e12707-9f73-4422-9a24-7175dc37dc15](https://github.com/user-attachments/assets/e4d9c6f7-c280-499d-bec3-e40d94412907)

use 11 Or: use auxiliary/scanner/mysql/mysql_version

![435556025-0b58f28c-89b4-40ee-8a82-f5fb61fe73f9](https://github.com/user-attachments/assets/8e416faa-6015-4547-95a8-816b59b7ccfe)

use 11 Or: use auxiliary/scanner/mysql/mysql_version

![435556025-0b58f28c-89b4-40ee-8a82-f5fb61fe73f9](https://github.com/user-attachments/assets/3ab0882c-8e13-4201-9aca-5e96a4761b30)

Use the set rhosts command to set the parameter and run the module, as follows:

![435556087-9f910374-df42-4001-a552-fccaa4510d7b](https://github.com/user-attachments/assets/b0d20328-fc9c-4ed5-828a-294e77debe21)

After scanning, you can also brute force MySQL root account via Metasploit's auxiliary(scanner/mysql/mysql_login) module.

![435556181-17c637ee-f95f-4000-93d5-d0c61831a5b6](https://github.com/user-attachments/assets/f50820d8-d1ba-4a0d-800c-2d7ebd6d66b2)

/usr/share/wordlists: set PASS_FILE /usr/share/wordlistss/rockyou.txt

![435556261-790829a8-ea62-418e-a0e0-a044551c9d0a](https://github.com/user-attachments/assets/b3b3a1ea-40c6-4ec3-aeca-3494acc3ea23)
![435556289-35500dc6-51f0-4ad4-bbd1-401517856bcb](https://github.com/user-attachments/assets/47969455-0dff-4711-8e4e-b9b4fe41a07c)


## RESULT:
The Metasploit framework for reconnaissance is  examined successfully
