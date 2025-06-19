# Nmap Port Scanner Project

## Description
This project implements a port scanner using Nmap on a Windows system as part of a cybersecurity course. The scanner identifies open ports, services, and versions on a target system, with automation via Python scripting. The repository includes the scanner code, documentation, and a project report summarizing findings from lab tests.

## Features
- Scans target IPs for open ports using Nmap’s SYN scan (`-sS`) and service detection (`-sV`).
- Automated scanning with a Python script using the `python-nmap` library.
- Saves scan results locally (excluded from Git) and summarizes findings in a report.
- Tested in a controlled lab environment (e.g., VirtualBox with Metasploitable).

## Setup
1. **Install Nmap**:
   - Download and install from [nmap.org](https://nmap.org/download.html).
   - Ensure Npcap is included for advanced scanning.
2. **Install Python**:
   - Download from [python.org](https://www.python.org/downloads/windows/).
   - Install `python-nmap`: `pip install python-nmap`.
3. **Clone the Repository**:
   ```bash
   git clone git@github.com:yourusername/nmap-port-scanner.git
4. **Run the scanner** :
   -Example: python src/scanner.py 192.168.1.1
