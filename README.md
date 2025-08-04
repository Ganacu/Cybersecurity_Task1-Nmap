# Cybersecurity_Task1-Nmap
Port Scanning and packet snalysis uisng Nmap
[Uploading scan_result_<?xml version="1.0" encoding="iso-8859-1"?>
<?xml-stylesheet href="file:///C:/Program Files (x86)/Nmap/nmap.xsl" type="text/xsl"?><nmaprun args="nmap -p 1-65535 -T4 -A -v 255.255.255.0" profile_name="Intense scan, all TCP ports" scanner="nmap" start="1754323016" startstr="Mon Aug  4 21:26:56 2025" version="7.95" xmloutputversion="1.04"><scaninfo type="syn" protocol="tcp" numservices="65535" services="1-65535"></scaninfo><verbose level="1"></verbose><debugging level="0"></debugging><output type="interactive">Starting Nmap 7.95 ( https://nmap.org ) at 2025-08-04 21:26 India Standard Time
NSE: Loaded 157 scripts for scanning.
NSE: Script Pre-scanning.
Initiating NSE at 21:26
Completed NSE at 21:26, 0.00s elapsed
Initiating NSE at 21:26
Completed NSE at 21:26, 0.00s elapsed
Initiating NSE at 21:26
Completed NSE at 21:26, 0.00s elapsed
get_srcaddr: can't connect socket: A socket operation was attempted to an unreachable network. 
Initiating Ping Scan at 21:26
Scanning 255.255.255.0 [4 ports]
Completed Ping Scan at 21:26, 0.05s elapsed (1 total hosts)
Initiating Parallel DNS resolution of 1 host. at 21:26
Completed Parallel DNS resolution of 1 host. at 21:26, 0.00s elapsed
Initiating SYN Stealth Scan at 21:26
Scanning 255.255.255.0 [65535 ports]
SYN Stealth Scan Timing: About 18.46% done; ETC: 21:29 (0:02:17 remaining)
SYN Stealth Scan Timing: About 43.86% done; ETC: 21:29 (0:01:18 remaining)
SYN Stealth Scan Timing: About 67.63% done; ETC: 21:29 (0:00:44 remaining)
Completed SYN Stealth Scan at 21:29, 132.82s elapsed (65535 total ports)
Initiating Service scan at 21:29
Initiating OS detection (try #1) against 255.255.255.0
Retrying OS detection (try #2) against 255.255.255.0
Initiating Traceroute at 21:29
Completed Traceroute at 21:29, 3.05s elapsed
Initiating Parallel DNS resolution of 2 hosts. at 21:29
Completed Parallel DNS resolution of 2 hosts. at 21:29, 0.18s elapsed
NSE: Script scanning 255.255.255.0.
Initiating NSE at 21:29
Completed NSE at 21:29, 0.01s elapsed
Initiating NSE at 21:29
Completed NSE at 21:29, 0.00s elapsed
Initiating NSE at 21:29
Completed NSE at 21:29, 0.00s elapsed
Nmap scan report for 255.255.255.0
Host is up (0.046s latency).
All 65535 scanned ports on 255.255.255.0 are in ignored states.
Not shown: 65535 filtered tcp ports (no-response)
Warning: OSScan results may be unreliable because we could not find at least 1 open and 1 closed port
Device type: power-device|firewall|WAP|router|general purpose|specialized
Running (JUST GUESSING): APC embedded (94%), Cisco ASA 9.X (94%), Cisco embedded (94%), Synology embedded (94%), Microsoft Windows 2000|2003 (93%), ETH Zurich Bluebottle (87%), Tibbo embedded (86%)
OS CPE: cpe:/o:cisco:asa:9.2 cpe:/h:synology:rt1900ac cpe:/o:microsoft:windows_2000::sp4 cpe:/o:microsoft:windows_server_2003::sp2 cpe:/o:ethzurich:bluebottle
Aggressive OS guesses: APC Network Management Card 3 (94%), Cisco Adaptive Security Appliance (ASA 9.2) (94%), Cisco Aironet 3800-series WAP (94%), Synology RT1900ac router (94%), Microsoft Windows 2000 SP4 (93%), Microsoft Windows Server 2003 SP2 (93%), Bluebottle OS (87%), Tibbo DS10xx serial controller, V3.34 (86%)
No exact OS matches for host (test conditions non-ideal).
Network Distance: 6 hops

TRACEROUTE (using port 80/tcp)
HOP RTT      ADDRESS
1   4.00 ms  10.243.196.98
2   ... 5
6   66.00 ms 255.255.255.0

NSE: Script Post-scanning.
Initiating NSE at 21:29
Completed NSE at 21:29, 0.00s elapsed
Initiating NSE at 21:29
Completed NSE at 21:29, 0.00s elapsed
Initiating NSE at 21:29
Completed NSE at 21:29, 0.00s elapsed
Read data files from: C:\Program Files (x86)\Nmap
OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 139.64 seconds
           Raw packets sent: 131236 (5.778MB) | Rcvd: 184 (7.416KB)
</output><host comment=""><status state="up"></status><address addr="255.255.255.0" vendor="" addrtype="ipv4"></address><hostnames></hostnames><ports><extraports count="65535" state="filtered"></extraports></ports><os><osmatch name="APC Network Management Card 3" accuracy="94" line="3338"><osclass vendor="APC" osfamily="embedded" type="power-device" osgen="" accuracy="94"></osclass></osmatch><osmatch name="Cisco Adaptive Security Appliance (ASA 9.2)" accuracy="94" line="14871"><osclass vendor="Cisco" osfamily="ASA" type="firewall" osgen="9.X" accuracy="94"></osclass></osmatch><osmatch name="Cisco Aironet 3800-series WAP" accuracy="94" line="16838"><osclass vendor="Cisco" osfamily="embedded" type="WAP" osgen="" accuracy="94"></osclass></osmatch><osmatch name="Synology RT1900ac router" accuracy="94" line="108595"><osclass vendor="Synology" osfamily="embedded" type="router" osgen="" accuracy="94"></osclass></osmatch><osmatch name="Microsoft Windows 2000 SP4" accuracy="93" line="77178"><osclass vendor="Microsoft" osfamily="Windows" type="general purpose" osgen="2000" accuracy="93"></osclass></osmatch><osmatch name="Microsoft Windows Server 2003 SP2" accuracy="93" line="79591"><osclass vendor="Microsoft" osfamily="Windows" type="general purpose" osgen="2003" accuracy="93"></osclass></osmatch><osmatch name="Bluebottle OS" accuracy="87" line="26405"><osclass vendor="ETH Zurich" osfamily="Bluebottle" type="general purpose" osgen="" accuracy="87"></osclass></osmatch><osmatch name="Tibbo DS10xx serial controller, V3.34" accuracy="86" line="109361"><osclass vendor="Tibbo" osfamily="embedded" type="specialized" osgen="" accuracy="86"></osclass></osmatch></os><uptime seconds="" lastboot=""></uptime><tcpsequence index="" difficulty="" values=""></tcpsequence><ipidsequence class="" values=""></ipidsequence><tcptssequence class="" values=""></tcptssequence><trace proto="tcp" port="80"><hop ttl="1" rtt="4.00" ipaddr="10.243.196.98" host=""></hop><hop ttl="6" rtt="66.00" ipaddr="255.255.255.0" host=""></hop></trace></host><runstats><finished time="1754323155" timestr="Mon Aug  4 21:29:15 2025"></finished><hosts up="1" down="0" total="1"></hosts></runstats></nmaprun>ass01.xml…]()
