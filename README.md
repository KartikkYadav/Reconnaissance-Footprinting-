# 🔍 Reconnaissance and Footprinting

## 📌 Overview
**Reconnaissance and Footprinting** is the first and most critical phase of ethical hacking and penetration testing.  
In this phase, an attacker or security tester gathers as much information as possible about a target system, organization, or network **without actively exploiting it**.

The goal is to understand the target’s attack surface and identify potential entry points.

---

## 🎯 Objectives
- Identify target systems and network boundaries  
- Gather publicly available information  
- Understand technologies, services, and infrastructure in use  
- Reduce guesswork in later attack phases  

---

## 🧭 Types of Reconnaissance

### 1️⃣ Passive Reconnaissance
Information is collected **without directly interacting** with the target.

**Examples:**
- Search engines (Google Dorking)
- WHOIS lookup
- DNS records
- Social media profiling
- Public data leaks
- Job postings

**Advantages:**
- Stealthy  
- Low risk of detection  

---

### 2️⃣ Active Reconnaissance
Direct interaction with the target system to gather information.

**Examples:**
- Ping sweeps
- Port scanning
- Banner grabbing
- DNS zone transfers
- Network mapping

**Advantages:**
- More accurate information  
- Reveals live services and hosts  

⚠️ *Easily detectable and may trigger alerts.*

---

## 🛠️ Common Tools Used

### 🔎 Passive Recon Tools
- `whois`
- `nslookup`
- `theHarvester`
- `Maltego`
- `Google Dorks`
- `Shodan`

### ⚙️ Active Recon Tools
- `Nmap`
- `Netcat`
- `Traceroute`
- `Dig`
- `Nikto`

---

## 📂 Information Gathered
- IP addresses  
- Domain names & subdomains  
- Open ports & services  
- Operating systems  
- Web technologies  
- Employee names & email formats  
- Network topology  

---

## 🔐 Why Reconnaissance Matters
- Forms the **foundation** of all attacks  
- Saves time during exploitation  
- Helps avoid unnecessary noise  
- Improves success rate of penetration tests  

> “The more you know about the target, the fewer mistakes you make.”

---

## ⚖️ Legal & Ethical Considerations
- Perform reconnaissance **only with proper authorization**
- Unauthorized scanning may be illegal
- Follow responsible disclosure practices
- Always stay within the defined scope

---

## 📘 Learning Outcomes
After completing this module, you will be able to:
- Differentiate between passive and active reconnaissance  
- Perform footprinting using real-world tools  
- Analyze gathered information for attack planning  
- Understand how attackers profile targets  

---

## 🚀 Next Phase
➡️ **Scanning & Enumeration**

---

## 📚 References
- OWASP Testing Guide  
- NIST SP 800-115  
- CEH v12 Curriculum  
