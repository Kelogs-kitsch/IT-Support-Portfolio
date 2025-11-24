# Baseline Network Information
Collected baseline network details prior to troubleshooting. 
Commands executed included ipconfig, ping, tracert, and nslookup to verify network connectivity, DNS resolution, and routing path.

Press Windows + R

Type: cmd

Press Enter

Run these commands:

ipconfig /all

ping 8.8.8.8

ping google.com

tracert google.com

nslookup google.com

### ipconfig /all
Displayed the full IP configuration of the workstation, including IP address, subnet mask, gateway, DNS servers, and DHCP status. Used to identify addressing or configuration issues.

<img width="1024" height="768" alt="ipconfig" src="https://github.com/user-attachments/assets/1a9a446a-de01-4ec9-b56c-dd56b3065794" />

### ping 8.8.8.8
Tested connectivity to the internet using Google’s public DNS server. Verified whether the device could reach external networks.

<img width="1024" height="768" alt="ping8 8 8 8" src="https://github.com/user-attachments/assets/4c3919ff-4515-4522-a739-53d422e824f0" />

### ping google.com
Checked DNS resolution and internet connectivity. Used to compare results against pinging an IP address to detect DNS problems.

<img width="1024" height="768" alt="pinggoogle" src="https://github.com/user-attachments/assets/8f240912-035b-4621-b6b7-a80b11279a92" />

### tracert google.com
Displayed the network path to google.com. Used to identify routing issues, connectivity breaks, and slow hops.

<img width="1024" height="768" alt="tracertgoogle" src="https://github.com/user-attachments/assets/b39212b3-189f-460d-9cba-038f369c0a24" />

### nslookup google.com
Tested DNS server response and name resolution. Helped confirm if DNS was functioning correctly.

<img width="1024" height="768" alt="nslookupgoogle" src="https://github.com/user-attachments/assets/764a3195-5c3f-444b-91ea-dc9d733f1017" />




