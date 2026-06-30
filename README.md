# Network Intrusion Detection Comparison — Snort 3 vs Suricata 7 vs Zeek 6

## Overview
Independent research project benchmarking three NIDS platforms across a 
standardised attack corpus (port scanning, brute-force, banner-grabbing, 
payload delivery) to support evidence-based platform selection for 
small business environments.

## Key Findings
- Suricata delivered the strongest multi-threaded detection throughput
- Zeek produced the most metadata-rich logs for log-based threat hunting
- Findings mapped to NIST CSF categories to support tiered deployment 
  recommendations

## Methodology
Designed a virtualised test environment and executed a standardised 
attack corpus against all three platforms under identical conditions 
to ensure a fair, like-for-like comparison.

## Full Report
See [abdulrahman.rahaq_IDS_Comparison](./abdulrahman.rahaq_IDS_Comparison.pdf) and [Abdulrahman.Rahaq.NIDS_Poster](./Abdulrahman.Rahaq.NIDS_Poster.pdf) for the 
complete 10,000-word writeup, poster, including detailed methodology, results, 
and deployment recommendations.

## Tools & Skills
Snort 3 · Suricata 7 · Zeek 6 · Wireshark · VirtualBox · NIST CSF
