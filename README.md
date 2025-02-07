# NetScanX
### Nmap Useful Script

I created this script for the purpose of speeding up one of the most common uses of Nmap, which is scanning active IPs in a subnet and possibly scanning standard ports.
#### Behavior
First, the script scans the network interfaces of the PC from which it is started and deduces the available subnets.
This is very convenient for those who frequently use a laptop during embedded system installations and need to figure out on the fly which network subnet the network cards are on (thinking of a laptop, you will probably have both an ethernet and a wirless).
Alternatively, one can manually enter a subnet or a single IP to analyze. This is convenient in case there is routing to other VLANs.
After selecting or manually entering a subnet, the script uses nmap to derive the list of active hosts on it, displaying the results on the screen. From that point you can choose whether to repeat the scan of active hosts or to continue with the scan of standard ports.
In case a single IP is entered, obviously the scan of active hosts is not performed, but it will be checked that the selected IP is reachable.

## Download and Use
In a terminal (linux or macOS), copy and past following lines:

```` bash
get 
````


## Run it

Open a terminal (Linux, macOS) and write NetScanX! ... Very simple, right?
