# Hack The Box Lab Writeups

Starting out in Cybersecurity, HackTheBox (HTB) has been the go-to resource provided to me or anyone interested in Penetration Testing and Ethical Hacking for that matter. 

## Contents

1. [Explore - Android (Easy)](Explore/Readme.md)
2. [Lame - Linux (Easy)](Lame/Readme.md)
3. [Shocker - Linux (Easy)](Shocker/Readme.md)
4. [Nibbles - Linux (Easy)](Nibbles/Readme.com)
5. [Bashed - Linux (Easy)](Bashed/Readme.md)
6. [Valentine - Linux (Easy)](Valentine/Readme.md)
7. [Beep - Linux (Easy)](Beep/Readme.md)
8. [Swagshop - Linux (Easy)](Swagshop/Readme.md)
9. [Sense - Linux (Easy)](Sense/Readme.md)
10. [Knife - Linux (Easy)](Knife/Readme.md)
11. [Armageddon - Linux (Easy)](Armageddon/Readme.md)
12. [ScriptKiddie - Linux (Easy)](ScriptKiddie/Readme.md)
13. [OpenAdmin - Linux (Easy)](OpenAdmin/Readme.md)
## Retired Machines vs Active Machines

HTB's Active Machines are free to access, upon signing up. Accessing the retired machines, which come with a HTB issued walkthrough PDF as well as an associated walkthrough from [Ippsec](https://www.youtube.com/c/ippsec) are exclusive to paid [subscribers](https://www.hackthebox.com/newsroom/vip-plus).

HackTheBox doesn't provide writeups for Active Machines and as a result, I will not be doing so either. Having said that, I *might* include some later on, albeit password-protected PDF's to maintain integrity. 

## HackTheBox in relation to OSCP Prep

Another reason for myself attempting the boxes on the HTB platform is to help me prepare for the [OSCP](https://www.offensive-security.com/pwk-oscp/) course & exam. As a result, my writeups will have an additional vector to root machines - **manual** exploitation and privilege escalation in addition to automated exploitation with tools like Metasploit, which are not allowed in the OSCP exam. 

### Accessing the VM's 

The HTB platform uses an OpenVPN connection to access the labs and machines. Once signed up, the connection pack can be downloaded as an `.ovpn` file and imported using the OpenVPN client.

## TJnull's OSCP Prep VM's

[TJnull](https://www.netsecfocus.com/oscp/2021/05/06/The_Journey_to_Try_Harder-_TJnull-s_Preparation_Guide_for_PEN-200_PWK_OSCP_2.0.html) and the team at NetSec Focus  have compiled a list of HackTheBox VM's that are a pathway to getting started, building practical skills and preparing for the OSCP in the [HTB tab](https://docs.google.com/spreadsheets/u/1/d/1dwSMIAPIam0PuRBkCiDI88pU3yzrqqHkDtBngUHNCw8/htmlview#).

I have extracted the table and fed it into this repository and will be ticking off the columns as I move down the line. 

### Linux VM's

| Linux   Boxes | Difficulty |                                                Tags                                                | Completed |
|:-------------:|:----------:|:--------------------------------------------------------------------------------------------------:|:---------:|
|               |            |                                                                                                    |           |
|     Lame      |    Easy    |                                       Injection, CMS Exploit                                       | Completed |
|   Brainfuck   |   Insane   |                                            Cryptography                                            |           |
|    Shocker    |    Easy    |                                 Perl, Injection, Web -   Shellshock                                | Completed |
|     Bashed    |    Easy    |                                     File Misconfiguration, Web                                     | Completed |
|    Nibbles    |    Easy    |                             File Misconfiguration, Web -   Nibble Blog                             | Completed |
|      Beep     |    Easy    |                                 LFI, Web - /vtigercrm in   Elastix                                 | Completed |
|     Cronos    |   Medium   |                              PHP, SQL, DNS Zone Transfer,   SQLi, Web                              |           |
|    Nineveh    |   Medium   |                                   PHP,   Port Knocking, LFI, Web                                   |           |
|     Sense     |    Easy    |                                       FreeBSD, Injection, Web                                      | Completed |
|   Solidstate  |   Medium   |                                     File Misconfiguration, Web                                     |           |
|    Kotarak    |    Hard    |                                     Arbitrary File Upload, Web                                     |           |
|      Node     |   Medium   |                           API Fuzzing, JSON, File   Misconfiguration, Web                          |           |
|   Valentine   |    Easy    |                                        Patch Management, Web                                       | Completed |
|     Poison    |   Medium   |                                 PHP, Log Poisoning, FreeBSD,   Web                                 |           |
|     Sunday    |    Easy    |                                   Solaris, File Misconfiguration                                   |           |
|  Tartaresauce |   Medium   |                                     C, Sandbox Escape, RFI, Web                                    |           |
|     Irked     |    Easy    |                                          Cryptography, Web                                         |           |
|   Friendzone  |    Easy    |                        LFI, DNS Zone Transfer, File   Misconfiguration, Web                        |           |
|    Swagshop   |    Easy    |                                           SQL, SQLi, Web                                           | Completed |
|   Networked   |    Easy    |                            PHP, Arbitrary File Upload,   Injection, Web                            |           |
|     Jarvis    |   Medium   |                                      SQL, SQLi, Web, Injection                                     |           |
|     Mirai     |    Easy    |                     Linux, Network, Default Creds,   File System Forensics, Web                    |           |
|    Popcorn    |   Medium   |                                              PHP, Web                                              |           |
|    Haircut    |   Medium   |                                         PHP, Injection, Web                                        |           |
|     Blocky    |    Easy    |                                              PHP, Web                                              |           |
|     Frolic    |    Easy    |                                           C, Cryptography                                          |           |
|    Postman    |    Easy    |                                     File Misconfiguration, Web                                     |           |
|     Mango     |   Medium   |                                         PHP, Injection, Web                                        |           |
|   Traverxec   |    Easy    |                                     File Misconfiguration, Web                                     |           |
|   OpenAdmin   |    Easy    |                                     File Misconfiguration, Web                                     | Completed |
|     Magic     |   Medium   |                            PHP, SQLi, SQL, Arbitrary File   Upload, Web                            |           |
|    Admirer    |    Easy    |                                              SQL, Web                                              |           |
|    Blunder    |    Easy    |                           Windows, Bash, Account   Misconfiguration, Web                           |           |
|     Tabby     |    Easy    |                        Bash, Account   Misconfiguration, Sandbox Escape, Web                       |           |
|     Doctor    |    Easy    |                   Bash, SSTI, Outdated Software,   Account Misconfiguration, Web                   |           |
|  SneakyMailer |   Medium   |                                    Bash, Client Side Attack, Web                                   |           |
|    Passage    |   Medium   |                                 Bash, File Misconfiguration,   Web                                 |           |
|     Luanne    |    Easy    |                     Bash, Injection, Web Fuzzing,   File Misconfiguration, Web                     |           |
|      Time     |   Medium   |                      JavaScript, Deserialization,   File Misconfiguration, Web                     |           |
|     Ready     |   Medium   |                                   Bash, Account Misconfiguration                                   |           |
|    Delivery   |    Easy    |                                   Bash, Account Misconfiguration                                   |           |
|    Ophiuchi   |   Medium   |                         Java, Deserialization, Golang,   Source Code Review                        |           |
|  ScriptKiddie |    Easy    |                                          Outdated Software                                         | Completed |
|   Armageddon  |    Easy    |        Outdated   Software, Linux, Web, PHP, CMS Exploit, Password Reuse, CVE, Weak Password       | Completed |
|     Knife     |    Easy    |                                       PHP, GTFOBins, Backdoor                                      | Completed |
|      Pit      |   Medium   | PHP,   Bash, CMS Exploit, Arbitrary File Upload, Outdated Software, Process   Inspection, RCE, CVE |           |
|  Seal (Linux) |   Medium   |                                        File Misconfiguration                                       |           |

### Windows VM's


| Windows   Boxes 	| Difficulty 	|                                   Tags                                  	| Completed 	|
|:---------------:	|:----------:	|:-----------------------------------------------------------------------:	|:---------:	|
|                 	|            	|                                                                         	|           	|
|      Legacy     	|    Easy    	|                         Injection, Eternal Blue                         	|           	|
|       Blue      	|    Easy    	|                      Patch Management, Eternal Blue                     	|           	|
|      Devel      	|    Easy    	|                        FTP, Arbitrary File Upload                       	|           	|
|     Optimum     	|    Easy    	|                                   Web                                   	|           	|
|     Bastard     	|   Medium   	|                        PHP, Patch Management, Web                       	|           	|
|      Granny     	|    Easy    	|                          Patch Management, Web                          	|           	|
|      Arctic     	|    Easy    	|               Arbitrary File Upload, Patch Management, Web              	|           	|
|     Grandpa     	|    Easy    	|                          Patch Management, Web                          	|           	|
|       Silo      	|   Medium   	|                          Arbitrary File Upload                          	|           	|
|      Bounty     	|    Easy    	|                    VBScript. C, Patch Management, Web                   	|           	|
|      Jerry      	|    Easy    	|            Arbitrary File Upload, File Misconfiguration, Web            	|           	|
|     Conceal     	|    Hard    	|                         C, Arbitrary File Upload                        	|           	|
|    Chatterbox   	|   Medium   	|                                Powershell                               	|           	|
|      Forest     	|    Easy    	|          Kerberoasting, Powershell, Active Directory, Windows           	|           	|
|    BankRobber   	|   Insane   	|               Windows, C, XSS, LFI, SQLi, JavaScript, Web               	|           	|
|     Secnotes    	|   Medium   	|              CSRF, Windows, SQL, PHP, Powershell, SQLi, Web             	|           	|
|     Bastion     	|    Easy    	|                Windows, Powershell, File Misconfiguration               	|           	|
|       Buff      	|    Easy    	|                         Windows, Powershell, Web                        	|           	|
|     Servmon     	|    Easy    	|                  Windows, Powershell, API Fuzzing, Web                  	|           	|
|      Active     	|    Easy    	|           Windows, Kerberoasting, Active Directory, Powershell          	|           	|
|      Remote     	|    Easy    	|                               Windows, Web                              	|           	|
|       Fuse      	|   Medium   	|                  Windows, Powershell, Active Directory                  	|           	|
|       Omni      	|    Easy    	|            Powershell, Patch Management, File Misconfig, Web            	|           	|
|      Worker     	|   Medium   	|                     Windows, Powershell, Cloud, Web                     	|           	|
|       Love      	|    Easy    	|                Windows, CVE, SSRF, RCE, AppLocker Bypass                	|           	|
|   Intelligence  	|   Medium   	| Windows, Active Directory, Network, Weak Password,   Kerberoasting, SMB 	|           	|
|       APT       	|   Insane   	|                           Windows, Powershell                           	|           	|