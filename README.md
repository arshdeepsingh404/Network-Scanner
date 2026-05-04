# Network-Scanner
An Industrial Ethernet commissioning utility for Industrial Automation Programmers. Streamlines device discovery, network diagnostics, and IP management.

## Purpose
This tool is designed to replace generic IT scanners with a workflow focused on industrial automation. It provides a stable, high-visibility interface for managing PLCs, HMIs, VFDs, and Remote I/O across diverse industrial subnets.

## Screenshot
<img width="1436" height="943" alt="Network Scanner" src="https://github.com/user-attachments/assets/f70b596f-0e7f-426b-b391-8d6db9b7629c" />

## Core Features

## 1. IP Management (Change IP with History)
Manage machine IP transitions and avoid address conflicts.
* **How to use**: Modify local adapter settings (DHCP or Static) directly through the utility interface.
* **History Tracking**: The app stores the last 10 configurations, allowing quick switching when moving between different machine subnets or the office network.

## 2. Network Discovery (Scan)
High-speed discovery of all active hardware on your local subnet.
* **Industrial Context**: Quickly locate PLCs, HMIs, and VFDs even when DNS is unavailable or hostnames are not configured.
* **Visibility**: View MAC addresses to identify hardware vendors like Siemens, Rockwell Automation, or Phoenix Contact.

## 3. Commissioning Documentation (Export)
Generate instant network reports for your project handovers.
* **How to use**: After completing a machine scan, use the **Export** feature to save the device list as a CSV.
* **Benefit**: Attach these reports to your technical documentation or use them for future maintenance reference.

## 4. Connection Diagnostics (Ping with History)
Monitor network accessibility and link stability.
* **How to use**: Enter a device IP and initiate a Ping. The integrated drop-down menu stores a history of the last 10 IP addresses used.
* **Industrial Context**: Essential for troubleshooting device accessibility and monitoring connection drops in electrically noisy environments.

---

## Download Instructions

## 1. Obtain the Software
Navigate to the **Releases** tab on the right side of this GitHub repository. Download the latest `.exe` containing the production build.

## 2. Portable Single-File Executable
This application is designed as a **single-file executable**. 
* **No Installation Required**: It runs instantly without the need for an installer or administrative setup on the OS.

---

## Appearance Settings
The application includes a **Light/Dark Theme** toggle located in the top-right corner. Your theme preference is automatically saved and will persist the next time you launch the utility.
