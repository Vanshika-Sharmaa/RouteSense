# RouteSense

A full-stack network diagnostics and troubleshooting platform for analyzing connectivity, DNS, TCP/IP, HTTP/HTTPS, and firewall rules through an interactive dashboard.

## 🚀 Features

- 🌐 Connectivity diagnostics
- 🔌 TCP port checking
- 🔎 DNS lookup and resolution analysis
- 🔐 HTTP/HTTPS diagnostics
- 🧠 Rule-based troubleshooting assistant
- 🛡️ Firewall rule simulator
- 📊 Diagnostic history with SQLite
- 🧪 Automated unit testing
- ⚡ Response-time and error reporting
- 📋 Layered troubleshooting workflow

## 🛠️ Tech Stack

- **Backend:** Python, Flask
- **Frontend:** HTML, CSS, JavaScript
- **Database:** SQLite
- **Networking:** TCP/IP, Socket Programming, DNS, HTTP/HTTPS
- **Testing:** Pytest

## 🏗️ Architecture

```text
Browser / Dashboard
        ↓
   Flask API Layer
        ↓
Diagnostic Services
        ↓
 ┌──────┼────────┐
 DNS   TCP/IP   HTTP/HTTPS
        ↓
 Firewall Simulator
        ↓
      SQLite
