# Network-Scanner
An Industrial Ethernet commissioning utility for Industrial Automation Programmers. Streamlines device discovery, network diagnostics, and IP management.

## Purpose
This tool is designed to replace generic IT scanners with a workflow focused on industrial automation. It provides a stable, high-visibility interface for managing PLCs, HMIs, VFDs, and Remote I/O across diverse industrial subnets.

## Core Engineering Features

### 1. Network Discovery (Scan)
High-speed ARP/ICMP scanning to identify active hardware. 
* **Industrial Context**: Quickly locate devices even when DNS is unavailable or hostnames are not configured.
* **Visibility**: View MAC addresses to identify hardware vendors (e.g., Rockwell, Siemens, Phoenix Contact).

### 2. Commissioning Documentation (Export)
Generate instant network reports.
* **How to use**: After completing a machine scan, use the **Export** feature to save the device list.
* **Benefit**: Attach these reports to your technical documentation or use them for future maintenance reference.

### 3. Connection Diagnostics (Ping with History)
Monitor network accessibility.
* **How to use**: Enter an IP address of a device and initiate a Ping. The drop-down menu stores the history of the last 10 IP addresses used.
* **Industrial Context**: Essential for troubleshooting accessibility of a device.

### 4. IP Management (Change IP with History)
Manage machine IP transitions and avoid address conflicts.
* **How to use**: Modify local adapter settings directly through the utility. 
* **History Tracking**: The drop-down menu stores the history of the last 10 IP addresses used and allows quick switching when moving between different machine subnets.
