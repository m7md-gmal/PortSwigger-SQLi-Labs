# PortSwigger-SQLi-Labs
"My solutions and payloads for PortSwigger Web Security Academy SQL Injection labs (Apprentice &amp; Practitioner levels)."
# SQL-Injection-Labs

A collection of hands-on SQL Injection labs completed on PortSwigger Web Security Academy using Burp Suite.

---

# Repository Structure

```text
SQL-Injection-Labs/
│
├── Authentication-Bypass/
│   ├── README.md
│   └── screenshots/
│
├── UNION-Based-SQLi/
│   ├── README.md
│   └── screenshots/
│
├── Blind-SQLi/
│   ├── README.md
│   └── screenshots/
│
├── Time-Based-SQLi/
│   ├── README.md
│   └── screenshots/
│
└── README.md
```

---

# Main README.md

```md
# SQL Injection Labs

This repository contains my hands-on practice and notes while learning SQL Injection through PortSwigger Web Security Academy.

## Topics Covered
- Authentication Bypass
- UNION-based SQL Injection
- Database Enumeration
- Blind SQL Injection
- Time-delay Attacks
- Out-of-band Data Exfiltration
- Oracle / MySQL / MSSQL exploitation

## Tools Used
- Burp Suite
- Browser DevTools
- PortSwigger Web Security Academy

## Goal
Improving practical skills in Web Application Security and Penetration Testing.
```

---

# Authentication-Bypass/README.md

```md
# Authentication Bypass SQL Injection

## Description
This lab demonstrates how SQL Injection vulnerabilities can be used to bypass authentication mechanisms.

## Skills Learned
- Identifying vulnerable login forms
- Understanding insecure SQL queries
- Authentication bypass techniques
- Payload testing using Burp Suite

## Tools Used
- Burp Suite
- Browser

## Notes
Practiced intercepting requests and modifying parameters to analyze authentication behavior.
```

---

# UNION-Based-SQLi/README.md

```md
# UNION-based SQL Injection

## Description
This section focuses on extracting data using UNION-based SQL Injection techniques.

## Skills Learned
- Determining column numbers
- Identifying compatible data types
- Extracting database information
- Enumerating tables and columns

## Tools Used
- Burp Suite
- Browser DevTools

## Notes
Learned how attackers can combine SQL queries to retrieve sensitive information from databases.
```

---

# Blind-SQLi/README.md

```md
# Blind SQL Injection

## Description
This lab demonstrates how attackers can extract information when database errors are not directly visible.

## Skills Learned
- Boolean-based Blind SQL Injection
- Conditional responses
- Inferring database information
- Testing hidden behaviors

## Tools Used
- Burp Suite
- Browser

## Notes
Practiced identifying application responses to determine whether SQL conditions are true or false.
```

---

# Time-Based-SQLi/README.md

```md
# Time-Based SQL Injection

## Description
This section focuses on detecting SQL Injection vulnerabilities through delayed server responses.

## Skills Learned
- Time-delay payloads
- Detecting asynchronous behavior
- Database response analysis
- Advanced Blind SQL Injection techniques

## Tools Used
- Burp Suite
- Browser

## Notes
Learned how response timing can reveal database behavior even without visible output.
```
# PortSwigger SQLi Labs

<img src="images/Screenshot 2026-05-24 054714.png" width="900">

## Topics Covered
- Authentication Bypass
- UNION-based SQL Injection
- Blind SQL Injection
- Time-delay Attacks
- Out-of-band Exploitation
## Screenshots

<img src="images/Screenshot 2026-05-24 054738.png" width="900">

<img src="images/Screenshot 2026-05-24 054825.png" width="900">

<img src="images/Screenshot 2026-05-24 054858.png" width="900">
