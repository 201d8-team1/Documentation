## Standard Operating Procedure (SOP)

Version 1.0

## Effective Date: 5/16/2023

### 1. Purpose:

   The purpose of this SOP is to outline the necessary guidelines required for setting up a new computer with an email account, Microsoft One Drive acount and automatic backup script file to provide an efficent onboarding process.

### 2. Responsibilities:

   The IT department will be responsible for installing the Windows 10 OS, configuring email acounts, connecting Microsoft One Drive and implementing automatic file backups.
   HR will provide necessary account information to IT for email and Microsoft One Drive configuration.

### 3. Definitions and Abbreviations:

   A. User profile naming convention: firstinitial.lastname
   B. Email Signature format:
      Harvest Haven
      Name
      Title
      Department

### 4. Procedure:

   A. Computer Setup

   1. Install Windows 10 to new Computer.

      a. Use BluewaveTech_HarvestHaven_Win10.iso for install.

         1. ISO Has the following pre-installed:

            a. Google Chrome

            b. Apache Open Office Suite

            c. Malware Bytes antivirus

            d. EaseUS Recovery tool

            e. Winderstat

            f. Thunderbird email client
   2. Create an Admin profile.

   3. Createa user profile following the proper naming convention under definitions.

   4. Configure Windows 10 endpoint security as outlined in [Windows 10 Endpoing Security SOP](C:\Users\User\Desktop\CodeFellows Projects\Project_1\Documentation\SOPs\Windows 10 Endpoint Security SOP)

   5. Allow RDP access for Admin only and verify functionality.

   6. Enable file and printer sharing.

   B. Email Setup

   1. Ensure Thunderbird is installed and has a desktop shortcut.

   2. Obtain email account information from HR.

   3. Enter account credentials in Thunderbird.

   4. Set and apply to all messages a custom signature to the profile using the format listed under defenitions.

   5. Test email functionality.

   C. File Backup

   1. Use account credentials to connect Microsoft One Drive account.

   2. copy file [backup.bat](https://github.com/201d8-team1/Scripts/blob/main/backup.bat) to user profile.
         
      a. Change the paths in the file to match the directory paths in the user account.

      b. add a test file to the home documents folder, run the .bat file and confirm the test file is backed up to one drive.

### 5. Troubleshooting and Problem Solving:

   A. backup.bat file does not backup to one drive.

   1. Verify all file paths are correct for the new account.

      a. This includes the copy from path, copy to path and log file path.

### 6. Revision History:

   Version 1.0: Initial SOP Created

### 7. Approval:

   David Prutch
