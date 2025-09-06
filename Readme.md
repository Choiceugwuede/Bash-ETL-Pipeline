# Scheduling pipeline to run 12am daily with Cron Job

## Configuring Cron Job
### Open cron job text editor 
- wsl --install  -- install ubuntu for windows
- wsl.exe -d Ubuntu  -- launch ubuntu

- crontab -e  -- open crontab editor

#### Scheduled to run at 12:00 everyday and echo output and errors to log file.
0 0 * * * /mnt/host/c/Users/Bluechip/CDE/CDE-BASH-ETL-PIPELINE/ETL.SH > /mnt/host/c/Users/Bluechip/CDE/CDE-BASH-ETL-PIPELINE/ETL.LOG 2>&1

exit -- to exit ubuntu



