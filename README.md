# 🔐 Windows Vulnerability Scan Report – Task 3 (Internship)

This repository contains the results of a local vulnerability assessment conducted using **Nessus Essentials** on a Windows 11 system.

---

## 🎯 Objective

To scan the local system (localhost `127.0.0.1`) for known vulnerabilities and generate a detailed report as part of **Task 3** in the cybersecurity internship program.

---

## 🛠️ Tools Used

- **Nessus Essentials** (Tenable)
- **Target**: Localhost (`127.0.0.1`)
- **OS**: Windows 11

---

## 📊 Summary of Findings

- **Total Vulnerabilities Detected**: 75
- **Scan Duration**: 8 minutes
- **Scanner Type**: Basic Network Scan

### 🔍 Common Vulnerabilities Found

| Type                        | Description                                      |
|-----------------------------|--------------------------------------------------|
| SSL/TLS Issues              | Weak encryption or certificate mismatches        |
| SMB Protocol Detection      | Insecure file-sharing protocol detected          |
| HTTP/Web Server Details     | Web-related configuration details exposed        |
| Netstat Port Scanning       | Open ports accessible from the system            |
| DCE & Microsoft Services    | Exposure of internal services over the network   |

---

## 📂 Files

- `vulnerability_report.pdf` → Full scan report converted from `.nessus` file

---

## 📘 Notes

This assessment highlights services and configurations that may be optimized for better system hardening. No high or critical vulnerabilities were found, but awareness of low/informational findings helps improve future security.

---

📅 **Scan Date**: 26 June 2025  
👩‍💻 **Prepared by**: Hari Devadharshini  
🏁 **Internship Task**: Task 3 – Vulnerability Scan Report
