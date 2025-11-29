# 🧾 Daily User Log Archiver Script

## 📘 Overview
This Bash script automatically generates a daily log file that contains:
- Username
- Date and uptime
- Top 5 CPU-consuming processes
- Disk usage

It also organizes older logs by moving them to an archive folder and compresses them every Sunday.

---

## ⚙️ Features
✅ Automatic log generation  
✅ Weekly archive compression  
✅ Simple and reusable design  
✅ Can be automated using `cron`  

---

## 💻 How to Use

1. Clone or download this repository.
2. Make the script executable:
   ```bash
   chmod +x daily_log.sh
   ```
3. Run it manually:
   ```bash
   ./daily_log.sh
   ```
4. Or schedule it with `cron` (for daily automation):
   ```bash
   crontab -e
   0 20 * * * /home/aadarshi/daily_log.sh
   ```

---

## 📂 Folder Structure
```
daily_log.sh
daily_logs/
├── archive/
├── log_YYYY-MM-DD.txt
Linux_Report.pdf
screenshots/
explanation.txt
```

---

## 🧑‍💻 Author
**Aadarshi Bisht**  
University of Petroleum and Energy Studies (UPES)
