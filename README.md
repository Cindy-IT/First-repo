# My IT Support Portfolio

Hi, I am Cindy. This is where I'll share my IT support projects.

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











