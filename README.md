<h1>Learning Active Directory Basics with TryHackMe</h1>

<h2>Description</h2>
In the Active Directory Basics room on TryHackMe, I gained foundational knowledge of Active Directory (AD) and its key components. The room primarily focuses on understanding AD structure, users, groups, and permissions. By the end of the room, I developed hands-on skills to navigate and manipulate Active Directory in both offensive and defensive contexts.
<br />

<h2>Utilities Used</h2>

- Active Directory Users and Computers (ADUC): A Microsoft management tool for administering AD environments.
- PowerShell: A powerful scripting language and automation tool used to manage and query Active Directory. Participants learn how to write PowerShell scripts to interact with AD, manage users, and automate tasks.
- BloodHound: A tool for Active Directory enumeration and privilege escalation.
- Nmap: Used for network scanning to detect AD services like SMB and LDAP.
</b> 

<h2>Skills Used</h2>

- Enumeration: Techniques to discover AD users, groups, and other objects.
- Privilege Escalation: Understanding how to exploit weaknesses in AD permissions for privilege escalation.
- Windows Security: Knowledge of security policies and configurations in an AD environment.

<h2>Environments Used</h2>

- Windows Server: The server OS typically used to host Active Directory.
- TryHackMe's Virtual Machines: Simulated environments where participants can interact with AD systems and practice real-world techniques.

<h2>Highlights:</h2>

<p align="center">
A brief intro on AD and Domains followed by firing up the virtual machine: <br/>
<img width="1437" alt="Image" src="https://github.com/user-attachments/assets/a5cd0b6a-63e5-4b1a-b2a7-569c06b7879d" />
<img width="1438" alt="Image" src="https://github.com/user-attachments/assets/d57c34f3-6f08-4b1e-9cdb-a777f66b197e" />
<img width="1434" alt="Image" src="https://github.com/user-attachments/assets/1076c6e7-3282-4a92-ad06-682e71abb2d0" />
<br />
<br />
Organizational Units (OU's) and Managing Users:  <br/>
<img width="1431" alt="Image" src="https://github.com/user-attachments/assets/7b2380c5-7207-45c0-8986-4f2f1f7e19cb" />
<img width="1434" alt="Image" src="https://github.com/user-attachments/assets/58fcb512-4990-4ffa-82dc-d9c026e73e0b" />
<img width="1435" alt="Image" src="https://github.com/user-attachments/assets/e3af073f-f5fb-41ab-afaf-c1f48a00d18e" />
<br />
<br />
From here we moved into Delegation: <br/>
<img width="1434" alt="Image" src="https://github.com/user-attachments/assets/b3591363-7c92-424a-89f0-bc9cdcb4ee9e" />
<img width="1430" alt="Image" src="https://github.com/user-attachments/assets/0e37d7ab-7022-48a2-a1f2-36755fc98e12" />
<img width="1431" alt="Image" src="https://github.com/user-attachments/assets/36836159-71bb-4a98-9f5e-0b3f3413192d" />
<br />
<br />
Using PowerShell to administer changes at the command line, changing a users password and accessing a flag in a text file on the user sophies desktop to complete the TryHackMe challenges:  <br/>
<img width="1433" alt="Image" src="https://github.com/user-attachments/assets/bbed1214-8667-4837-830f-5be57c2fc731" />
<img width="1433" alt="Image" src="https://github.com/user-attachments/assets/6e119f7f-4b56-437c-92d2-c3555124106c" />
<img width="1430" alt="Image" src="https://github.com/user-attachments/assets/c6d75b3d-efd5-4370-b4a6-627ed112ff7a" />
<br />
<br />
Managing computers in AD:  <br/>
<img width="1430" alt="Image" src="https://github.com/user-attachments/assets/8b411268-271e-46ab-bb91-78671a374e36" />
<img width="1426" alt="Image" src="https://github.com/user-attachments/assets/66e89715-06a9-43d8-8b26-fb0f744ffaa4" />
<br />
<br />
Managing Group Policies, in this case minimum password length, screen lock and access to control panel changes for various groups:  <br/>
<img width="1431" alt="Image" src="https://github.com/user-attachments/assets/a2d801d9-aacc-4a1e-b262-e45b3eb4dc4d" />
<img width="1435" alt="Image" src="https://github.com/user-attachments/assets/e7960418-5b15-4047-9ed2-2f2dc6b623b9" />
<img width="1433" alt="Image" src="https://github.com/user-attachments/assets/5a9accbf-ca8e-4edc-9631-7e090ed0dad8" />
<img width="1431" alt="Image" src="https://github.com/user-attachments/assets/54312218-5fb1-4193-b65e-8094be87fe28" />
<img width="1429" alt="Image" src="https://github.com/user-attachments/assets/fd903a03-9065-460d-94e6-8256d46f564c" />
<img width="1431" alt="Image" src="https://github.com/user-attachments/assets/b6718f3f-28e3-4350-917f-74b1e2581a41" />
<img width="1427" alt="Image" src="https://github.com/user-attachments/assets/bf40dec5-d370-40df-a850-45e2f9361063" />
<img width="1432" alt="Image" src="https://github.com/user-attachments/assets/29d67fd3-7443-4bce-aeff-ad84416e3392" />
<img width="1435" alt="Image" src="https://github.com/user-attachments/assets/7ae9a89b-67db-4f30-b61c-4628827e0597" />
<img width="1434" alt="Image" src="https://github.com/user-attachments/assets/1440ddec-2706-4400-9d29-e3226b95b5fb" />
<img width="1431" alt="Image" src="https://github.com/user-attachments/assets/ee5e4571-912f-4941-a591-e3c49eebe095" />
<br />
<br />
Authentication domains; Trees, Forests and Trusts; Conclusion :  <br/>
<img width="1428" alt="Image" src="https://github.com/user-attachments/assets/2ffcaa76-a5e9-43e3-99b1-084d7bcd54c5" />
<img width="1431" alt="Image" src="https://github.com/user-attachments/assets/b9d32aba-1352-45a3-b4f7-5cb251cd7707" />
<img width="1434" alt="Image" src="https://github.com/user-attachments/assets/a8ade793-69d1-4665-a25f-972ff1f0dd97" />
<br />
<br />
Working with TryHackMe is a great way to learn more about information technology and cybersecurity and I'm looking forward to digging deeper into the lessons the provide in the future.
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
