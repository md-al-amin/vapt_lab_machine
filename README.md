# 🔐 Vulnerable OS for VAPT Practice

A lightweight, intentionally vulnerable virtual machine based on **Q4OS**, created for hands-on **Vulnerability Assessment and Penetration Testing (VAPT)** practice. It is optimized to run on systems with only **512MB RAM**, making it suitable for low-resource environments.

---

## 📦 Download the VM

🗂️ Download the zipped virtual machine file from the link below:

👉 **[Download Vulnerable OS (Google Drive)](https://drive.google.com/file/d/1SIC09YglCb_SWPb2n9BPBn-AOJvIQUWU/view?usp=drive_link)**

After downloading, extract the archive and import it into your virtualization platform (e.g., VirtualBox or VMware).

---

## 🛠️ Pre-Installed Applications

This VM comes pre-configured with the following deliberately vulnerable web applications:

- [DVWA (Damn Vulnerable Web Application)](http://www.dvwa.co.uk/)
- [Mutillidae II](https://owasp.org/www-project-mutillidae-ii/)
- [WordPress](https://wordpress.org/) with known vulnerabilities

---


## 🔍 How to Find the IP Address

1. Login with the default credentials.
2. Open a terminal.
3. Run the following command:

   ```bash
   ip addr

---
## 🌐 Access URLs

Once the VM is running and connected to your network via DHCP, access the web applications using your browser:


### 🖥️ **System Requirements**


## 🖥️ System Requirements

| **Component**     | **Requirement**           |
|------------------|---------------------------|
| Operating System  | Q4OS (Debian-based)       |
| RAM               | 512 MB                    |
| Disk Space        | ~5 GB                     |
| Network           | NAT or Host-Only (DHCP)   |

## 🎯 Intended Use Cases

This VM is ideal for:

- Practicing web vulnerabilities:  
  - XSS (Cross-Site Scripting)  
  - SQL Injection  
  - CSRF (Cross-Site Request Forgery)
- Testing vulnerability scanners and automated tools
- Building ethical hacking and red team skills
- Preparing for certifications such as:  
  - CEH (Certified Ethical Hacker)  
  - OSCP (Offensive Security Certified Professional)  
  - Security+ and others
## ⚠️ Disclaimer

> ⚠️ **Important Notice:**  
> This virtual machine is provided **strictly for educational and ethical hacking practice only**.  
> Do **NOT** use this in production environments or unauthorized networks.  
> The creator is **not responsible** for any illegal activity, misuse, or damages resulting from the use of this project.

