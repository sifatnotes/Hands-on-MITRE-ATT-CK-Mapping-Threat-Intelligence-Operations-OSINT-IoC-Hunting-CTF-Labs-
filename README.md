# Hands-on-MITRE-ATT-CK-Mapping-Threat-Intelligence-Operations-OSINT-IoC-Hunting-CTF-Labs-
A practical collection of cybersecurity CTF labs covering adversary behavior mapping, threat intelligence operations, OSINT footprinting, and proactive threat hunting.
# MITRE ATT&CK Mapping, Threat Intelligence Operations, OSINT & IoC Hunting CTF Labs

Welcome to the **MITRE ATT&CK Mapping, Threat Intelligence Operations, OSINT & IoC Hunting CTF Lab Collection**. This repository serves as an organized, searchable catalog of practical cybersecurity labs hosted on Learn SecByte.

This collection focuses on mapping adversary Tactics, Techniques, and Procedures (TTPs), operationalizing Cyber Threat Intelligence (CTI), executing open-source reconnaissance, and proactive threat hunting—spanning **MITRE ATT&CK Framework Mapping & Adversary TTPs (ATT&CK taxonomy fundamentals, initial access entry paths, execution technique detection)**, **Cyber Threat Intelligence (CTI) Operations & Automation (Automated intelligence platforms, signals-to-decisions workflows, executive intelligence reporting, CTI analyst bootcamp)**, and **Threat Actor Profiling, IoC Hunting & OSINT Reconnaissance (Clues to campaign attribution, Indicators of Compromise IoC incident hunting, OSINT footprint tracing)**.

---

## Lab Collection Index

### 1. MITRE ATT&CK Framework Mapping & Adversary TTPs
* **MITRE ATT&CK Fundamentals: Mapping the Adversary**  
  *Lab Link:* [https://learn.secbyte.org/ctf/mitre-attck-fundamentals-mapping-the-adversary](https://learn.secbyte.org/ctf/mitre-attck-fundamentals-mapping-the-adversary)  
  *Focus:* Understanding the structure of the MITRE ATT&CK framework, navigating matrices (Enterprise, Cloud, Mobile), and mapping raw adversary behavior to standardized Tactics, Techniques, and Procedures (TTPs).

* **MITRE ATT&CK: Mapping from Alerts to Adversary TTPs**  
  *Lab Link:* [https://learn.secbyte.org/ctf/mitre-attck-mapping-from-alerts-to-adversary-ttps](https://learn.secbyte.org/ctf/mitre-attck-mapping-from-alerts-to-adversary-ttps)  
  *Focus:* Translating SIEM/EDR telemetry and security alerts into ATT&CK Navigator layer JSON files, identifying gap coverage, and modeling threat actor attack chains.

* **Initial Access Techniques: Entry Paths Under Pressure**  
  *Lab Link:* [https://learn.secbyte.org/ctf/initial-access-techniques-entry-paths-under-pressure](https://learn.secbyte.org/ctf/initial-access-techniques-entry-paths-under-pressure)  
  *Focus:* Triaging adversary initial access vectors (T1190 Exploit Public-Facing Application, T1566 Phishing, T1078 Valid Accounts), analyzing perimeter entry telemetry, and hardening perimeter defenses.

<Image src="image_agent_tag_10788555229787490619" alt="MITRE ATT&CK Matrix Navigator showing various techniques across tactics" caption="MITRE ATT&CK Adversary Matrix Navigator Taxonomy" />

---

* **Execution Techniques: From Theory to Detection**  
  *Lab Link:* [https://learn.secbyte.org/ctf/execution-techniques-from-theory-to-detection](https://learn.secbyte.org/ctf/execution-techniques-from-theory-to-detection)  
  *Focus:* Analyzing command-line execution primitives (T1059 Command and Scripting Interpreter, T1204 User Execution), detecting PowerShell/WMI malicious invocations, and writing SIGMA detection rules.

### 2. Cyber Threat Intelligence (CTI) Operations & Platform Automation
* **Threat Intelligence Operations: From Signals to Decisions**  
  *Lab Link:* [https://learn.secbyte.org/ctf/threat-intelligence-operations-from-signals-to-decisions](https://learn.secbyte.org/ctf/threat-intelligence-operations-from-signals-to-decisions)  
  *Focus:* Executing the CTI lifecycle—from direction and collection to processing, analysis, dissemination, and converting raw security telemetry into actionable tactical/strategic intelligence.

<Image src="image_agent_tag_10788555229787491138" alt="Incident Response and Intelligence Lifecycle Diagram" caption="Threat Intelligence & Incident Response Lifecycle Model" />

---

* **Intelligence Automation: Signals to Decisions**  
  *Lab Link:* [https://learn.secbyte.org/ctf/intelligence-automation-signals-to-decisions](https://learn.secbyte.org/ctf/intelligence-automation-signals-to-decisions)  
  *Focus:* Automating intelligence ingestion feeds (STIX/TAXII standards), parsing unstructured threat advisories, scoring indicator confidence levels, and triggering SOAR playbook integrations.

* **Intelligence Platform Operations**  
  *Lab Link:* [https://learn.secbyte.org/ctf/intelligence-platform-operations](https://learn.secbyte.org/ctf/intelligence-platform-operations)  
  *Focus:* Managing Threat Intelligence Platforms (TIP) such as OpenCTI or MISP, correlating indicators across campaign clusters, managing CTI feeds, and enriching internal telemetry.

* **Malware Intelligence Analyst Bootcamp**  
  *Lab Link:* [https://learn.secbyte.org/ctf/malware-intelligence-analyst-bootcamp](https://learn.secbyte.org/ctf/malware-intelligence-analyst-bootcamp)  
  *Focus:* Conducting static and dynamic malware CTI analysis, extracting YARA rule matches, extracting C2 configuration blocks, and mapping malware capabilities to CTI frameworks.

* **Intelligence Reporting Essentials**  
  *Lab Link:* [https://learn.secbyte.org/ctf/intelligence-reporting-essentials](https://learn.secbyte.org/ctf/intelligence-reporting-essentials)  
  *Focus:* Authoring high-impact tactical, operational, and strategic CTI reports, applying Diamond Model & Cyber Kill Chain frameworks, and delivering actionable executive intelligence summaries.

### 3. Threat Actor Profiling, IoC Hunting & OSINT Reconnaissance
* **Threat Actor Profiling: From Clues to Attribution**  
  *Lab Link:* [https://learn.secbyte.org/ctf/threat-actor-profiling-from-clues-to-attribution](https://learn.secbyte.org/ctf/threat-actor-profiling-from-clues-to-attribution)  
  *Focus:* Profiling Advanced Persistent Threat (APT) groups, analyzing infrastructure overlap, evaluating operational security (OpSec) errors, and establishing high-confidence adversary attribution.

* **Indicators of Compromise: Incident Hunt Lab**  
  *Lab Link:* [https://learn.secbyte.org/ctf/indicators-of-compromise-incident-hunt-lab](https://learn.secbyte.org/ctf/indicators-of-compromise-incident-hunt-lab)  
  *Focus:* Proactively hunting for atomic, computed, and behavioral Indicators of Compromise (IoCs)—hashes, IP addresses, domains, registry modifications—across enterprise endpoints and SIEM logs.

* **Trace the Footprints: OSINT Investigation Lab**  
  *Lab Link:* [https://learn.secbyte.org/ctf/trace-the-footprints-osint-investigation-lab](https://learn.secbyte.org/ctf/trace-the-footprints-osint-investigation-lab)  
  *Focus:* Executing Open Source Intelligence (OSINT) investigations using Maltego, Shodan, VirusTotal, and WHOIS records to trace adversary infrastructure footprints and public exposures.

---

## Learning Path

### Path A: ATT&CK Mapping & Threat Hunting Specialist
1. **ATT&CK Fundamentals & Alerts:** Start with [MITRE ATT&CK Fundamentals](https://learn.secbyte.org/ctf/mitre-attck-fundamentals-mapping-the-adversary) and [Mapping from Alerts to TTPs](https://learn.secbyte.org/ctf/mitre-attck-mapping-from-alerts-to-adversary-ttps).
2. **Vectors & IoC Hunting:** Analyze TTPs in [Initial Access Techniques](https://learn.secbyte.org/ctf/initial-access-techniques-entry-paths-under-pressure), [Execution Techniques](https://learn.secbyte.org/ctf/execution-techniques-from-theory-to-detection), and [Indicators of Compromise Hunt](https://learn.secbyte.org/ctf/indicators-of-compromise-incident-hunt-lab).

### Path B: CTI Operations & Automation Engineer
1. **Lifecycle & Platforms:** Master threat intel in [Threat Intelligence Operations](https://learn.secbyte.org/ctf/threat-intelligence-operations-from-signals-to-decisions) and [Intelligence Platform Operations](https://learn.secbyte.org/ctf/intelligence-platform-operations).
2. **Automation & Reporting:** Automate CTI workflows via [Intelligence Automation](https://learn.secbyte.org/ctf/intelligence-automation-signals-to-decisions), [Malware Intelligence Analyst Bootcamp](https://learn.secbyte.org/ctf/malware-intelligence-analyst-bootcamp), and [Intelligence Reporting Essentials](https://learn.secbyte.org/ctf/intelligence-reporting-essentials).

### Path C: OSINT & Threat Actor Attribution Investigator
1. **Adversary Profiling:** Track APTs using [Threat Actor Profiling: From Clues to Attribution](https://learn.secbyte.org/ctf/threat-actor-profiling-from-clues-to-attribution).
2. **OSINT Infrastructure Tracing:** Conduct external recon in [Trace the Footprints: OSINT Investigation Lab](https://learn.secbyte.org/ctf/trace-the-footprints-osint-investigation-lab).

---

## How to Use the Labs

1. Select a practice scenario from the **Lab Collection Index**.
2. Click the direct link to launch the exercise environment hosted on Learn SecByte.
3. Review scenario directives, SIEM telemetry, STIX/TAXII JSON feeds, malware sample hashes, or OSINT target domains.
4. Construct ATT&CK Navigator JSON layers, configure automated CTI feeds in MISP/OpenCTI, write YARA/SIGMA detection rules, track IoCs across endpoint logs, or conduct Maltego/Shodan footprinting to capture flags.

---

## Target Audience

* **Cyber Threat Intelligence (CTI) Analysts:** Operationalize threat feeds, profile APT threat actors, manage TIP platforms (MISP/OpenCTI), and author executive CTI reports.
* **Threat Hunters & SOC Analysts:** Map security alerts to the MITRE ATT&CK framework, search for IoCs across enterprise logs, and hunt for execution/initial access TTPs.
* **Malware & OSINT Researchers:** Perform static malware CTI extraction, trace infrastructure footprints via Shodan/VirusTotal, and perform campaign attribution.
* **Cybersecurity Students:** Acquire practical hands-on experience in threat intelligence lifecycle management, ATT&CK mapping, and open-source intelligence gathering.

---

## Disclaimer

All lab links provided in this repository direct to official training environments hosted on Learn SecByte. All materials and exercises are provided strictly for educational purposes, defensive skill building, and authorized security research. Unauthorized scanning, OSINT scraping, or infrastructure probing against external production systems is strictly prohibited.
