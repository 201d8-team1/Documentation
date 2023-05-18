# Employee Onboarding Standard Operating Procedure (SOP)

Version 1.3

Effective Date: 5/17/2023

## 1. Purpose:

   A. The purpose of this SOP is to outline the necessary guidelines for setting up a new client Windows 10 machine with an email account, Microsoft One Drive acount and automatic backup script file to provide an efficent onboarding process.

## 2. Responsibilities:

   A. The MSP is responsible for installing the Windows 10 OS, configuring email acounts, connecting Microsoft One Drive and implementing automatic file backups.
   
   B. Client HR will provide necessary account information to MSP for email and Microsoft One Drive configuration.
   
   C. MSP will provide new employee with account access information.

## 3. Definitions and Abbreviations:

   A. User profile naming convention: firstinitial.lastname
   
   B. Email Signature format:
   
      Harvest Haven
      
      Name
     
      Title
      
      Department

## 4. Procedure:

   A. Computer Setup

   1. Install Windows 10 Pro to new Computer.

      a. Use BluewaveTech_HarvestHaven_Win10Pro.iso for install.

         1. ISO Has the following pre-installed:

            a. Google Chrome

            b. Apache Open Office Suite

            c. Malware Bytes antivirus

            d. EaseUS Recovery tool

            e. Winderstat

            f. Thunderbird email client
            
            g. Admin RDP access enabled for LAN
            
            h. PowerShellRemote enabled for LAN

   2. Create an user profile following the proper naming convention under definitions.

   3. Configure Windows 10 endpoint security as outlined in [Windows 10 Endpoing Security SOP](https://github.com/201d8-team1/Documentation/blob/main/SOPs/Windows_10_Endpoint_Security_SOP.md)

   4. Verify RDP access for Admin only and verify functionality.

   5. Verify PSRemote capabilities.

   B. Email Setup

   1. Ensure Thunderbird is installed and has a desktop shortcut.

   2. Obtain email account information from client HR.

   3. Enter account credentials in Thunderbird.

   4. Set and apply to all messages a custom signature to the profile using the format listed under defenitions.

   5. Test email functionality.

   C. File Backup

   1. Use account credentials to connect Microsoft One Drive account.

   2. Copy file [backup.bat](https://github.com/201d8-team1/Scripts/blob/main/backup.bat) to user profile.
         
      a. Change the paths in the file to match the directory paths in the user account.

      b. Add a test file to the home documents folder, run the .bat file and confirm the test file is backed up to one drive.
      
      c. In Windows task scheduler set task to run backup.bat daily at midnight.
      
   D. Notify new employee of user account information.
      
   1. Draft welcome email consisting of the following:
   
      a. PC user account credentials.
      
      b. Microsoft 365 credentials. 
      
      c. cc Harvest Haven HR in email for verification of completion.
      
      d. Bluewave Tech Solutions support contact information.

## 5. Troubleshooting and Problem Solving:

   A. backup.bat file does not backup to one drive.

   1. Verify all file paths are correct for the new account.

      a. This includes the copy from path, copy to path and log file path.

## 6. Revision History:

   David 05/16/2023 Version 1.0: Initial SOP Created 
   
   David, Jason, Gerald 05/17/2023 Version 1.1: Revisions
   
   David 05/17/2023 Version 1.2: Provide credentials to new hire.
   
   David, Jason, Wayne, Gerald 5/18/2023 Version 1.3: Revision.

## 7. Approval:

   David Prutch, Gerald Reitmeyer, Jason Jung, Wayne Brandon
