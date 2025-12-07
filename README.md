# NetScan – Local Vulnerability Scanner

NetScan is a simple web-based tool that scans a local network for open ports and potential vulnerabilities.
It uses **Nmap** for scanning and provides results through a clean web interface with real-time logs, progress tracking, and PDF report generation.

## Features

* Scan a subnet (e.g., `192.168.1.0/24`)
* Detect open ports and weak/insecure services
* Identify outdated software versions
* View live logs and scan progress
* Download automatically generated PDF reports
* Modern UI built with Tailwind CSS

## Requirements

* Python 3.10+
* Flask
* python-nmap
* FPDF
* Nmap installed and added to PATH

## Installation

```bash
git clone <repository-url>
cd NetScan

# Create virtual environment
python -m venv .venv
.venv\Scripts\activate     # For Windows
# source .venv/bin/activate  # For Linux/Mac

# Install dependencies
pip install -r requirements.txt
```

## Install Nmap

Download from: [https://nmap.org/download/](https://nmap.org/download/)
Make sure to check: **Add Nmap to PATH**

## Running the App

```bash
python app.py
```

Then open in browser:

```
http://127.0.0.1:5000
```

## Folder Structure

```
NetScan/
│── app.py
│── scanner.py
│── report_generator.py
│── requirements.txt
│── outputs/
│── static/js/main.js
│── templates/
│   ├── base.html
│   └── index.html
```

## Notes

* Only scan networks you own or have permission to scan.
* PDF reports are saved automatically inside the `outputs/` folder.
