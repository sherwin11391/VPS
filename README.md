# VPS for DEBIAN 9 SSH,SQUID,SSL

wget https://raw.githubusercontent.com/sherwin11391/VPS/master/VPS.sh && chmod +x VPS.sh && ./VPS.sh



# SoftEther Auto Install Multi Platform

SoftEther Auto Install Script for Multi-Platform
Updated 5/30/18
SoftEther VPN Server (Ver 4.27, Build 9668, beta)
An open source VPN project from University of Tsukuba Japan
Works With

CentOS 6 or 7 x64
Fedora
Debian 8 or 9 x64
Ubuntu 14, 15, 16, 17, 18 x64
Instruction

Choose your desired platform folder
Download installer.sh using wget or transfer to your root directory using ftp

(Copy All The Codes Below And Paste On Your Terminal)

Download and install the installer.sh by executing the commands below


For CentOS and Fedora 

yum install wget -y && wget https://raw.githubusercontent.com/Driz12/SoftetherAutoInstallMultiPlatform/master/CentOS%20and%20Fedora/installer.sh && chmod +x installer.sh && ./installer.sh 



For Debian and Ubuntu 

wget https://raw.githubusercontent.com/Driz12/SoftetherAutoInstallMultiPlatform/master/Debian%20and%20Ubuntu/installer.sh && chmod +x installer.sh && ./installer.sh



VPN server commands

/etc/init.d/vpnserver start - to start
/etc/init.d/vpnserver restart - to restart
/etc/init.d/vpnserver stop - to stop


vpncmd is at /usr/local/vpnserver

If you can't connect to your vpn server using VPN server manager. Open this ports on your firewall dashboard if you are using Google cloud, Amazon AWS, Alibaba Cloud and Digital Ocean

TCP 443
TCP 992
TCP 1194
TCP 5555
