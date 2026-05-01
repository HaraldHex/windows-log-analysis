# Splunk Queries

## Failed Logins

index=security EventID=4625

---

## Successful Login After Failures

index=security (EventID=4625 OR EventID=4624)

---

## Suspicious Process

index=security EventID=4688 powershell.exe

---

## Privilege Escalation

index=security EventID=4672
