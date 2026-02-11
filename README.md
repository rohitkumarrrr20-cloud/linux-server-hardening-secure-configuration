# linux-server-hardening-secure-configuration
Linux Server Hardening and Secure Configuration project covering user management, SSH security, firewall setup, service control, file permissions, and log monitoring.
# Linux Server Hardening & Secure Configuration

## 👨‍💻 Author
**Name:** Ch Rohit Kumar  
**University:** Aditya University  
**Email:** rohitkumarrrr20@gmail.com  

---

## 📌 Project Overview

This project demonstrates comprehensive Linux server hardening and secure configuration practices. The objective is to minimize attack surfaces, enforce least privilege, secure remote access, and monitor system activity.

The project covers both theoretical concepts and practical implementation steps.

---

## 🔐 Topics Covered

### 1️⃣ Review Default Linux System Settings
- Identify system users (root, system, regular users)
- Review groups and permissions
- Check running and enabled services
- Identify open ports
- Analyze default security configurations

---

### 2️⃣ User Management & Least Privilege
- Identify existing users
- Remove unused accounts
- Lock/unlock user accounts
- Restrict sudo access
- Configure sudoers file securely
- Apply Principle of Least Privilege

---

### 3️⃣ Secure SSH Configuration
- Disable root login
- Configure SSH key-based authentication
- Disable password authentication
- Restart and verify SSH configuration
- Test secure login

---

### 4️⃣ System Updates & Automatic Security Patching
- Update package lists
- Upgrade installed packages
- Install unattended-upgrades
- Enable automatic security updates
- Verify update service status

---

### 5️⃣ Firewall Configuration (UFW)
- Enable firewall
- Set default deny policy
- Allow only required ports (SSH, HTTP, HTTPS)
- Verify firewall rules
- Apply least privilege to network traffic

---

### 6️⃣ Disable Unnecessary Services
- List running services
- Identify non-essential services
- Stop services
- Disable services from startup
- Verify reduced attack surface

---

### 7️⃣ Secure File Permissions
- Protect critical system files:
  - `/etc/passwd`
  - `/etc/shadow`
  - `/etc/sudoers`
- Secure SSH configuration files
- Secure user SSH keys
- Audit world-writable files
- Apply least privilege to files

---

### 8️⃣ Log Monitoring & Security Auditing
- Monitor authentication logs
- Review failed login attempts
- Track sudo activity
- Check login history
- Analyze system logs
- Detect suspicious behavior

---

## 🛡️ Security Principles Applied

- Principle of Least Privilege
- Principle of Least Functionality
- Attack Surface Reduction
- Secure Remote Access
- Continuous Monitoring
- Automatic Patch Management

---

## 🎯 Project Outcome

After implementing all configurations:

- Unnecessary users and services were removed
- Root login was disabled
- SSH secured with key-based authentication
- Firewall restricted to required ports only
- Sensitive files protected with strict permissions
- Logs actively monitored
- System updated with automatic security patches

This establishes a secure baseline configuration for Linux servers.

---

## 🧾 Conclusion

Comprehensive Linux server hardening was performed to strengthen system security, reduce vulnerabilities, and ensure controlled access. These configurations significantly improve the overall security posture of a production Linux environment.

---

## 📂 Keywords

Linux Hardening, Server Security, SSH Security, Firewall Configuration, UFW, System Administration, Cybersecurity, Log Monitoring, Least Privilege, Secure Configuration
