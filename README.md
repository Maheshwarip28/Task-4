# 🔐 Task 4: Firewall Configuration on Windows

## 📌 Objective
To configure and test basic firewall rules on a Windows system using Windows Defender Firewall. Specifically, block and test inbound traffic on port 23 (Telnet).


## 🛠 Tools Used
- Windows 11
- Windows Defender Firewall (Advanced Settings)
- Telnet Client (enabled using DISM)
- Command Prompt (Administrator)
- Screenshots & Documentation (PDF)

---

## 📂 What I Did

1. **Enabled Telnet Client**  
   Used the command: dism /online /Enable-Feature /FeatureName:TelnetClient

2. **Created a New Inbound Rule**  
- Blocked **TCP port 23** using Windows Defender Firewall.
- Named the rule `Block Telnet Port 23`.

3. **Tested the Rule**  
- Ran: `telnet localhost 23`
- Got: `Could not open connection to the host, on port 23: Connect failed`

4. **Deleted the Rule**  
- Removed the firewall rule after testing.
- Re-tested and got the same result, confirming port 23 was closed (no service running).

5. **Documented Everything**  
- Compiled all steps and screenshots into a PDF file.

---

## 📸 Screenshots & Documentation
Find all screenshots and detailed steps in the attached `Task4_Firewall_Windows.pdf`.

---

## 📚 Key Concepts Learned
- Inbound and outbound firewall rules
- Port filtering with Windows Firewall
- Telnet client usage and behavior
- Importance of testing network rules

---

## ✅ Outcome
Successfully demonstrated firewall rule creation, testing, and removal on a Windows system.




