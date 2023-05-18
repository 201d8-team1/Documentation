# Remote and Offsite Support Standard Operating Procedure (SOP)

Version 1.1

Effective Date: 5/16/2023

## 1. Purpose:

   The purpose of this SOP is to outline the guidelines required to use PSREMOTE and RDP so MSP can provide remote support.

## 2. Responsibilities:

   A. The MSP will use PSREMOTE or RDP in to client systems as needed.
   
   B. MSP will perform troubleshooting and implement solutions to resolve issues.
   
   C. The MSP will perform administrative tasks using RDP or PSRemote.
   
   D. MSP will document all steps in troubleshooting process.
   
   E. MSP will notify the client of the issue status, possible downtime and resolution.
   
## 3. Definitions and Abbreviations:

   A. RDP - Remote Desktop Protocol.
   
   B. PSRemote - PowerShell Remote.

## 4. Procedure:

   A. Performing administrative actions.
      
      1. Using PSRemoting invoke commands to remote computer.

   B. RDP access.
   
      1. Open Remote Desktop.
      
      2. Input the IP address for the computer you are connecting to and select connect.
      
      3. Input Admin account credential when prompted. 
      
      4. Perform any neccessary actions required for the specific case.
      
      5. Verify full functionality of the system, to include user account functionality.
      
      6. End remote session.
      
   C. Client notification.
   
      1. Prior to service.
      
         A. Inform client of intended time to complete service. 
         
         B. If the machine is unavailable, work with the client to schedule a time.
         
         C. Inform client of potential downtime.
         
      2. Post Service.
      
         A. Notify client of services completed and machine status. 
         
## 5. Safety Concerns:

   A. When invoking PSRemote only run commands that are verified and neccessary.
   
   B. Perform data backup prior to troubleshooting to prevent data loss.
   
## 6. Troubleshooting and Problem Solving:

   A. If unable to establish a connection verify the IP address is correct.
   
   B. If unable to invoke command double check syntax.
   
   C. For unexpected issues found on client computer follow [Troubleshooting Methodology SOP](https://github.com/201d8-team1/Documentation/blob/main/SOPs/Troubleshooting%20Methodology%20SOP.md).

## 7. Revision History:

   Wayne 5/16/2023 Version 1.0: Initial SOP
   
   Wayne, David, Jason, Gerald 5/18/2023 Version 1.1: Revision
   
## 8. Approval

   Wayne Brandon, Jason Jung, David Prutch, Gerald Reitmeyer
