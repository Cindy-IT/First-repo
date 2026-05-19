# 👋 Hi, I'm Cindy

💻 IT Support & Cybersecurity Professional
🛡️ CompTIA Security+ Certified
📍 Passionate about troubleshooting, security, and continuous learning

---

## 🎯 Career Goals
Currently seeking opportunities in:
- IT Support
- Helpdesk
- SOC Analyst

I’m building hands-on skills in system administration, troubleshooting, networking, and security while documenting my learning journey through projects and labs.

---

## 🛠️ Technical Skills

### Operating Systems & Support
- Windows troubleshooting
- Password resets & account recovery
- Remote desktop support basics
- User support & technical documentation

### Active Directory
- User account creation
- Password management
- Account unlock/reset
- Group Policy basics

### Networking
- Wi-Fi troubleshooting
- Routers & modems
- Basic network connectivity
- Network fundamentals

### Scripting
- Basic batch scripting

---

## 📚 Currently Learning
- ServiceNow
- Jira
- SOC workflows
- Security monitoring tools
- Advanced troubleshooting

---

## 🚀 Projects & Labs
Here you'll find:
- IT support troubleshooting guides
- Active Directory labs
- Networking practice
- Security learning notes
- Hands-on technical projects

---

## 🏆 Certifications
- ✅ CompTIA Security+

---

## 📫 Connect With Me
- GitHub: github.com/Cindy-IT/First-repo
- https://github.com/Cindy-IT/First-repo


# My IT Support Portfolio
## My first guide: Laptop won't connect to Wi-Fi

### Problem:
The laptop shows no Wi-Fi networks or says "Cannot connect to this network."

### Step-by-step fix:
1. **Check if Wi-Fi is turned on** – Look for a physical switch on the laptop or press Fn + one of the F keys (usually F2, F3, or F12)
2. **Restart the modem and router** – Unplug for 30 seconds, plug back in
3. **Forget and reconnect** – Click the Wi-Fi icon → your network name → "Forget" → reconnect and type the password again
4. **Run the Windows troubleshooter** – Settings → Network & Internet → Status → "Network troubleshooter"
5. **Last resort** – In Command Prompt (run as admin), `netsh winsock reset` then restart the laptop

### When to call IT support
If none of these work after 15 minutes, the network adapter might be failing.

## My Second Guide: Forgot Windows Password

### Problem
A user cannot log into their work computer because they forgot their password.

---

## 1. Self-Service Password Recovery
- Click “I forgot my password” on the login screen
- Answer configured security questions
- Reset the password if verification succeeds

---

## 2. Administrator-Assisted Reset
- If self-service recovery fails, contact IT support
- An administrator can reset the password from another authorized system

---

## 3. Security Best Practices
- Never bypass company security controls
- Always follow organizational password reset procedures
- Ensure recovery actions are properly authorized

## My third guide: Computer is running very slow

### Problem:
A user complains their computer takes forever to open programs, boot up, or browse the internet.

### Step-by-step fix:

#### 1. Quick wins (no technical skills needed)
- Restart the computer (not shut down — actually click "Restart")
- Close unused browser tabs (Chrome/Firefox/Edge eat memory)
- Check if antivirus is running a scan (wait for it to finish)

#### 2. Clean up temporary files (Windows)
- Press `Windows key + R`, type `temp`, press Enter
- Delete everything in that folder (safe to delete)
- Do the same with `%temp%` and `prefetch`

#### 3. Check what's slowing it down
- Press `Ctrl + Shift + Esc` to open Task Manager
- Click "More details" (bottom of window)
- Look at "CPU" and "Memory" columns if anything is at 100%, that's the problem

#### 4. When to escalate to IT
- If disk is at 100% constantly (hard drive may be failing)
- If CPU is at 100% with no programs open (possible virus)
- If user has less than 4GB RAM (need hardware upgrade)

### Pro tip for IT support:
Before doing anything, ask the user: *"When did this start happening?"* The answer often reveals the cause; a new update, a new program, or a recent error message.

## My first script: Battery Health Report (Windows)

### What this script does:
Generates a detailed battery health report for Windows laptops.

### When IT support uses this:
- User says "My battery dies too fast"
- Checking if a battery needs replacement
- Documenting battery degradation over time

### How to run it:
1. Save the file as `battery-report.bat`
2. Right-click → "Run as Administrator"
3. A file called `battery-report.html` will appear in your user folder
4. Double-click that file to open the report in your browser

### What the report shows:
- Original battery capacity
- Current battery capacity
- Recent usage history
- Estimated battery life

## Active Directory Guide: How to reset a user's password

### Scenario:
A user calls IT support saying they forgot their password and can't log into their computer.

### Step-by-step fix (for IT support):

#### 1. Log into the Domain Controller
- Remote Desktop into the Active Directory server
- Or use a management workstation with RSAT tools installed

#### 2. Open Active Directory Users and Computers (ADUC)
- Click Start → Type `dsa.msc` → Press Enter
- Or find it under Windows Administrative Tools

#### 3. Find the user
- Navigate to the correct Organizational Unit (OU)
- Or right-click the domain → Find → Type the user's name

#### 4. Reset the password
- Right-click the user → Select "Reset Password"
- Enter a temporary password (example: `Greenhouse056`)
- Check "User must change password at next logon"
- Click OK

#### 5. Communicate with the user
- Give the user their temporary password
- Tell them: "You'll be prompted to create a new password when you log in"
- Remind them to use a strong password (8+ characters, mix of letters/numbers/symbols)

### Pro tips for IT support:
- Never ask for a user's password — reset it for them
- Document all password resets in your ticketing system
- If this happens frequently for the same user, check if they need training or if there's a larger issue

### Common issues & fixes:
| Issue | Solution |
|-------|----------|
| "Access denied" when resetting | Your admin account lacks permissions → escalate to senior admin |
| User still can't log in after reset | Check if account is locked or disabled |
| User is remote (not on VPN) | They need VPN access before the new password works |










