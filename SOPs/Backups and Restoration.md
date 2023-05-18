## Backups & Restoration Standard Operating Procedure (SOP)

Version 1.2

## Effective Date: 5/16/2023

### 1. Purpose:

   A. Procedure on how to backup and restore user data, critical infrastructure configurations and hosted data.

### 2. Responsibilities:

   A. Backup all data (user, infrastructure, and configurations) to an cloud backup.
   
   B. Ensure that data is succesfully backed up onto cloud storage.
   
   C. Verify that the backups are functional.
   
   D. Double check that no files were skipped over.
   
### 3. Definitions and Abbreviations:

   A. Backup: Making a copy of data.
   
   B. Data: Files and settings configurations.
   
   C. Robocopy: Terminal command that automatically copies files from a defined location to another defined location.
   
### 4. Procedure:

   A. Ensure all new and updated files are saved in the user's Documents folder for backup.
   
   B. Every night at midnight event scheduler runs the robocopy script to backup files in the Documents folder to One Drive.
   
   C. Robocopy script outputs the backup log to One Drive folder.
   
   D. Check the log outputs to verify backup has completed without error and that the backup is up to date.
   
### 5. Safety Considerations:
   
   A. Make sure the computer is not in use by anyone when backing up.
   
   B. If backing up system configurations also make a system restore point.
   
### 6. Troubleshooting and Problem Solving:

   A. Robocopy does not backup files or store log in One Drive.
   
   B. Check the robocopy script for the correct paths and parameters.
   
   C. Ensure that robocopy is scheduled to run at midnight in task scheduler.
   
### 7. References:

   A. [How To Verify Backup](https://planetmagpie.com/news/woof-newsletter/2020/03/11/how-to-verify-that-your-backups-actually-work)
   
   B. [One Drive Data Resiliency](https://learn.microsoft.com/en-us/compliance/assurance/assurance-sharepoint-onedrive-data-resiliency)
   
   C. [Assurance Monitoring And Self Healing](https://learn.microsoft.com/en-us/compliance/assurance/assurance-monitoring-and-self-healing)
   
### 8. Revision History:

   Gerald 5/16/2023 1.0: Inital version/outline.

   Gerald, Jason, David 05/17/2023 1.1: Revisions.
   
   David 5/18/2023 1.2 Revisions outlined by Ethan Denny.

### 9. Approval:

   Gerald Reitmeyer, Jason Jung, David Prutch.
  
