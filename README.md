# Lab 1 — Linux User & Group Management (RHEL 9)

**Goals:**  
- Create and manage local users.  
- Set and update passwords.  
- Create groups and manage memberships.  
- Configure password expiration policies.  
- Verify users and groups in system files.  

---

## What I Did
- Created a new user with `useradd`.  
- Set a password with `passwd`.  
- Created a group with `groupadd`.  
- Added a user to the group with `usermod -aG`.  
- Created another user with options (`-m -s /bin/bash`).  
- Deleted a user with `userdel -r`.  
- Verified password expiration with `chage`.  
- Checked `/etc/passwd` and `/etc/group` to confirm results.  

---

## Evidence

### Step 1 — Create a New User
![Step 1 — Create User](step1.png)

### Step 2 — Set a Password
![Step 2 — Set Password](step2.png)

### Step 3 — Create a Group
![Step 3 — Create Group](step3.png)

### Step 4 — Add User to the Group
![Step 4 — Add User to Group](step4.png)

### Step 5 — Create Another User with Options
![Step 5 — Create User with Options](step5.png)

### Step 6 — Delete a User
![Step 6 — Delete User](step6.png)

### Step 7 — Password Expiration
![Step 7 — Password Expiration](step7.png)

### Step 8 — Verify All Users & Groups
![Step 8 — Verify Users & Groups](step8.png)

---

## Skills Demonstrated
- Linux user administration (`useradd`, `passwd`, `userdel`).  
- Linux group administration (`groupadd`, `usermod`).  
- Password and policy management (`chage`).  
- Verification of system accounts and groups (`/etc/passwd`, `/etc/group`).  
- Sysadmin fundamentals aligned with **RHCSA exam objectives**.  

