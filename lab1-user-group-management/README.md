# Linux Lab 1 — User & Group Management (RHEL 9)

🎯 **Focus:** Creating and managing users and groups in RHEL.  
🛠 **Commands used:** `useradd`, `passwd`, `groupadd`, `usermod -aG`, `userdel -r`, `chage`.

---

## Step 1 — Create a New User
```bash
sudo useradd devuser
id devuser
sudo passwd devuser
sudo groupadd devgroup
cat /etc/group | grep devgroup
sudo usermod -aG devgroup devuser
groups devuser
sudo useradd -m -s /bin/bash projectuser
id projectuser
sudo userdel -r projectuser
sudo chage -l devuser
cat /etc/passwd | tail -n 5
cat /etc/group | tail -n 5

---

## 🔑 Why this is strong
- **Headings** make each step clear.  
- **Code blocks** show the exact commands.  
- **Inline screenshots** prove you actually ran them.  
- **Summary at the end** ties it back to RHCSA objectives.  

---

👉 Do you want me to now update the **root README.md** with these same step labels (instead of just a plain list), so recruiters see a polished summary before they even click into the lab?
