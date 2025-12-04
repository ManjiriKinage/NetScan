# 🚨 NetScan — Local Vulnerability Scanner  
*A lightweight network scanning tool with real-time logs, progress tracking, and PDF reporting.*

---

## 🛡️ Overview
NetScan is a Flask-based web application that scans your local network for open ports, weak services, and outdated software.  
It uses **Nmap** under the hood and provides:

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

