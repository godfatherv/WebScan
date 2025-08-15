# WebScan
A Python-based website vulnerability scanner with PDF/JSON reports


# 🛡️ WebScan - Website Vulnerability Scanner
# 🤝 Author
  👤 **Sagar Mane**

WebScan is an advanced Python-based website vulnerability scanner designed for penetration testers, cybersecurity students, and researchers.  
It automates reconnaissance, vulnerability detection, and reporting with both PDF and JSON outputs.  

---

## 📌 Features
- **Reconnaissance**: Gathers information such as domain data, HTTP headers, SSL certificate info, etc.
- **Crawler**: Crawls the target domain to discover hidden endpoints.
- **Vulnerability Detection**:
  - SQL Injection (SQLi)
  - Cross-Site Scripting (XSS)
  - Command Injection
  - Security Misconfiguration
  - Weak SSL/TLS configurations
  - HTTP method misconfigurations
- **Report Generation**:
  - PDF format
  - JSON format
- **Custom Payloads** for testing
- **Multi-threaded** scanning for speed
- **CLI-based Interface** with banners & colored output

---
## Steps to Download
```
Create & Activate a Virtual Environment

Windows (PowerShell)
cd path\to\WebScan
python -m venv .venv
.\.venv\Scripts\Activate.ps1      # PowerShell
# or: .\.venv\Scripts\activate.bat # CMD
python -m pip install --upgrade pip

Linux / macOS (bash/zsh)
cd /path/to/WebScan
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip


### 2️⃣ Install dependencies
Run Webscan in Virtual Envoitnment (venv)
already inside the activated venv and at the WebScan root
```bash
pip install -r requirements.txt
pip install -r webscan/requirements.txt
pip install .
```


## 3️⃣ Install Playwright browsers (for screenshots)
```bash
pip install playwright
python -m playwright install 
playwright install
```
## verify webscan
```
python -c "import webscan; print('WebScan import OK')"
```

## 🚀 Usage

```bash
webscan --url http://example.com 
usage: webscan [-h] [--full] --url URL [--depth DEPTH] [--techstack] [--ports PORTS]
```

## 📁 Project Structure
```
📂 WebScan​

├── 📄 read.md​

├── 📄 requirements.txt​

├── 📄 setup.py​

├── 📄 testingsites.txt​

└── 📂 webscan​

      ├── 📄 crawler.py​

      ├── 📄 main.py​

      ├── 📄 payloads.py​

      ├── 📄 recon.py​

      ├── 📄 report.py​

      ├── 📄 requirements.txt​

      ├── 📄 scanner.py​

      ├── 📄 techstack.py​

      ├── 📄 utils.py​

      ├── 📂 assets​

      │     └── 🖼 logo.png.png​

      └── 📂 reports​

```

## 📜 License
```
This project is for **educational purposes only**. The author is **not responsible** for any illegal use of this tool.
```
