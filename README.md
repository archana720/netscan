_   _      _    _____                 
 | \\ | |    | |  / ____|                
 |  \\| | ___| |_| (___   ___ __ _ _ __  
 | . ` |/ _ \\ __|\\___ \\ / __/ _` | '_ \\ 
 | |\\  |  __/ |_ ____) | (_| (_| | | | |
 |_| \\_|\\___|\\__|_____/ \\___\\__,_|_| |_|
Python network scanner for online machines.

🔍 Overview:-
A network scanner for online machines is a tool used to discover devices hosts connected to a network and determine whether they are active (online), along with additional details like IP address, open ports, OS, and services.

🎯 Objective:-
1.Detects the local network automatically or accepts user input
2.Scans a given IP range
3.Identifies active (online) hosts using ping
4.Displays results in a sorted list


🛠️ Tools & Techniques Used:-
1. Command-Line Interface (CLI)
2. Network Detection
3. Subnet & CIDR Handling
4. Ping-Based Host Discovery
5. Multithreading (Performance Optimization)
6. Regex Parsing
7. Error Handling
8. Sorting & Output Formatting


📦 Modules Used:-
1.sys → command-line arguments
2.socket → networking (get IP)
3.ipaddress → IP range handling
4.concurrent.futures → multithreading
5.platform → detect OS
6.subprocess → run system commands (ping, ipconfig)
7.re → pattern matching (IP, TTL)
8.os → OS-related utilities


🧪 Environment:-
1.OS: Kali Linux
2.Python Version: 3.x


📌 Conclusion:-
NetScan is a fast, multithreaded network scanner that detects active devices by pinging all hosts in a given network.
It combines automatic network detection and efficient parallel processing to provide quick and reliable network discovery.
