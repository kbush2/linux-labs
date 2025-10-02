# Lab 1 — Linux User & Group Management (RHEL 9)

**Goals:**  
- Create and manage local users.  
- Set and update passwords.  
- Create groups and manage memberships.  
- Configure password policies.  
- Verify users and groups in system files.  

---

## What I Did
- Created new users with `useradd`.  
- Set passwords with `passwd`.  
- Created a new group with `groupadd`.  
- Added users to groups with `usermod -aG`.  
- Created a user with custom options (`-m -s /bin/bash`).  
- Deleted a user with `userdel -r`.  
- Verified password expiration with `chage`.  
- Checked `/etc/passwd` and `/etc/group` to confirm changes.  

---

## Evidence

### Step 1 — Created a new user
![Step 1 — Create User](step1.png)

### Step 2 — Set a password
![Step 2 — Set Password](step2.png)

### Step 3 — Created a group
![Step 3 — Create Group](step3.png)

### Step 4 — Added user to the group
![Step 4 — Add User to Group](step4.png)

### Step 5 — Created another user with options
![Step 5 — Create User with Options](step5.png)

### Step 6 — Deleted a user
![Step 6 — Delete User](step6.png)

### Step 7 — Password expiration check
![Step 7 — Password Expiration](step7.png)

### Step 8 — Verified users & groups
![Step 8 — Verify Users & Groups](step8.png)

---

## Skills Demonstrated
- Linux user administration (`useradd`, `passwd`, `userdel`).  
- Linux group administration (`groupadd`, `usermod`).  
- Password and policy management (`chage`).  
- Verification of system files (`/etc/passwd`, `/etc/group`).  
- Sysadmin fundamentals aligned with RHCSA exam objectives.  
