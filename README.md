# NetScanX
Nmap Useful Script
This script simplify a common use of nmap to write a file containing scan results.

example:
- nmap -sn -oG - x.x.x.x/24 -vv | grep Up
- nmap -sn -oG - x.x.x.x/24 -vv | grep Up | awk -F " " '{print $2}' > filename 
- nmap -iL filename > results.txt

## Use
Copy it on /user/local/bin and run it from any path

## Run it

# !! WORK IN PROGRESS !!
