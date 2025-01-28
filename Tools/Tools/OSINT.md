## Introduction
Open-Source Intelligence (OSINT) tools are used for gathering publicly available information from various sources on the internet. These tools are crucial for cybersecurity professionals, investigators, and security analysts to gather intelligence without directly engaging with the target.

## 1. What's My Name

**Description**:  
What’s My Name is an OSINT tool that helps to find and discover online accounts and profiles associated with a particular name or username. It gathers information from various public sources and social media platforms. It provides a very flexible report of the results. The results table can be sorted by column, and you can export the results as CSV or PDF for reporting.

**Common Usage**:
- Search for a name or username:
  - Example: Input your name or username to find linked accounts.
  - Tool will search multiple platforms such as social media, forums, and other websites to identify accounts with the given name or username.

**Website**: [What’s My Name](https://www.whatsmyname.app) 

---

## 2. Names Directory

**Description**:  
Names Directory is a tool that gathers information from social media and public databases. It allows you to search for a person’s name and find out additional details such as location, phone number, and email address.

**Common Usage**:
- Input a person's name to find their contact information and associated profiles from different databases.
- Useful for people search and recon work.

**Website**: [Names Directory](https://www.names-directory.com) 

---

## 3. SpiderFoot

**Description**:  
SpiderFoot is an automated OSINT collection tool that is usually included with Kali. It is used to gather intelligence from public sources like WHOIS records, DNS information, social media, IP address data, and more. SpiderFoot allows you to analyze a target by pulling data from over 1000 different data sources.

**Common Usage**:
Spiderfoot seeds its scan with one of the following:
- Domain Name
- IP Addresses
- Subnet Addresses
- Email Addresses
- Phone Numbers
- Personal Names
     
  ```bash
  python3 spiderfoot.py -s example.com
SpiderFoot can also be used to automate reconnaissance tasks in penetration testing. It offers the option of choosing scans based on use case, required data and by module. The use cases are:
- All: - Get every bit of information on a target.
- Footprint - Understand the target's network perimeter, associated identities and other information yielded from the web.
- Investigate - For targets suspected of malicious behavior. Sources that report on malicious sites will be returned.
- Passive - If it is paramount that the target is unaware of being scanned.
Website: SpiderFoot (official website)

## 4. Recon-ng
**Description**:
Recon-ng is a modular-based open-source web reconnaissance framework written in Python. It automates tasks like gathering domain information, performing footprinting, and other OSINT activities.

**Common Usage**:
Reon-ng performs a wide range of reconnaissance activities in different settings. Some modules come with kali while others are available for download on the marketplace.



