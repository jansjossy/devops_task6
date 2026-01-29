# devops_task6
# DevOps Internship - Task 6: Compression & Automation
**User:** Janzj
**System:** Ubuntu (WSL)

## 1. Manual Compression
- **Tool Used:** `tar` (Tape Archive)
- **Command:** `tar -czvf archive.tar.gz source_folder`
- **Result:** Successfully compressed files reducing size and combining them into a single artifact.

## 2. Automation Script
- **Script Name:** `automated_backup.sh`
- **Feature:** Uses `$(date)` variable to generate unique timestamps for every backup (e.g., `backup_2026-01-29.tar.gz`).

## 3. Cron Job Configuration
- **Schedule:** `* * * * *` (Every minute for testing purposes).
- **Config Command:** `crontab -e`
- **Verification:** Verified that new backup files appear in the `/backups` directory every 60 seconds.

<img width="960" height="1020" alt="Screenshot 2026-01-29 101051" src="https://github.com/user-attachments/assets/9f8ecbee-e471-42a4-8c2d-31c63795016a" />
<img width="960" height="1020" alt="Screenshot 2026-01-29 101044" src="https://github.com/user-attachments/assets/23d3ff88-f562-4f7b-ae2c-6422aabab9ae" />
<img width="960" height="1020" alt="Screenshot 2026-01-29 101030" src="https://github.com/user-attachments/assets/58334c27-ed24-47b1-80ca-b77a35cc172c" />

