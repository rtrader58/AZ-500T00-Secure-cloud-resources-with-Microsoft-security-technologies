# AZ-500T00 Learning Path 4 Labs Errata  – Total time ~220 Minutes (440 Min) 

When starting each lab choose Yes when prompted to be visible in networks<br>

# Remember anywhere the term Azure Active Directory (AAD) select Microsoft Entra ID  (Name change)

## Lab 7 – Key Vault (Implementing Secure Data by setting up Always Encrypted) ~75 Minutes (90)

### Exercise 1: Deploy the base infrastructure from an ARM template

Task 1: Deploy an Azure VM and an Azure SQL database <br>
Step 4:  Allfiles is located on the Desktop <br>

## Exercise 2: Configure the Key Vault resource with a key and a secret

Task 1: Create and configure a Key Vault <br>
Replace steps 1 - 4 with the following steps. (Key vault has to be created manually) <br>
Search for Key Vaults, select Key Vaults from the list <br>
Clcik + Create <br>
Select the pre-created Resource Group <br>
Name the Key Vault - az500kv-yourinitials <br>
Click Next <br>
Under Permission model select the radial button next to Vault access policy <br>
Under Access policies ensure your user account is checked <br>
Click Review and create > Create <br>

Step 9:  After selecting the 15 Certificate permissions > Clcik next > on the Principal tab search for your account (paste user account into search from the Lab Resources tab

## Exercise 3: Configure an Azure SQL database and a data-driven application

Task 2: Create a policy allowing the application access to the Key Vault<br>
Step 3:  Replace  ‘<Azure_AD_Application_Id>’ with your AP ID recorded in earlier step.  Make sure to include the ‘ at the beginning and end<br>

Task 5: Create a table in the SQL Database and select data columns for encryption <br>
Step 6:  The link will open in your local browser > copy the link and paste into the Edge browser in the lab (installation took ~10 minutes) <br>
Step 10:  If you get an error when connecting, manually type in your password <br>

Step 16:  You may have to sign into Azure to see your key vault.  Click sign into Azure <br>

# NOTE - Labs 8, 9, 10 and 11 launch in a single lab environment - Do Note End between labs ~180 Minutes (320)
### Keep an eye on the lab timer.  You will need to extend the lab at least once to complete 

## Lab 8 – Create a Log Analytics Workspace, Azure Storage Account, and Data Collection Rule (DCR)

### Exercise 1: Deploy an Azure virtual machine

Task 1: Deploy an Azure virtual machine <br>
Before step 7: Run the PowerShell CMDLET provided in the box above the lab instructions <br>
Step 10: Paste the password used for the labuser account in the Resources drop down > add 1234 to make the password 12 characters  <br>

### Exercise 3: Create an Azure storage account
Task 1: Create an Azure storage account  <br>
Step 3: Add your initials to the Storage Account Name  <br>

# ***** DO NOT END THE LAB!!  After completing Lab 8 use the drop down window at the top to move to lab 9  DO NOT END THE LAB!! *****

## Lab 9 – Configuring Microsoft Defender for Cloud Enhanced Security Features for Servers

No Errata <br>

# ***** DO NOT END THE LAB!!  After completing Lab 8 use the drop down window at the top to move to lab 9  DO NOT END THE LAB!! *****

## Lab 10: Enable just-in-time access on VMs

No Errata <br>

# ***** DO NOT END THE LAB!!  After completing Lab 9 use the drop-down window at the top to move to lab 10.  Do not end the lab!! *****<br>

## Lab 11: Microsoft Sentinel

### Exercise 1: Implement Microsoft Sentinel

Task 1: On-board Microsoft Sentinel<br>
Step 1:  You should already be logged in<br>

Task 2: Configure Microsoft Sentinel to use the Azure Activity data connector<br>
Step 13: Per the note it may take over 15 minutes before the connector shows Connected and Data recieved. Please wait for it to show Connected before proceeding. <br>

Task 3: Create a rule that uses the Azure Activity data connector <br>
Wait for Task 2 to complete before you continue >br>
Step 3: You will need to split off the instructions and go full screen to see the scroll bar > Click on the ... and select + Dreate Rule <br>

Task 4: Create a playbook<br>
Steps 1-3: Do these tasks in the VM, not your local OS.<br>
Step 3: Allfiles folder is located on your desktop <br>
Step 5: Leave email blank <br>
Step 12: Click on Change Connection > then follow the remaining step instructions > if pop is blocked > unblock it <br>
Step 15: Click on Change Connection > Click on LabUser <br>

Task 5: Create a custom alert and configure a playbook as an automated response<br>
Step 4: Tactics should say MITRE ATT&CK <br>
Step 10: Under Alert automation, select the drop-down and check the Select all box<br>

Task 6: Invoke an incident and review the associated actions<br>
Step 5: This can take several minutes to show up. Stretch & hydrate!<br>
