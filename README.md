# Nmap Scan Tool

This is a Bash script to perform various Nmap scans. The tool provides 20 different scanning options for network exploration and security auditing. 

## Features

- **Basic Scan**: Performs a simple scan on the target IP.
- **Specific Port Scan**: Scans specific ports on the target IP.
- **Scan All Ports**: Scans all ports on the target IP.
- **Service and Version Info**: Detects the service and version information of open ports.
- **OS Detection**: Identifies the operating system of the target.
- **SYN Scan**: Performs a TCP SYN scan.
- **UDP Scan**: Scans UDP ports.
- **Aggressive Scan**: Conducts a comprehensive scan that includes OS detection, version detection, script scanning, and traceroute.
- **Ping Sweep**: Checks for live hosts on the network.
- **Scan Specific Hosts**: Scans a specified host or range of hosts.
- **List Open Ports**: Lists only the open ports on the target.
- **Save Output in Normal Format**: Saves the scan output in a normal text format.
- **Save Output in XML Format**: Saves the scan output in XML format.
- **Scan Port Range**: Scans a range of ports on the target.
- **TCP Connect Scan**: Performs a TCP connect scan.
- **Firewall Detection**: Attempts to detect and bypass firewalls.
- **Scan Multiple Targets from File**: Scans multiple targets listed in a file.
- **IP Protocol Scan**: Scans for IP protocols.
- **TCP ACK Scan**: Performs a TCP ACK scan.
- **FIN Scan**: Performs a TCP FIN scan.

## Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/hash2602/quicknmap
   ```

   ```bash
   cd quicknmap
   ```
   
   ```
   chmod +x quicknmap.sh
   ```
   
   ```bash
   bash quicknmap.sh
   ```
   
