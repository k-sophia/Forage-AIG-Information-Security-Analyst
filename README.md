# Forage-AIG-Information-Security-Analyst
AIG virtual experience program on Forage.

As an Information Security Analyst, analyze security alerts and respond to a ransomware attack using Python and stakeholder management skills.

## Files Overview
**From Task 1:**
- **advisory_email.md** – Advisory email for the Log4j vulnerability.

**From Task 2:**
- **bruteforce.py** – Python script to recover the password for `enc.zip`.
- **enc.zip** – Encrypted file representing the ransomware-affected document.
- **ImportantFile.docx** – Recovered file retreived after successful bruteforce.
- **rockyou.txt** – Small sublist of common/weak passwords.

## Task 1 - Responding to a zero-day vulnerability

### Scenario

Review publications from the Cybersecurity & Infrastructure Security Agency (CISA) to draft an email to inform the relevant infrastructure teams at AIG of the seriousness of the vulnerability (Log4j) that has been reported. 

Analyze the “Infrastructure List” to determine which systems may be affected and which teams own them. Draft a concise advisory email to alert the owners and recommend appropriate mitigation steps.

### Provided Resources
The CISA has published the following two advisories:
1. [Mitigating Log4Shell and Other Log4j-Related Vulnerabilities](https://www.cisa.gov/news-events/cybersecurity-advisories/aa21-356a) - outlines a serious vulnerability in one of the world’s most popular logging software.
2. [CISA, FBI, NSA and International Partners Issue Advisory on Ransomware Trends from 2021](https://www.cisa.gov/news-events/news/cisa-fbi-nsa-and-international-partners-issue-advisory-ransomware-trends-2021) - explores how ransomware has been increasing and is becoming professionalized - a concern for a large company like AIG.

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
