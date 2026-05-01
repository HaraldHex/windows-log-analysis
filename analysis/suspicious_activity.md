# Suspicious Activity Analysis

## Observations

### 1. Multiple Failed Logins
- Repeated failed login attempts detected
- Followed by successful login

 Possible brute force attack

---

### 2. Privilege Escalation
- Admin privileges assigned after login

 Suspicious behavior

---

### 3. Suspicious Process Chain
winword.exe → powershell.exe → cmd.exe

 Common attack pattern

---

## Conclusion

The logs indicate:
- Potential brute force attack
- Possible privilege escalation
- Suspicious command execution

This behavior should trigger a SOC alert.
