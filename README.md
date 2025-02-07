# Windows System Administration and Security Hardening - Good Corp, Inc.
(Ficticious Company)

This project showcases key Windows administration and security tasks performed as a junior system administrator, ensuring compliance, security, and efficient system management.</br>

Key Tasks:</br>
<b>User & Group Management</b>: Created users and groups, enforced password policies, and configured Active Directory.</br>
<b>Security & Compliance</b>: Implemented GPOs, restricted unnecessary apps via PowerShell, and configured SIEM-compatible logging.</br>
<b>Task Automation</b>: Used Task Scheduler for automated reporting and system monitoring.</br>
<b>Windows Update & Threat Investigation</b>: Ensured OS security patches were applied and analyzed user permissions, processes, and system anomalies for potential threats.
</br>

<h2> Step 1: Creating a Reports Folder on the Desktop </h2>
I executed the following command in the Windows Command Prompt to create a "reports" folder on the user's desktop
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/RRWZ9o2.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Step 2: Creating a Text File </h2>
I executed the following command in the Windows Command Prompt to create a report.txt file with the title "Baselining Report" inside the reports folder
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/a6ZQHO2.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Step 3: Appending Texts to a File </h2>
I executed the following command in the Windows Command Prompt to append a line "Created by [your name here]" to the report.txt file
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/TqoKtPd.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Step 4: Using Environment Variables in the Command Line </h2>
To append the desired information (OS, date, and username) to the report.txt file using environment variables, I executed the following command in the Windows Command Prompt
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/5MJrAKL.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Step 6: Enumerating Users </h2>
To enumerate all users on the system using the <b>net user</b> command, I executed the following command in the Windows Command Prompt
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/zn5f6rH.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Step 7: Checking Password Status </h2>
To find the password status of the user Alex, I executed the following command in the Windows Command Prompt
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/4vjyCkk.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Step 8: Enumerating Local Groups </h2>
To enumerate the local groups on the system using the <b>net localgroup</b> command, I executed the following command in the Windows Command Prompt
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/Ul5KOV8.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Step 9: Retrieving Password Policy </h2>
To enumerate the current password policy using the <b>net accounts</b> command, I executed the following command in the Windows Command Prompt
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/1wTcey9.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Step 10: Creating a Regular User </h2>
To create a regular user named <b>Anselm</b> with the password Ilovesales123! using the <b>net user</b> command in the Windows Command Prompt, I executed the following command
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/MqOzc5q.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Step 11: Adding User to Administrators Group </h2>
To add user named <b>Anselm</b> to the Administrators group, I executed the following commands in the Windows Command Prompt
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/xn4GYmD.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/8Kx2iq1.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/cO78xVP.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/lK6Uj2E.png" height="80%" width="90%" alt=""/>
<br />
<br />

  
<h2> Step 12: Configuring Password Policies Using Group Policy Editor </h2>
I launch gpedit.msc (Group Policy Editor) and set password policies for the entire Windows machine
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/twgjtBV.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/6hHR51w.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/7vIIdRT.png" height="80%" width="90%" alt=""/>
<br />
<br />
  
<h2> Step 13: Moving Files from User Directories to C:\ </h2>
To move the contracts folder from Alex's desktop to the C:\ drive, I executed the following command in the Windows Command Prompt
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/pQf23Na.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/RXxqcAJ.png" height="80%" width="90%" alt=""/>
<br />
<br />
  
<h2> Step 14: Creating Directories </h2>
To create the Backup, Script, and Log directories in the C:\ drive, I executed the following commands in the Windows Command Prompt
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/0riJBmr.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/1ezeqHJ.png" height="80%" width="90%" alt=""/>
<br />
<br />
  
<h2> Step 15: Listing Available Event Logs </h2>
To retrieve the Security and Application logs using PowerShell and output the latest 100 events in JSON format to the C:\Log directory, I executed the following command and verified that all contents had been retrieved as specified
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/MhWCuLE.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/W2zFjYi.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/pS4C4wB.png" height="80%" width="90%" alt=""/>
<br />
<br />

  
<h2> Step 16: Creating a PowerShell Script File </h2>
I created a PowerShell script called removepackages.ps1 to automate the uninstallation of packages listed in a CSV file named chocoactivity.csv. The script first imports the CSV using the Import-Csv cmdlet, and then loops through each package name using a foreach loop. For each package, the script runs the choco uninstall command with the -y parameter to automatically confirm the uninstallation. By executing this script, it initiates the uninstallation of the listed packages, streamlining the process of removing multiple packages efficiently.
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/Gq0jEZz.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/tVkXIoS.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/44rnybi.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/8jxf8pI.png" height="80%" width="90%" alt=""/>
<br />
<br />
  
<h2> Step :  </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/.png" height="80%" width="90%" alt=""/>
<br />
<br />
  
<h2> Step :  </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/.png" height="80%" width="90%" alt=""/>
<br />
<br />
  
<h2> Step :  </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/.png" height="80%" width="90%" alt=""/>
<br />
<br />
  
<h2> Step :  </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/.png" height="80%" width="90%" alt=""/>
<br />
<br />
