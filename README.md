# CyberRiskScanner
CyberRiskScanner Tool is a Python-based project designed to help students and early-career cybersecurity professionals learn how to perform basic vulnerability scans on safe test environments. It can scan local hosts for open ports, check for weak passwords, and generate a simple risk report. This tool is intended for educational and authorized testing purposes only.

## Features
- Scan specified hosts for open ports
- Check weak passwords for demo accounts
- Generate CSV reports summarizing findings
- Easy-to-read console output

## Usage
1. Install required packages: `pip install -r requirements.txt`
2. Update `hosts.txt` with IPs to scan
3. Run `python audit.py`
4. Check the generated report in `reports/`
