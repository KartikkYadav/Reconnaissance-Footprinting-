# Reconnaissance & Footprinting

A practical collection of notes covering **passive and active reconnaissance, website discovery, WHOIS, DNS, IP intelligence, ASN and traceroute analysis, Google Dorking, GitHub reconnaissance, Shodan, OSINT, image metadata, email security, people-search resources, and reconnaissance checklists**.

This repository is focused on the information-gathering phase of ethical hacking and penetration testing, helping security testers understand a target's public-facing attack surface before deeper assessment begins.

---

## Overview

Reconnaissance and footprinting are foundational activities in security assessments. The goal is to build an accurate picture of the target's **domains, infrastructure, technologies, people-related exposure, public data, and externally visible services**.

The collection progresses from core reconnaissance concepts into specialized OSINT and infrastructure-discovery techniques.

### Learning Path

**Reconnaissance Fundamentals → Website Recon → Technology Identification → WHOIS/DNS → IP & ASN Intelligence → Google Dorking → GitHub Recon → Shodan → OSINT → Metadata → Email Security → People Search → Recon Checklist**

---

## Contents

### 01. Reconnaissance & Footprinting

**[Reconnaissance (Footprinting)](./01.Reconnaissance%20(Footprinting).md)**

Introduces the fundamentals of reconnaissance and footprinting.

Topics include:

- Passive reconnaissance
- Active reconnaissance
- WHOIS
- DNS enumeration
- Google Hacking
- Domain and IP discovery
- Email addresses
- Organizational information
- Network information
- Operating-system information
- Attack-surface mapping

The note also explains the types of information that can be collected before exploitation or vulnerability validation.

---

### 02. Spidering & Crawling

**[Spidering & Crawling](./02.Spidering_And_Crawling.md)**

Covers website reconnaissance and automated discovery of website structure.

Topics include:

- Website information gathering
- Sitemap discovery
- `robots.txt`
- `sitemap.xml`
- Spidering
- Crawling
- URL discovery
- Query-parameter discovery
- Metadata collection
- Historical website analysis
- Wayback Machine
- Burp Suite
- OWASP ZAP
- HTTrack
- Scrapy
- wget

---

### 03. Built With / Technology Identification

**[Built With](./03.Built_With.md)**

Focuses on identifying the technologies used by a website or web application.

Useful for discovering:

- Web frameworks
- CMS platforms
- JavaScript libraries
- Web servers
- Hosting technologies
- Technology fingerprints

This helps determine which technologies require deeper assessment during later testing phases.

---

### 04. WHOIS Lookup

**[WHOIS Lookup](./04.Who_Is_Lookup.md)**

Covers domain-registration reconnaissance.

Topics include:

- Registrant information
- Registrar
- Creation and expiration dates
- Name servers
- Domain status
- WHOIS records
- Command-line WHOIS
- Reverse WHOIS
- WHOIS history

The notes also reference public WHOIS and domain-research services.

---

### 05. Content Delivery Network (CDN)

**[Content Delivery Network](./05.Content_Delevery_Network_(CDN).md)**

Explains CDN architecture and why CDN identification is useful during reconnaissance.

Topics include:

- CDN fundamentals
- Edge servers
- Caching
- DNS-based routing
- TLS
- DDoS protection
- WAF concepts
- CDN headers
- DNS CNAME/A record analysis
- CDN identification tools

The notes reference services such as Cloudflare, AWS CloudFront, Akamai, and Fastly.

---

### 06. IP Address & Location Lookup

**[IP Address to Location Lookup](./06.IP_Address_To_Location_Lookup.md)**

Covers gathering intelligence associated with IP addresses and domains.

The notes include command-line DNS lookups and online IP-information resources useful for reconnaissance and infrastructure analysis.

---

### 07. ASN & Traceroute

**[ASN & Trace Route](./07.ASN_&_Trace_Route.md)**

Covers network-ownership and route analysis.

Key areas include:

- Autonomous System Numbers (ASN)
- Network ownership
- Routing information
- Traceroute
- Infrastructure mapping
- Network-path analysis

This can help connect domains and IP ranges to larger network infrastructure.

---

### 08. Google Dorks

**[Google Dorks](./08.Google_Dorks.md)**

Introduces advanced search-engine operators for finding publicly indexed information.

Topics include operators such as:

- `site:`
- `inurl:`
- `intitle:`
- `filetype:`
- `cache:`
- `related:`
- `inanchor:`

These techniques are useful for identifying publicly exposed pages, documents, directories, and other indexed information during authorized reconnaissance.

---

### 09. Google Dorking Cheat Sheet

**[Google Dorking Cheat Sheet](./09.Google_Dorking_Cheat_Sheet.md)**

Provides a quick-reference collection of Google search operators and reconnaissance-oriented search patterns.

Useful as a practical cheat sheet while performing passive reconnaissance.

---

### 10. Google Hacking Database Tools

**[Google Hacking Database Tools](./10.Google_Hacking_Database_Tools.md)**

Covers tools and resources related to Google Hacking Database (GHDB) techniques.

The section connects search-engine reconnaissance with broader OSINT workflows and publicly indexed data discovery.

---

### 11. GitHub Reconnaissance

**[GitHub Recon](./11.Github_Recon.md)**

Focuses on reconnaissance using public GitHub data.

Potential areas of interest include:

- Public repositories
- Source-code exposure
- Credentials and secrets
- API keys
- Configuration files
- Developer information
- Repository search
- GitHub-focused reconnaissance tools

This type of research should remain within authorized and responsible-disclosure boundaries.

---

### 12. Shodan Reconnaissance

**[Shodan Recon](./12.Shadon_Recon.md)**

Introduces Shodan as a source of internet-facing infrastructure intelligence.

Potential reconnaissance areas include:

- Public IP addresses
- Internet-facing services
- Service banners
- Technology fingerprints
- Exposed infrastructure
- Organization-level infrastructure discovery

---

### 13. Open Source Intelligence (OSINT)

**[Open Source Intelligence](./13.Open_Source_inteligence_(OSINT).md)**

Provides a broader introduction to OSINT-based reconnaissance.

The focus is on collecting and correlating information from publicly available sources to build a more complete understanding of a target's digital footprint.

---

### 14. Image Metadata

**[Image Metadata](./14.Image_Metadata.md)**

Covers image metadata as a reconnaissance source.

Potential information available in image metadata can include:

- File properties
- Camera information
- Software information
- Timestamps
- Geolocation data where present

Metadata should be handled carefully because it can contain personally sensitive information.

---

### 15. SPF, DKIM & DMARC

**[SPF, DKIM & DMARC](./15.%2CSPF_DKIM_DMARC.md)**

Covers email-domain authentication technologies and their reconnaissance value.

### Topics

- SPF
- DKIM
- DMARC
- DNS TXT records
- Email-domain security posture
- Mail infrastructure analysis

The notes include DNS-based lookup techniques for reviewing these records.

---

### 16. Email Spoofing

**[Email Spoofing](./16.Email_Spoofing.md)**

Explains email-spoofing concepts and how defenders can identify and reduce spoofing risk.

Topics include:

- Email headers
- Sender identity
- Reply-To behavior
- Received headers
- SPF
- DKIM
- DMARC
- Spoofing risks
- Header analysis
- Defensive controls

---

### 17. People Search & OSINT Tools

**[People Search & OSINT Tools](./17.People_Search_and_OSINT_Tools.md)**

Collects OSINT resources for investigating public information related to people, domains, infrastructure, and images.

The notes reference categories such as:

- People-search engines
- Reverse image search
- Regional search engines
- Satellite/aerial imagery
- Domain and hosting intelligence
- IP threat intelligence

---

### 18. Email Tracking & Protocols

**[Email Tracking & Protocols](./18.Email_Tracking_And_Protocols.md)**

Introduces email architecture and common email protocols.

Topics include:

- Email addresses
- Mail User Agents (MUA)
- Mail Transfer Agents (MTA)
- Mail Delivery Agents (MDA)
- SMTP
- POP3
- IMAP
- Email flow
- Secure vs unencrypted email services

---

### 19. IP / GPS Logger

**[GPS IP Logger](./19.Gps_Ip_Logger.md)**

Contains a PHP-based logging example that records request information such as:

- IP address
- User-Agent
- Referrer
- Timestamp
- Browser-provided GPS coordinates where permission is granted

The note also covers protecting log files and emphasizes privacy and controlled-use considerations.

---

### 20. Reconnaissance Checklist

**[Reconnaissance Checklist](./20.Reconnaissance_CheckList.md)**

A practical checklist covering a broad reconnaissance process.

Areas include:

- Website reconnaissance
- Spidering and crawling
- Technology identification
- WHOIS
- Domain-to-IP resolution
- IP geolocation
- Traceroute
- IP history
- Reverse IP
- Reverse mail-server lookup
- Reverse name-server lookup
- Port scanning
- Google Dorking
- GitHub reconnaissance
- LLM-assisted recon
- OSINT frameworks
- People-search resources
- IP logging
- Email tracking and spoofing
- Additional information-gathering sources

This is the main checklist to use as a repeatable reconnaissance workflow.

---

## Reconnaissance Categories

| Category | Focus |
|---|---|
| Domain Intelligence | WHOIS, DNS, domain history |
| Infrastructure | IPs, ASN, routing, CDN, exposed services |
| Website Recon | Crawling, spidering, technologies, sitemaps |
| Search Recon | Google Dorks, GHDB |
| Code & Repository Recon | GitHub repositories, secrets, configurations |
| Internet Exposure | Shodan and public infrastructure |
| OSINT | Public records and open-source information |
| Email Intelligence | SMTP, SPF, DKIM, DMARC, headers |
| People OSINT | Public profiles and search resources |
| Metadata | Image and document metadata |
| Tracking | IP and browser-request information |

---

## Passive vs Active Reconnaissance

| Type | Description | Examples |
|---|---|---|
| Passive | Gather information without directly interacting with the target | Search engines, WHOIS, public repositories, OSINT |
| Active | Interact directly with target infrastructure | DNS queries, traceroute, port scanning, service discovery |

### Passive Recon

**Lower interaction → Lower chance of detection → More dependent on public data**

### Active Recon

**More interaction → More direct information → Greater chance of detection**

The appropriate approach depends on the engagement scope and rules of engagement.

---

## Practical Reconnaissance Workflow

A structured workflow represented throughout the repository is:

### 1. Define Scope

Identify:

- Authorized domains
- IP ranges
- Applications
- Organizations
- Out-of-scope assets
- Testing restrictions

### 2. Passive Reconnaissance

Collect public information from:

**Search Engines → WHOIS → DNS → GitHub → Shodan → OSINT → Public Documents**

### 3. Infrastructure Mapping

Correlate:

**Domains → Subdomains → IPs → ASNs → CDNs → Hosting → Services**

### 4. Website Reconnaissance

Review:

**Sitemaps → robots.txt → Technologies → URLs → Parameters → Historical Content**

### 5. Email & Organizational Recon

Review authorized public information such as:

**Email Patterns → Mail Infrastructure → SPF/DKIM/DMARC → Public Roles → Organizational Information**

### 6. Active Reconnaissance

Where explicitly authorized:

**DNS Queries → Traceroute → Port Scanning → Service Identification**

### 7. Correlate Findings

Build an attack-surface map connecting infrastructure, technologies, public information, and externally visible services.

### 8. Prepare for Assessment

Use the resulting intelligence to prioritize subsequent **enumeration, vulnerability assessment, and penetration testing** activities.

---

## Recon Data to Record

A useful reconnaissance record should capture:

| Data Type | Examples |
|---|---|
| Domains | Primary domain, subdomains |
| IP Addresses | IPv4/IPv6, historical IPs |
| ASN | Network ownership |
| DNS | A, MX, NS, TXT and related records |
| CDN | CDN/provider indicators |
| Technologies | Frameworks, CMS, servers |
| URLs | Public and historical endpoints |
| Emails | Public addresses and patterns |
| Repositories | Public GitHub projects |
| Services | Exposed ports and banners |
| Metadata | Image/document properties |
| Notes | Relationships and observations |

---

## Toolset

The repository references a broad reconnaissance and OSINT toolset, including:

**WHOIS · Nslookup · Dig · Nmap · Traceroute · Shodan · theHarvester · Maltego · BuiltWith · Wappalyzer · Burp Suite · OWASP ZAP · HTTrack · Scrapy · Wayback Machine · GitHub search · GitLeaks · TruffleHog · VirusTotal · Netcraft**

---

## Reporting Checklist

For a professional reconnaissance report, record:

| Field | Purpose |
|---|---|
| Asset | Domain, IP, URL, repository, or service |
| Source | Where the information was obtained |
| Method | Passive or active technique |
| Observation | What was discovered |
| Evidence | Screenshot, output, record, or URL |
| Confidence | Confirmed / probable / unverified |
| Security Relevance | Why the information matters |
| Scope | Whether the asset is authorized/in scope |
| Next Step | Suggested follow-up assessment |

---

## Recommended Study Order

For a structured learning progression:

**Recon Fundamentals → Website Recon → WHOIS → DNS/IP Intelligence → ASN & Traceroute → CDN Identification → Google Dorking → GHDB → GitHub Recon → Shodan → OSINT → Metadata → Email Security → People Search → Recon Checklist**

After completing reconnaissance, continue into the repository's **Enumeration, Networking, Web Application Security, Active Directory, File Transfer, Privilege Escalation, and Tunneling** topics.

---

## Responsible Use

This repository is intended for:

**Cybersecurity Education · CTFs · Security Labs · Authorized Penetration Testing · OSINT Research**

Only collect or actively query information within the scope you are legally authorized to assess.

Respect privacy when handling:

- Personal information
- Email addresses
- GPS/location data
- Credentials or exposed secrets
- Private repositories
- Sensitive documents

Use responsible disclosure practices when security-sensitive information is discovered.

---

## Author

**Kartik Yadav**

Cybersecurity | Reconnaissance | OSINT | Penetration Testing

GitHub: [KartikkYadav](https://github.com/KartikkYadav)

---

⭐ **A practical reference for building reconnaissance and footprinting skills across domains, infrastructure, websites, public repositories, email systems, and OSINT sources.**
