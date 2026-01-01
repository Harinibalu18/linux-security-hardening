This project demonstrates important Linux server security configurations including:
- SSH Hardening
- Fail2Ban Rules
- UFW Firewall Rules

Author: Harini B  
College: Jansons Institute of Technology, Coimbatore  
Year: December 2025

🔐 Security Components Used
1️⃣ SSH Hardening
- Disabled root login
- Changed SSH port to 2222
- Allowed only specific users
- Enforced password authentication rules

 2️⃣ Fail2Ban Configuration
- Intrusion prevention tool
- Blocks repeated failed login attempts from suspicious IPs

3️⃣ UFW Firewall Rules
- Allowed only required ports (22/80/443)
- Blocked unused ports

📌 How to Use
```bash
sudo systemctl restart ssh
sudo systemctl restart fail2ban
sudo ufw enable
sudo ufw status verbose
