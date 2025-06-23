# HackPark - TryHackMe Walkthrough

This repository contains a personal walkthrough of the HackPark room on [TryHackMe](https://tryhackme.com/room/hackpark). It covers all steps from initial reconnaissance to post-exploitation and privilege escalation.

---

## 🖥️ Room Information

- **Room**: HackPark  
- **Platform**: TryHackMe  
- **Difficulty**: Easy to Medium  
- **Skills**: Web exploitation, brute-force attacks, reverse shells, Windows privilege escalation

---

## 🧩 Tasks Covered

### Task 1: Deploy the Machine
- Instructions to launch and access the vulnerable environment.

### Task 2: Hydra Brute-force Attack
- How to use Burp Suite to intercept credentials.
- Crafting a custom Hydra command to brute-force the login form.

### Task 3: Exploiting the Web Server
- Finding a vulnerable ASPX upload point.
- Triggering a reverse shell using a custom `.ascx` file.

### Task 4: Privilege Escalation (Metasploit)
- Creating a reverse shell with `msfvenom`.
- Hosting it with Python HTTP server.
- Gaining a Meterpreter session.
- Using winPEAS to detect privilege escalation vectors.

### Task 5: Manual Privilege Escalation
- Detecting scheduled tasks.
- Replacing executables to gain elevated access.

---

## 🧠 Notes

- The walkthrough includes errors and expressions that reflect my current level of English.
- The goal of this document is not only to show the solution but also my learning journey through each step.

---

## 📫 Contact

Feel free to connect or reach out if you have suggestions!

- LinkedIn: https://www.linkedin.com/in/fran-olivares/
- Email: franolivares386@gmail.com
