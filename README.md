
# 🏢 Active Directory Lab – MobileHub
This project is a self-built Active Directory lab designed to simulate a real-world enterprise domain environment. It demonstrates core IT Support and SOC Analyst skills including identity management, user administration, and domain configuration.

<img width="900" height="500" alt="Screenshot 2026-05-26 at 3 26 54 pm" src="https://github.com/user-attachments/assets/2c095960-0bcf-4811-8eba-1cbd828b9865" />

## 🖥️ Environment

- 💻 Windows Server (2019/2022)
- 👥 Active Directory Domain Services (AD DS)
- 🖥️ Windows 10/11 Client Machines
- 🖥️ [VirtualBox](https://www.virtualbox.org/)

## ⚙️ Setup
- 🌐 Create NAT Network 

```
   - Network Name: `NAT Network`
   - IPv4 Network CIDR: `10.0.2.0/24`
   - Enable DHCP ✔
```
> 💡 **Tip:** NAT Network allows your VMs to communicate and access the internet.
  
## 🎥 Video


### Summary
- Installed Active Directory Domain Services (AD DS)
- Promoted server to Domain Controller
- Created domain: MobileHub.local
- Configured DNS for domain resolution
- Domain successfully created and ready for client join
- Created domain user accounts
- Assigned users to departments (IT, HR, Sales)
- Organised users within appropriate OUs
- Created security groups for access control
- Created distribution groups for communication
- Assigned users to relevant groups


<!-- <img width="1026" height="854" alt="oldname" src="https://github.com/user-attachments/assets/0a6f9f39-4397-4815-a8c5-fbed28872a14" />
Reboot and hold f8 to enter boot menu
select 'safe mode with networking'

Login with administrator account

open the Registry Editor
In the left pane navigate to
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\SchedulingAgent
In the right pane, double click OldName

The Value Data should be the old name of your PC . . .

Control panel -> system -> rename this pc
Enter the old name and restart

<img width="1045" height="983" alt="AD broken" src="https://github.com/user-attachments/assets/f2d7a3e7-8e67-489f-95e4-a28df3a1dcda" />
-->
