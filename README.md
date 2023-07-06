[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/not-a-bug-a-feature.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/makes-people-smile.svg)](https://forthebadge.com)
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=blue" height=35 width=110>

<br>


## This Repo Inspired By ``` SANJAY GODAWAT ```  :green_heart: and :star: the Repo To SUPPORT
- [@sanjay](https://github.com/sanjaygodawat0)
<br>


## DOWNLOAD
### [Kali Linux](https://www.kali.org/downloads/) &nbsp; &nbsp; :dragon:   <br>
### [Parrot OS](https://parrotsec.org/download/) &nbsp;&nbsp; :parrot:   <br>

<br><br>

<!-- ## What is Hacking? :space_invader:
 #### <i>Hacking is identifying weakness in computer systems or networks to exploit its weaknesses to gain access.</i>
 <p>Hacking can be carried out in many ways. The most common form is the phishing scam, where hackers attempt to gain login names and passwords, or introduce malware into networked computing environments, by tricking users into opening an email attachment or forwarding private information.
Some of the most serious breaches of recent years, including the Wannacry malware attack, began as phishing scams, affecting not just the target enterprise but associated partners, customers, government agencies and others.</p>
<br>

## Who is a hacker? :man_technologist:
<p>A Hacker is a person who finds and exploits the weakness in computer systems and/or networks to gain access. Hackers are usually skilled computer programmers with knowledge of computer security.
Hackers are classified according to the intent of their actions. The following list classifies hackers according to their intent.</p>

* [White hat](https://en.wikipedia.org/wiki/White_hat_(computer_security)) &nbsp; A hacker who gains access to systems with a view to fix the identified weaknesses. They may also perform penetration Testing and vulnerability assessments
* [Black hat](https://en.wikipedia.org/wiki/Black_hat_(computer_security)) &nbsp; A hacker who gains unauthorized access to computer systems for personal gain. The intent is usually to steal corporate data, violate privacy rights, transfer funds from bank accounts etc.
* [Grey hat](https://en.wikipedia.org/wiki/Grey_hat) &nbsp; A hacker who is in between ethical and black hat hackers. He/she breaks into computer systems without authority with a view to identify weaknesses and reveal them to the system owner.
<br>

## What is Ethical-Hacking?
<p>Ethical Hacking sometimes called as Penetration Testing is an act of intruding/penetrating into system or networks to find out threats, vulnerabilities in those systems which a malicious attacker may find and exploit causing loss of data, financial loss or other major damages. The purpose of ethical hacking is to improve the security of the network or systems by fixing the vulnerabilities found during testing. Ethical hackers may use the same methods and tools used by the malicious hackers but with the permission of the authorized person for the purpose of improving the security and defending the systems from attacks by malicious users.
Ethical hackers are expected to report all the vulnerabilities and weakness found during the process to the management.</p>
<br>

## What is Cybersecurity? :computer:
<p>Cybersecurity is the practice of protecting systems, networks, and programs from digital attacks. These cyberattacks are usually aimed at accessing, changing, or destroying sensitive information; extorting money from users; or interrupting normal business processes.</p>
<br>

## What are Ethical-Hacking-Tools? :man_technologist: :hammer_and_wrench:
<p>Hacking Tools are computer programs and scripts that help you find and exploit weaknesses in computer systems, web applications, servers and networks. There are a variety of such tools available on the market. Some of them are open source while others are commercial solutions.</p>
<br>



<br><br><br>

## The 10 most common cyber attack types:

1) [Denial-of-service (DoS) and distributed denial-of-service (DDoS) attacks](https://blog.netwrix.com/2018/05/15/top-10-most-common-types-of-cyber-attacks/#Denial-of-service%20(DoS)%20and%20distributed%20denial-of-service%20(DDoS)%20attacks) &nbsp; <br>
2) [Man-in-the-middle (MitM) attack](https://blog.netwrix.com/2018/05/15/top-10-most-common-types-of-cyber-attacks/#Man-in-the-middle%20(MitM)%20attack) &nbsp; <br>
3) [Phishing and spear phishing attacks](https://blog.netwrix.com/2018/05/15/top-10-most-common-types-of-cyber-attacks/#Phishing%20and%20spear%20phishing%20attacks) &nbsp; <br>
4) [Drive-by attack](https://blog.netwrix.com/2018/05/15/top-10-most-common-types-of-cyber-attacks/#Drive-by%20attack) &nbsp; <br>
5) [Password attack](https://blog.netwrix.com/2018/05/15/top-10-most-common-types-of-cyber-attacks/#Password%20attack) &nbsp; <br>
6) [SQL injection attack](https://blog.netwrix.com/2018/05/15/top-10-most-common-types-of-cyber-attacks/#SQL%20injection%20attack) &nbsp; <br>
7) [Cross-site scripting (XSS) attack](https://blog.netwrix.com/2018/05/15/top-10-most-common-types-of-cyber-attacks/#Cross-site%20scripting%20(XSS)%20attack) &nbsp; <br>
8) [Eavesdropping attack](https://blog.netwrix.com/2018/05/15/top-10-most-common-types-of-cyber-attacks/#Eavesdropping%20attack) &nbsp; <br>
9) [Birthday attack](https://blog.netwrix.com/2018/05/15/top-10-most-common-types-of-cyber-attacks/#Birthday%20attack) &nbsp; <br>
10) [Malware attack](https://blog.netwrix.com/2018/05/15/top-10-most-common-types-of-cyber-attacks/#Malware%20attack) &nbsp; <br>
-->

# Ultimate List of kali lunix Commands 

## Command History

```bash
history                                # View all previous commands
history 3                              # View the last 3 executed commands
history -d 99                          # Clear a command from a specific line 
history -c                             # Clears all history commands
!!                                     # Run the last command executed
```

## Navigating Directories
 ``` bash
pwd                       # Print current directory path
ls                        # List directories
ls -a|--all               # List directories including hidden
ls -l                     # List directories in long form
ls -l -h|--human-readable # List directories in long form with human readable sizes
ls -t                     # List directories by modification time, newest first

cd foo                    # Go to foo sub-directory
cd                        # Go to home directory
cd ~                      # Go to home directory
cd -                      # Go to the previously chosen directory
```
## Creating Directories 

```bash
mkdir foo                        # Create a directory
mkdir foo bar                    # Create multiple directories

## Deleting Directories

```bash
rmdir foo                        # Delete non-empty directory
rm -r|--recursive foo            # Delete directory including contents
```

## Creating Files

```bash
touch foo.txt          # Create file or update existing files modified timestamp
touch foo.txt bar.txt  # Create multiple files
touch {foo,bar}.txt    # Create multiple files
touch test{1..3}       # Create test1, test2 and test3 files
touch test{a..c}       # Create testa, testb and testc files

mktemp                 # Create a temporary file
```
## Moving and Copy files 

```bash
cp foo.txt bar.txt                                 # Copy file [cp file name spece destination]
mv foo.txt bar.txt                                 # Move file
```

## Reading Files

```bash
cat foo.txt              # Print all contents
nano                              # Open a new file in nano
nano foo.txt                      # Open a specific file
```

## Finding Files

Find binary files for a command.

```bash
type -a wget                              # Display all locations of executable
which -a wget                             # Display all locations of executables 
```

## update and upgrade

```bash
apt update                          # Refreshes repository index
apt upgrade                         # Upgrades all upgradable packages
apt clean                           # Clears out the local repository of 
```
## Shutdown and Reboot

```bash
shutdown                     # Shutdown in 1 minute
shutdown now                 # Immediately shut down
shutdown +5                  # Shutdown in 5 minutes

shutdown -r|--reboot         # Reboot in 1 minute (" | " mean " or " )
shutdown -r|--reboot now     # Immediately reboot
shutdown -r|--reboot +5      # Reboot in 5 minutes
shutdown -c                  # Cancel a shutdown or reboot

reboot                       # Reboot now
reboot -f                    # Force a reboot
```

## User Management

```bash
sudo su                                            # Switch to root user
sudo foo                                           # Execute commands(has permission denied) as the root user
sudo nano /foo/foo.txt                             # Open directories and files(is not writable) as the root user
su username                                        # Switch to a different user

passwd                                             # To change the password of a user
adduser username                                   # To add a new user
userdel username                                   # To remove user
userdel -r|--remove username                       # To remove user with home directory and mail spool
usermod -a|--append -G|--groups GROUPNAME USERNAME # To add a user to a group
deluser USER GROUPNAME                             # To remove a user from a group

last                                               # Display information of all the users logged in
last username                                      # Display information of a particular user
w                                                  # Display who is online
```

## Network Troubleshooting

```bash
ifconfig                     # Display all network card and interface information 
ifconfig -a                  # Display information of all network cards (including those that are not started at boot) 
ifconfig eth0                # Display specific device information 
ifconfig eth0 up             # Turn on the network card
ifconfig eth0 down           # Turn off the network card
ifconfig eth0 192.168.120.56 # Configure IP address for network card


ping example.com             # Send multiple ping requests using the ICMP protocol
ping -c 10 -i 5 example.com  # Make 10 attempts, 5 seconds apart

ip addr                      # List IP addresses on the system
ip route show                # Show IP addresses to router
 
netstat -i|--interfaces      # List all network interfaces and in/out usage
netstat -l|--listening       # List all open ports

traceroute example.com       # List all servers the network traffic goes through

mtr -w|--report-wide example.com                                    # Continually list all servers the network traffic goes through
mtr -r|--report -w|--report-wide -c|--report-cycles 100 example.com # Output a report that lists network traffic 100 times

nmap 0.0.0.0                 # Scan for the 1000 most common open ports on localhost
nmap 0.0.0.0 -p1-65535       # Scan for open ports on localhost between 1 and 65535
nmap 192.168.4.3             # Scan for the 1000 most common open ports on a remote IP address
nmap -sP 192.168.1.1/24      # Discover all machines on the network by ping'ing them
```
<h2>Networking</h2>
<h3>TTL Fingerprinting</h3>
<table>
<thead>
<tr>
<th>Operating System</th>
<th>TTL Size</th>
</tr>
</thead>
<tbody>
<tr>
<td>Windows</td>
<td>128</td>
</tr>
<tr>
<td>Linux</td>
<td>64</td>
</tr>
<tr>
<td>Solaris</td>
<td>255</td>
</tr>
<tr>
<td>Cisco / Network</td>
<td>255</td>
</tr>
</tbody>
</table>
<h2>IPv4</h2>
<h3>Classful IP Ranges</h3>
<p>E.g Class A,B,C (depreciated)</p>
<table>
<thead>
<tr>
<th>Class</th>
<th>IP Address Range</th>
</tr>
</thead>
<tbody>
<tr>
<td>Class A IP Address Range</td>
<td>0.0.0.0 – 127.255.255.255</td>
</tr>
<tr>
<td>Class B IP Address Range</td>
<td>128.0.0.0 – 191.255.255.255</td>
</tr>
<tr>
<td>Class C IP Address Range</td>
<td>192.0.0.0 – 223.255.255.255</td>
</tr>
<tr>
<td>Class D IP Address Range</td>
<td>224.0.0.0 – 239.255.255.255</td>
</tr>
<tr>
<td>Class E IP Address Range</td>
<td>240.0.0.0 – 255.255.255.255</td>
</tr>
</tbody>
</table>
<h3>IPv4 Private Address Ranges</h3>
<table>
<thead>
<tr>
<th>Class</th>
<th>Range</th>
</tr>
</thead>
<tbody>
<tr>
<td>Class A Private Address Range</td>
<td>10.0.0.0 – 10.255.255.255</td>
</tr>
<tr>
<td>Class B Private Address Range</td>
<td>172.16.0.0 – 172.31.255.255</td>
</tr>
<tr>
<td>Class C Private Address Range</td>
<td>192.168.0.0 – 192.168.255.255</td>
</tr>
<tr>
<td></td>
<td>127.0.0.0 – 127.255.255.255</td>
</tr>
</tbody>
</table>
<h3>IPv4 Subnet Cheat Sheet</h3>
<table>
<thead>
<tr>
<th>CIDR</th>
<th>Decimal Mask</th>
<th>Number of Hosts</th>
</tr>
</thead>
<tbody>
<tr>
<td>/31</td>
<td>255.255.255.254</td>
<td>1 Host</td>
</tr>
<tr>
<td>/30</td>
<td>255.255.255.252</td>
<td>2 Hosts</td>
</tr>
<tr>
<td>/29</td>
<td>255.255.255.249</td>
<td>6 Hosts</td>
</tr>
<tr>
<td>/28</td>
<td>255.255.255.240</td>
<td>14 Hosts</td>
</tr>
<tr>
<td>/27</td>
<td>255.255.255.224</td>
<td>30 Hosts</td>
</tr>
<tr>
<td>/26</td>
<td>255.255.255.192</td>
<td>62 Hosts</td>
</tr>
<tr>
<td>/25</td>
<td>255.255.255.128</td>
<td>126 Hosts</td>
</tr>
<tr>
<td>/24</td>
<td>255.255.255.0</td>
<td>254 Hosts</td>
</tr>
<tr>
<td>/23</td>
<td>255.255.254.0</td>
<td>512 Host</td>
</tr>
<tr>
<td>/22</td>
<td>255.255.252.0</td>
<td>1022 Hosts</td>
</tr>
<tr>
<td>/21</td>
<td>255.255.248.0</td>
<td>2046 Hosts</td>
</tr>
<tr>
<td>/20</td>
<td>255.255.240.0</td>
<td>4094 Hosts</td>
</tr>
<tr>
<td>/19</td>
<td>255.255.224.0</td>
<td>8190 Hosts</td>
</tr>
<tr>
<td>/18</td>
<td>255.255.192.0</td>
<td>16382 Hosts</td>
</tr>
<tr>
<td>/17</td>
<td>255.255.128.0</td>
<td>32766 Hosts</td>
</tr>
<tr>
<td>/16</td>
<td>255.255.0.0</td>
<td>65534 Hosts</td>
</tr>
<tr>
<td>/15</td>
<td>255.254.0.0</td>
<td>131070 Hosts</td>
</tr>
<tr>
<td>/14</td>
<td>255.252.0.0</td>
<td>262142 Hosts</td>
</tr>
<tr>
<td>/13</td>
<td>255.248.0.0</td>
<td>524286 Hosts</td>
</tr>
<tr>
<td>/12</td>
<td>255.240.0.0</td>
<td>1048674 Hosts</td>
</tr>
<tr>
<td>/11</td>
<td>255.224.0.0</td>
<td>2097150 Hosts</td>
</tr>
<tr>
<td>/10</td>
<td>255.192.0.0</td>
<td>4194302 Hosts</td>
</tr>
<tr>
<td>/9</td>
<td>255.128.0.0</td>
<td>8388606 Hosts</td>
</tr>
<tr>
<td>/8</td>
<td>255.0.0.0</td>
<td>16777214 Hosts</td>
</tr>
</tbody>
</table>
