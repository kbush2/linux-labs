# Linux Labs — RHCSA Prep & Sysadmin Practice

Hands-on **RHEL 9** labs documented with commands and screenshots.  
Built by a U.S. Army veteran pivoting into **IT Helpdesk → Sysadmin → Cloud/Security**.

---

## 📂 Labs

- **Lab 1 — User & Group Management**  
  👉 [Open Lab 1](./lab1-user-group-management)

  Topics: `useradd`, `passwd`, `groupadd`, `usermod -aG`, `userdel -r`, `chage`, `/etc/passwd`, `/etc/group`

*(More labs coming soon: File permissions, ACLs, storage & LVM, SELinux, systemd, networking, etc.)*

---

## 🔑 Why This Repo?
- Demonstrates **hands-on Linux administration** aligned with **RHCSA exam objectives**.  
- Each lab shows **commands + screenshots** for verification.  
- Highlights my ability to **document technical workflows** clearly for both engineers and recruiters.

---

## 🔗 Profiles
- GitHub: [github.com/kbush2](https://github.com/kbush2)  
- LinkedIn: *www.linkedin.com/in/kamal-bush*

  # Lab 1 — Windows User & System Basics

**Goals:**  
- Create and manage local users.  
- Generate and review failed logon events.  
- Install/uninstall software.  
- Verify networking with NAT vs Bridged.  
- Practice device management basics.  

## What I Did
- Created local user `labuser` using `net user`.
- Generated a failed logon and captured Event ID 4625 in Event Viewer.
- Installed and uninstalled **7-Zip**.
- Verified IP configuration and connectivity with `ipconfig` and `ping`.
- Compared NAT vs Bridged modes in VirtualBox.


## Evidence

### Step 1 — Create a New User
![Create a New User](step1.png)

### Step 2 — Set a Password
![Failed logon Event 4625](03_event-4625-failed-logon.png)

### Step 3 — Create a Group
![Installed 7-Zip](04_Installed-App-List.png)

### Step 4 — Add User to the Group
![Ping test](07_ping-8888.png)

### Step 5 — Create Another User with Options
![NAT connectivity](08_NAT-conn

### Step 6 — Delete a User
![Bridged connectivity](09_Bridged-connectivity.png)

### Step 7 — Password Expiration
![Bridged connectivity](09_Bridged-connectivity.png)

### Step 8 — Verify All Users and Groups
![Bridged connectivity](09_Bridged-connectivity.png)



---

## 🧰 Tech Stack
`RHEL 9` · `Bash` · `systemd` · `SELinux` · `LVM` · `SysAdmin`
