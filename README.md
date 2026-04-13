# Python network scanner for online machines.




 ### **🔍 Overview:-**
 
A network scanner for online machines is a tool used to discover devices hosts connected to a network and determine whether they are active (online), along with additional details like IP address, open ports, OS, and services.

## **🎯 Objective:-**

1.Detects the local network automatically or accepts user input

    -Automatically detects the local network or allows the user to manually enter a network range

2.Scans a given IP range

    -Scans a specified IP address range to discover devices
    
3.Identifies active (online) hosts using ping

    -Uses ping to identify which hosts are active and reachable
    
4.Displays results in a sorted list

    -Displays the active hosts in a clean, sorted list with one-line summaries

## **🛠️ Tools & Techniques Used:-**

1. Command-Line Interface (CLI)

    -The tool operates via a CLI, allowing users to provide inputs and receive results efficiently.

2 Network Detection

    -Automatically determines the local network configuration for scanning.

3 Subnet and CIDR Handling

    -Uses IP addressing standards to define and iterate through network ranges.

4 Ping-Based Host Discovery

    -Sends ICMP echo requests (ping) to detect whether a host is active.

5 Multithreading

    -Implements parallel execution using threading to significantly improve scanning speed.

6 Regex Parsing

    -Extracts useful information such as IP addresses and TTL values from command outputs.

7 Error Handling

    -Ensures stability by handling exceptions and invalid inputs gracefully.

8 Sorting and Output Formatting

    -Organizes scan results into a structured and easy-to-read format.


## **📦 Modules Used:-**

     1.  sys → command-line arguments

     2.  socket → networking (get IP)

     3.  ipaddress → IP range handling

     4.  concurrent.futures → multithreading

     5.  platform → detect OS

     6.  subprocess → run system commands (ping, ipconfig)

     7.  re → pattern matching (IP, TTL)

     8.  os → OS-related utilities



## **▶️ How Run:-**

         python netscan.py



## **📊 Sample Output:-**

  ####   python netscan.py 192.168.1

    Scanning network: 192.168.1.0/24

    Online hosts:

    192.168.1.1

    192.168.1.37

    192.168.1.40





## **🧪 Environment:-**

1.OS: Kali Linux

2.Python Version: 3.x


## **📌 Conclusion:-**

NetScan is a fast, multithreaded network scanner that detects active devices by pinging all hosts in a given network.
It combines automatic network detection and efficient parallel processing to provide quick and reliable network discovery.
