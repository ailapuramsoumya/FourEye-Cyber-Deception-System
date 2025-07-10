# 🛡️ FourSight: Cyber Deception System

**FourSight** is a cyber deception tool designed to **trap attackers**, **monitor their actions**, and **study intrusion techniques**. By simulating vulnerable systems and services, FourSight offers a safe and controlled way to observe real-world hacking attempts.

---

## 🎯 Why Cyber Deception?

Traditional security systems react **after an attack** happens. **Cyber deception** turns the table:
- Detect attackers early
- Mislead them away from real assets
- Collect intelligence on their methods

---

## 🚀 Features

✅ **Decoy Services**  
Spin up fake servers (e.g., SSH, HTTP) to lure attackers.

✅ **Live Attack Monitoring**  
Track IPs, commands, and behaviors in real-time.

✅ **Attack Logging & Analysis**  
Export logs to CSV or SQLite for further study.

✅ **Customizable Traps**  
Easily add new decoy services or tweak system behavior.

✅ **Lightweight Deployment**  
Built with simplicity and speed in mind — perfect for research or education.

---

## 🛠️ Technologies Used

| Tool          | Purpose                    |
|---------------|----------------------------|
| Python        | Core logic and deception system |
| Flask         | (Optional) Web monitoring dashboard |
| SQLite / CSV  | Data storage and export    |
| Bash Scripts  | Simulated service setup    |

---

## 📂 Project Structure
FourSight/
├── decoys/ # Simulated decoy services
├── logs/ # Attacker logs and session data
├── app.py # Main runner
├── monitor.py # Real-time monitoring logic
├── utils/ # Helper functions
├── config.json # System configurations
└── README.md # This file


---

## 🧪 How to Run

> 💡 Make sure you’re using Python 3.11 or later.

1. **Clone the repository**
https://github.com/ailapuramsoumya/FourEye-Cyber-Deception-System.git


