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
<img width="1440" alt="Image" src="https://github.com/user-attachments/assets/c18cc816-8899-4a84-b981-c6dcd76d91b3" />
<img width="1440" alt="Image" src="https://github.com/user-attachments/assets/b558af37-8b31-4e87-9f3c-20928a60732e" />
<img width="1440" alt="Image" src="https://github.com/user-attachments/assets/6aea7bb8-f8ef-4d12-acfb-c5c9568b101d" />
<img width="1440" alt="Image" src="https://github.com/user-attachments/assets/13b062f0-6ac3-47fc-8aae-3ed5e921568d" />
<img width="1439" alt="Image" src="https://github.com/user-attachments/assets/2b974898-01f0-4950-84ac-ebda318c3c0a" />
<br />
<br />
I also worked with connecting various devices via wireless LAN and Bluetooth. Here you can see the process of verifying an internet connection on the laptop after connecting to the network with a wireless adapter and confirming DHCP:  <br/>
<img width="1439" alt="Image" src="https://github.com/user-attachments/assets/53f8abe9-7429-4dd6-acfd-3c5850c96ac5" />
<img width="1440" alt="Image" src="https://github.com/user-attachments/assets/8d0c8f71-ccc7-4797-be35-6745cbb49393" />
<img width="1436" alt="Image" src="https://github.com/user-attachments/assets/e48276d2-a6ac-4961-b4a0-6b7f0df95bf4" />
<img width="1440" alt="Image" src="https://github.com/user-attachments/assets/2336fa88-b591-4fc7-a895-881b01a271fa" />
<img width="1437" alt="Image" src="https://github.com/user-attachments/assets/da2b19fb-8976-4368-a6d7-6414b2e3560a" />
<img width="1437" alt="Image" src="https://github.com/user-attachments/assets/02bdf7f9-9ef8-4aae-9362-213704a0ee6a" />
<br />
<br />
Connecting devices via Bluetooth, the sound that played was a brief clip of crickets chirping:  <br/>
<img width="1439" alt="Image" src="https://github.com/user-attachments/assets/eea216aa-3714-4f46-96a0-2aa4d05cb80d" />
<img width="1440" alt="Image" src="https://github.com/user-attachments/assets/f489fd2e-38af-4229-8f5b-7fd3091f5e4e" />
<br />
<br />
Lastly I tethered to a Smartphone via Bluetooth with the User Laptop to connect to the internet:  <br/>
<img width="1434" alt="Image" src="https://github.com/user-attachments/assets/2e64d1b4-c5b1-4035-816d-daf0781e783b" />
<img width="1439" alt="Image" src="https://github.com/user-attachments/assets/e5f5aaff-0c5e-4743-943a-d0bb926cf61a" />
<img width="1440" alt="Image" src="https://github.com/user-attachments/assets/2802a65d-48a2-4d22-bcc4-31cee2416a7e" />
<img width="1439" alt="Image" src="https://github.com/user-attachments/assets/701b5fc5-1f7d-46f3-851b-f6e234133028" />
<img width="1437" alt="Image" src="https://github.com/user-attachments/assets/e8fb8fe5-4d3d-47fa-8106-19742a66d040" />
<img width="1430" alt="Image" src="https://github.com/user-attachments/assets/038e7e35-7f79-438b-be94-680559f9ded4" />
<img width="1437" alt="Image" src="https://github.com/user-attachments/assets/a334d4e5-58de-42a3-8033-22a27a4239e6" />
<br />
<br />
I enjoyed working with Cisco Packet Tracer as it provides an approximation of working hands on with the equipment and concepts involved with networking. I look forward to expanding my knowledge with additional Packet Tracer offerings in the future.
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
