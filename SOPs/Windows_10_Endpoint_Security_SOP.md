## Windows 10 Endpoint Security Standard Operating Procedure (SOP)

Version 1.0

## Effective Date: 5/16/2023

### 1. Purpose:

   The purpose of this SOP is to outline the necessary Windows 10 endpoint security configurations.

### 2. Responsibilities:

   IT will configure the security setting for all Harvest Haven computers with Windows 10 Pro installations.

### 3. Definitions and Abbreviations:

   [List key terms, acronyms, and abbreviations used in the SOP.]
### 4. Procedure:

A. Verify Windows Defender Antivirus running and real time protection is active, if not activate it.

   1. Open Windows Security.

   2. Select Virus and threat Protection.

   3. Verify No current threats under current threats.

   4. Verify no action needed under Virus and Threat Protection Settings. If action is needed select and follow prompts.

   5. Verify security intelligence is up to date under Virus and threat protection updates. If not select check for updates.

   6. Verify no action needed under Ransomware protection.

   7 Under Virus and protection setting select Manage Settings. Verify Real-time Protection, Cloud Based Protection and Tamper Protection are enabled.

B. Verify Windows Defender Firewall is active, if not activate it.

   1. In Windows Security Select Firewall and Network Protection.

   2. Verify Domain Network, Private Network and Public Network display Firewall is on. 

   3. If not enabled selecting restore Firewalls to default will reset them to on.

C. Verify Network Profile is set to Private.

   1. In Windows Security Firewall and Network Settings it will display Active next to Private Network.

   2. If Public is active Open Settings Network and Internet Access.

      a. Select Properties.

      b. Select Private

D. Verify SMBv1 disabled

   1. Open "Turn Windows Features on or off" in control panel.

   2. Locate SMB 1.0/ CIFS File Sharing Support and deselect.

E. Enable Reputation Based Protection to protect device from potentially malicious apps, files and websites.

   1. Open Windows Security.

   2. Select Apps and Browser Control.

   3. Select "Turn on" Reputation Based Protection.

### 5. References:

   1. [Microsoft Support: Reputation Based Protection](https://support.microsoft.com/en-us/microsoft-edge/how-can-smartscreen-help-protect-me-in-microsoft-edge-1c9a874a-6826-be5e-45b1-67fa445a74c8)

### 6. Revision History:

   Version 1.0: Initial SOP Created 5/16/2023 by David Prutch

### 7. Approval:

   David Prutch
