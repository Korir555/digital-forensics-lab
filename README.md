# Digital Forensics Lab

Comprehensive Linux disk and memory forensics toolkit demonstrating acquisition, timeline reconstruction, artifact extraction, and chain of custody procedures aligned with Kenya Cybercrime Act and industry standards.

## Overview

Digital forensics lab environment for investigating compromised Linux systems. Covers full investigation lifecycle: evidence acquisition, volatile data capture, file system analysis, registry/log examination, and forensically sound reporting.

**Degree relevance:** Core component of BSc Cybersecurity & Digital Forensics (Open University of Kenya).

## Key Features

- **Disk Acquisition**: DD/Ddrescue with SHA256/MD5 validation, forensically sound copying
- **Memory Forensics**: Volatility framework for RAM analysis, process enumeration, network connections
- **Timeline Reconstruction**: Sleuthkit mactime for activity sequencing across file system, logs, artifacts
- **Artifact Extraction**: Browser history, email caches, temp files, application artifacts, deleted data recovery
- **Chain of Custody**: Automated logging, hash verification at each stage, evidence integrity validation
- **Reporting**: Forensically sound case reports with findings, timeline analysis, recommendations

## Key Components

- Disk/memory acquisition with cryptographic verification
- File system analysis and deleted file recovery
- Timeline reconstruction and activity sequencing
- Artifact extraction (browser, email, applications)
- Chain of custody logging and validation
- Forensic reporting templates

## Installation

```bash
git clone https://github.com/Korir555/digital-forensics-lab.git
cd digital-forensics-lab
pip install -r requirements.txt
```

## Lab Scenarios

- **Intrusion Detection**: Compromised web server investigation
- **Data Exfiltration**: Data theft timeline reconstruction
- **Malware Analysis**: Infected system artifact analysis

## Technologies

Python 3.9+, Volatility 3, Sleuthkit, Linux bash, cryptographic hashing

## Hiring Relevance

- End-to-end forensic investigation capability
- Incident response expertise
- Evidence handling and chain of custody procedures
- Kenya Cybercrime Act alignment
- Admissibility in legal proceedings
