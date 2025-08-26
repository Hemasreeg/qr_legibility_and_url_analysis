**🛡️ QR Code Security Scanner**

A Deep Learning Framework to Detect Phishing URLs & Malicious APKs

QR codes are convenient—but dangerous. Attackers use them to hide phishing links and malware. This project introduces a smart, deep learning-based system that analyzes QR code content to detect threats before you're compromised.

**🔍 What It Does**

This framework scans QR codes and automatically detects:


🎣 Phishing URLs (fake login pages, scam sites)

💣 Malicious APKs (Android apps with harmful permissions)

Using metadata, domain info, and permission patterns, it applies deep learning models to flag suspicious content in real time.

**🧠 How It Works**

**Scan QR Code** – Upload or capture a QR image.

**Decode & Classify** – Extracts the link or download URL.

Analyze Threats:
🔗 For URLs: Checks for phishing using a DNN + LSTM model (based on domain, SSL, redirects, etc.)

📱 For APKs: Downloads safely, analyzes permissions, and uses a Graph Neural Network (GNN) to detect malware behavior.

Alert or Allow – Gives a clear verdict: Safe or Dangerous.

**✅ Features**


Real-time threat detection

High accuracy: 98.7% for phishing, 96.5% for malware

Uses metadata (domain age, SSL, WHOIS) and Android permissions

Designed for mobile security apps or enterprise tools


**📁 Dataset**
20,450 QR codes (50% benign, 50% malicious)

Sources: PhishTank, VirusTotal, official apps, user submissions

**🚀 Future Goals**

Offline mode

On-device AI (for privacy)

Browser & mobile app integration

**📚 Based on Research**

"A Deep Learning Framework for QR Code Analysis: Detecting Phishing URLs and Malicious APKs via Metadata and Permissions" 


**⚠️ Stay safe. Always scan QR codes with caution.**
