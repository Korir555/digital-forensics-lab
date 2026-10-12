# Digital Forensics Lab

Linux disk and memory forensics lab with Volatility and Sleuthkit, demonstrating evidence collection, chain of custody, and forensic artifact analysis aligned to Kenya Cybercrime Act.

## Features

- Disk Forensics: File recovery, filesystem analysis, artifact extraction
- Memory Analysis: Process analysis, network connections, malware detection
- Timeline Reconstruction: Mactime-based activity sequencing
- Chain of Custody: Evidence integrity and tamper-proof logging
- Legal Reporting: Cyber crime act-compliant documentation

## Quick Start

```bash
git clone https://github.com/Korir555/digital-forensics-lab.git
cd digital-forensics-lab
./acquire_disk_image.sh /dev/sdX disk_image.raw
python forensic_analysis.py disk_image.raw
```

## Analysis Modules

- Disk Analysis: Deleted file recovery, filesystem timeline
- Memory Forensics: Process enumeration, network I/O, malware detection
- Log Analysis: Bash history, syslog, auth logs
- Cross-Correlation: Disk <-> Memory evidence linking

## Technologies

Volatility 3.0+ | Sleuthkit 4.0+ | autopsy | strings, hexdump | Python 3.9+

## Hiring Relevance

- Incident response and forensics
- Law enforcement investigations
- Evidence preservation and analysis
- Kenya Cybercrime Act compliance

## Documentation

Full forensic procedures and case study: Case Study

## License

MIT License
