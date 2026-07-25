# DC

## **D**omain **C**ontroller
> [[MOC-term](MOC-term.md)]
---
## managers a computer network
- is a special server
- acts like the security guard
---
## Simple Analogy: A Building Pass Desk

Think of a Domain Controller like the **reception security desk** in a big office building:

1. **Checking Your ID (Authentication):** When you log in with your username and password, the DC checks if you are who you say you are.
    
2. **Giving Access (Authorization):** Once approved, the DC gives you access to the specific rooms (files, printers, shared folders) you are allowed to enter.
    

## 3 Main Jobs of a Domain Controller

- **User Verification:** It stores all usernames and passwords in a central database (called Active Directory on Windows).
    
- **Single Sign-On:** You only need to log in once on your computer, and the DC tells other servers in the network that you are allowed in.
    
- **Central Control:** System admins can change settings, push software updates, or block access for all computers at once through the DC.
    

> **Why is it useful?** Without a Domain Controller, an IT manager would have to manually create your user account and set permissions on **every single computer and printer** in the office. With a DC, they only do it once.
---

[uncompleted](uncompleted)
