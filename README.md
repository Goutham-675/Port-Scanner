# Port-Scanner
Lightweight educational TCP port scanner
# Port-Scanner — Educational Network Tool

**A small, lightweight port scanner implemented for learning purposes.**  
This project demonstrates basic network scanning concepts (TCP connect scans), socket programming, and simple concurrency. It is intended for lab and classroom use only.

## Features
- Scan a target host for open TCP ports (single port, range, or common ports)
- Simple concurrency to speed up scans (threading)
- Clear console output showing open/closed ports and response times
- Minimal external dependencies — easy to run on a local machine

## Tech / Languages
- Python 3 (recommended) or C (starter implementation available)
- Uses standard libraries (`socket`, `threading` in Python)

## Usage (example)
> **Only scan hosts/networks you own or have explicit permission to test. Unauthorized scanning is illegal and unethical.**

1. Clone the repository or copy the files to your machine.
2. Run the scanner:
```bash
# Example (Python)
python3 main.py --target 192.168.1.10 --ports 20-1024

# Example (scan a single port)
python3 main.py --target example.com --port 80
