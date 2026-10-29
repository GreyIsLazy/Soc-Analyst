# Alert Analysis: [اسم التنبيه]

**Date:** [التاريخ]  
**Platform:** LetsDefend  
**Severity:** High / Medium / Low  
**Category:** Phishing / Malware / Suspicious Activity / etc.

---

## 1. Alert Overview
[جملتان تصفان التنبيه — ما الذي حدث وما الجهاز أو الحساب المتأثر]

Example: "A high-severity alert was triggered for a suspicious email 
received by a company employee. The email contained an attachment 
flagged by the antivirus engine."

---

## 2. Investigation Steps

### Step 1: [اسم الخطوة]
[ماذا فعلت وماذا وجدت]

### Step 2: [اسم الخطوة]
[ماذا فعلت وماذا وجدت]

### Step 3: [اسم الخطوة]
[ماذا فعلت وماذا وجدت]

---

## 3. Artifacts Found

| Type       | Value              | Notes                        |
|------------|--------------------|------------------------------|
| IP Address | 185.220.101.45     | Flagged on VirusTotal (32/90)|
| Domain     | malicious-site.com | Registered 2 days ago        |
| MD5 Hash   | a1b2c3d4e5f6...    | Matches known malware        |
| Email      | attacker@fake.com  | Spoofed legitimate domain    |

---

## 4. Verdict

**TRUE POSITIVE ✓**

Reason: [لماذا قررت أنه هجوم حقيقي أو إيجابية كاذبة — جملة أو جملتان]

---

## 5. Recommended Actions
- Block the IP address at the firewall level
- Quarantine the affected endpoint
- Notify the user and reset credentials
- Add the domain to the blocklist

---

## 6. Lessons Learned
[ماذا تعلمت من هذا التنبيه — جملة أو جملتان]

Example: "This case highlighted the importance of checking domain 
registration age as an early indicator of phishing campaigns."
