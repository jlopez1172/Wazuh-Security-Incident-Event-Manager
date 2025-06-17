# 🛡️ Wazuh SIEM – Brute Force Attack Simulation Lab

As part of my graduate studies in cybersecurity, this lab focused on detecting and analyzing a simulated brute-force attack using **Wazuh**, an open-source SIEM built on the Elastic Stack.

---

## 🔍 Objectives

- Explore the Wazuh SIEM Dashboard
- Filter and analyze over 700+ security events
- Simulate a brute-force SSH attack via Bash script
- Investigate authentication logs and MITRE ATT&CK mappings
- Detect login attempts from non-existent users

---

## 🧠 Key Takeaways

- ✅ Identified 137 failed SSH login attempts for the `root` user in under 5 minutes  
- ✅ Detected "Promiscuous Mode" network alerts indicating packet sniffing tools
- ✅ Located relevant logs (`/var/log/auth.log`) and rule IDs for failed logins
- ✅ Used advanced filters (`rule.level`, `full_log`) to remove noise and prioritize threats
- ✅ Mapped alerts to MITRE ATT&CK techniques like **Brute Force**

---

## 🧰 Tools & Technologies

- **SIEM:** Wazuh (Elastic Stack)
- **OS:** Linux
- **Script:** Bash (`attack.sh`, `.challenge.sh`)
- **Frameworks:** MITRE ATT&CK
- **Log Analysis:** `/var/log/auth.log`, Wazuh Dashboards

---

## 🎯 Outcome

This lab reinforced my skills in:
- Threat hunting
- Event correlation
- SIEM tuning
- Understanding real-world brute-force behavior
- Investigative log filtering

---

## 📸 Screenshots

See attached word document.

---

## 📚 Learning In Progress

I’m currently pursuing a **Master’s in Cybersecurity** and continuously building hands-on labs like this one.  

Check out more of my work on [LinkedIn](https://linkedin.com/in/profile4joshualopez) and [GitHub](https://github.com/jlopez1172).
