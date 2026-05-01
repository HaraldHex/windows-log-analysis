# Detection Rules

## Rule 1: Brute Force Detection

IF:
- Multiple failed logins
- Followed by success

THEN:
- Trigger alert

---

## Rule 2: Suspicious Process Execution

IF:
- winword.exe spawns powershell.exe

THEN:
- High severity alert

---

## Rule 3: Privilege Escalation

IF:
- Admin privileges assigned after login

THEN:
- Investigate user activity
