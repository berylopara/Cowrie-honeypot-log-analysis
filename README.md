# 🧠 Incident Response: Investigating Logs with Cowrie Honeypot  

**Author:** Beryl Amondi Opara  
**Course:** IBM Cybersecurity Analyst Professional Certificate  
**Module:** Penetration Testing, Threat Hunting, and Cryptography  
**Lab:** Investigate Logs Using Cowrie  

---

## 📖 Overview  

This project demonstrates how to investigate and analyze security events using the **Cowrie honeypot**, a medium-interaction SSH and Telnet honeypot used to log brute-force attacks and shell interactions.  

The objective of this lab was to simulate an attacker’s interaction with the system, collect log data, analyze the captured activity, and then safely shut down the honeypot environment.  

---

## 🧰 Tools & Environment  

- 🐋 **Docker** — Used to deploy and manage the Cowrie honeypot container.  
- 🕵🏽‍♀️ **Cowrie Honeypot** — Simulated unauthorized access attempts and logged attacker actions.  
- 🧾 **Cowrie Logs (cowrie.json, cowrie.log)** — Contained detailed records of simulated attacks.  
- 💻 **Linux Terminal** — For monitoring, investigation, and container management.  

---

## 🧪 Steps Performed  

### **1️⃣ Run Cowrie on Docker**  
Launched the Cowrie honeypot inside a Docker container to begin capturing attacker activity.  

![Run Cowrie on Docker](./Cowrie%20on%20Docker%20running%20successfully.png)

---

### **2️⃣ Telnet to Cowrie**  
Connected to the honeypot via Telnet to simulate unauthorized access and observe Cowrie’s logging behavior.  

![Telnet to Cowrie](./Telnet%20session.png)

---

### **3️⃣ Analyze Logs**  
Reviewed and analyzed captured logs to identify login attempts, IP addresses, commands executed, and timestamps.  

![Analyze Logs](./Log%20analysis.png)

---

### **4️⃣ Terminate Cowrie**  
Safely stopped and removed the Cowrie container after completing the log investigation.  

![Terminate Cowrie](./Container%20termination.png)

---

## 📊 Key Findings  

- Multiple **brute-force login attempts** were detected, confirming Cowrie’s ability to capture attacker data.  
- **Command logs** revealed attacker patterns, common reconnaissance commands, and behavioral insights.  
- The exercise reinforced the importance of **log analysis** in understanding threat actor behavior and improving detection systems.  

---

## 🧠 Key Takeaways  

- Honeypots like **Cowrie** provide safe environments for studying cyberattack techniques.  
- **Log analysis** is a vital component of incident response and digital forensics.  
- Proper environment termination ensures that logs are preserved and no unintended network exposure remains.  

---

## ⚙️ Ethical & Safety Disclaimer  

All tasks were performed in a **controlled, educational lab environment** under the IBM Cybersecurity Analyst program.  
No real systems were targeted or harmed.  
This project was completed purely for **educational and defensive cybersecurity learning purposes**.  

---

## 🏁 Summary  

This hands-on lab enhanced my understanding of **incident response, log analysis, and honeypot monitoring** — essential skills for a future **SOC Analyst**.  

---

✨ **Project Completed by:** *Beryl Amondi Opara*
