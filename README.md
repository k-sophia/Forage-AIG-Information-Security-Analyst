# Forage-AIG-Information-Security-Analyst
AIG virtual experience program on Forage.

As an Information Security Analyst, analyze security alerts and respond to a ransomware attack using Python and stakeholder management skills.

## Task 1 - Responding to a zero-day vulnerability

## Task 2 - Bypassing ransomware

### Scenario
An attacker exploited a vulnerability (Log4j) and attempted to load a ransomware virus. The Incident Detection & Response team prevented the infection from completing and only a single ZIP file was encrypted. The CISO decided not to pay the ransom because there is no guarantee that the decryption key will be provided or that the attackers won’t strike again.

Write a bruteforcer to break into the ransomware-encrypted files, to avoid paying ransom.

### Tools
- Python 3
- zipfile module
- Rockyou.txt sublist

### How to Run
```Bash
python3 bruteforce.py
```

### Expected Output
```Bash
[+] Beginning bruteforce 
[+] Password found: b'SPONGEBOB'
```
