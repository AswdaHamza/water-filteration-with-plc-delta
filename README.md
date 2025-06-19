# 💧 Water Treatment Automation using Delta PLC

This project presents a fully automated water treatment system controlled by a **Delta DVP Series PLC**. The process is managed across three interconnected tanks using sensor feedback and ladder logic to ensure continuous, safe, and efficient operation.

---

## 📑 Project Description

The system automates water treatment through three stages:

1. **Tank 1** – Initial water collection and level control  
2. **Tank 2** – Aeration phase using dual blowers  
3. **Tank 3** – Final purification using UV and mixer motors  

Each tank is equipped with **low-level and high-level sensors**, and water transfer is handled by **alternating motors** for balanced operation. The purification cycle includes UV sterilization and thorough mixing before clean water is discharged.

---

## 🧠 Technologies Used

- **Delta PLC** (DVP Series)
- **WPLSoft** for ladder logic programming
- **Level sensors**, **blowers**, **UV motor**, **mixer motor**
- **PDF documentation** and **flowchart** for system visualization

---

## 📂 Files Included

| File                        | Description                              |
|-----------------------------|------------------------------------------|
| `ladder-diagram.pdf`        | Ladder logic in PDF format               |
| `flowchart.png`             | System flowchart showing process logic   |
| `final-report.pdf`          | Full technical report with explanations  |

---

## 🔍 How It Works

- Sensor-triggered logic ensures no overflow or dry-run
- Timed blower operation enhances aeration
- A 4-step purification cycle ensures water quality
- Alternating motors reduce wear and ensure redundancy

---

## 📘 Usage

1. Review the `flowchart.png` to understand the system logic  
2. Open `ladder-diagram.pdf` to see the full PLC program  
3. Read `final-report.pdf` for technical and hardware details

---

## 📜 License

This project is shared for educational and engineering reference under the [MIT License](LICENSE).
