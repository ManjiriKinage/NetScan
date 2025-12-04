# 🚨 NetScan — Local Vulnerability Scanner  
*A lightweight network scanning tool with real-time logs, progress tracking, and PDF reporting.*

---

## 🛡️ Overview
NetScan is a Flask-based web application that scans your local network for open ports, weak services, and outdated software.  
It uses **Nmap** under the hood and provides:
# NetScan – Local Vulnerability Scanner

NetScan is a simple web-based tool that scans a local network for open ports and potential vulnerabilities.  
It uses Nmap for scanning and provides results through a clean web interface with real-time logs and PDF report generation.

## Features
- Scan a subnet (e.g., 192.168.1.0/24)
- Detect open ports and weak services
- Identify outdated software versions
- View live logs and scan progress
- Download automatically generated PDF reports

## Requirements
- Python 3.10+
- Flask
- python-nmap
- FPDF
- Nmap installed and added to PATH

## Installation
```bash
git clone <repository-url>
cd NetScan
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt

✔ Real-time logs  
✔ Live progress bar  
✔ Device-wise vulnerability insights  
✔ Auto-generated PDF reports  
✔ Stylish dark dashboard UI  

This tool is perfect for beginners, students, cybersecurity learners, and internal network auditing.

---

## ✨ Features

### 🔍 **Network Scanning**
- Scans a full subnet (e.g., `192.168.1.0/24`)
- Detects open ports  
- Identifies weak/insecure services  
- Matches outdated software versions  

### 📡 **Real-Time Dashboard**
- Live log viewer  
- Progress bar updates  
- Device count, vulnerability count, and report count  
- Beautiful TailwindCSS UI  

### 📝 **PDF Reporting**
Generates clean and readable reports containing:
- Devices found  
- Vulnerabilities per device  
- Scan time  
- Summary section  

### 🖥️ **Web UI**
Modern UI built with:
- Tailwind CSS  
- Custom dark-themed dashboard  
- Interactive controls  

---

## ⚙️ Tech Stack

| Component | Technology |
|----------|------------|
| Backend  | Python + Flask |
| Scanner  | python-nmap |
| UI       | Tailwind CSS |
| Reporting | FPDF |
| Async-like updates | AJAX polling |

---

## 📁 Project Structure

