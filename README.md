# BACKUP-AUTOMATION
Backups are an essential part of database administration as they provide a way to recover data in case of data loss or a disaster, like a power outage or a cyber-attack.  Automating the backup process ensures that backups are taken at regular intervals and reduces the risk of human error. 

**BACKUP AUTOMATION **

One of the major responsibilities of a DBA is ensuring that, regular backups of the database are running.

**CASE STUDY **

A Company is a medium-sized organization that heavily relies on its SQL Server database for critical business operations. They have experienced data loss in the past due to manual backup processes and are looking for a robust backup automation solution to ensure data availability and minimize downtime.

**Solution:**
To address the client's challenges and meet their backup requirements, a comprehensive backup automation system was implemented. Their backup process are listed below 

**1. Full backup every SUNDAY 11PM**
**2. Differential backup Every DAY except sundays at 10pm**
**3. Transaction Log backup to run every 15 minutes**

The key tools used is SQL SERVER MAINTENANCE PLAN in SSMS

**PROCESS OF BACKUP AUTOMATION USING SQL SERVER MAINTENANCE PLAN**  
