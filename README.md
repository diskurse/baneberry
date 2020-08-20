# baneberry pi
<p align="center">
<img align="right" src="https://github.com/diskurse/baneberry/blob/master/images/imageedit_4_2684878937.jpg">
</p>
Baneberry is an intentionally vulnerable raspbian image with logging designed to be shipped and ingested by a SIEM.
<br><br>
This is intended to be an educational aid to learn about red team tools, Linux logging and log file analysis in SIEMs.

## Usage

Details about log shipping setup, default logins for access, configurable services and vulnerabilities.

Warning, do not allow this image to be directly accessible from the internet, keep it behind a firewall.

## Exploits Covered

+ shellshock

## Data Sources

+ auditd
+ Apache
+ MySQL 
+ SAMBA
+ BIND
+ syslog
+ /var/log/secure
+ /var/log/auth.log
+ /var/log/faillog

## Services Running
