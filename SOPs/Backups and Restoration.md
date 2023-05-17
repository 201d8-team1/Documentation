Backups & Restoration Standard Operating Procedure (SOP)

Version 1.0

Effective Date: 5/16/2023

1. Purpose:

   Procedure on how to backup and restore user data, critical infrastructure configurations and hosted data.

2. Responsibilities:

   Backup all data (user, infrastructure, and configurations) to an cloud backup.
   Ensure that data is succesfully backed up onto cloud storage.
   Verify that the backups are functional.
   Double check that all files that needed to be backed up were backed up and none were skipped over.
   
3. Definitions and Abbreviations:
   Backup: Making a copy of data 
   Data: Files and settings configurations
   Robocopy: Terminal command that automatically copies files from a defined location to another defined location
   
4. Procedure:

   Identify what files are in need of a backup and put them into a backup folder
   Every night at midnight event scheduler runs robocopy script to backup files to one drive
   First thing in the morning verify backup has completed without error and that the backup is up to date
   
5. Safety Considerations:
   
   Make sure the computer is not in use by anyone when backing up
   If backing up system configurations also make a system restore point
   
6. Troubleshooting and Problem Solving:
   Identify a error code
   Deduce when/where the error code
   Replicate (if possible)
   
7. References:
   https://planetmagpie.com/news/woof-newsletter/2020/03/11/how-to-verify-that-your-backups-actually-work
   https://learn.microsoft.com/en-us/compliance/assurance/assurance-sharepoint-onedrive-data-resiliency
   https://learn.microsoft.com/en-us/compliance/assurance/assurance-monitoring-and-self-healing
   
8. Revision History:
Gerald 5/16/2023 1.0: Inital version/outline

   [Maintain a log of revisions made to the SOP, including version numbers, dates, and a brief description of the changes.]
9. Approval:
Gerald
   [Include a section for signatures or approvals from relevant stakeholders or departments.]
