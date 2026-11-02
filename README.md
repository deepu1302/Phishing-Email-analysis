# Phishing Email Analysis and Investigation

## Project Overview
This project demonstrates a basic SOC L1 phishing email
investigation using a fictional email sample in a controlled
cybersecurity training environment.

## Objectives
- Identify suspicious email characteristics.
- Inspect email headers.
- Understand SPF, DKIM and DMARC.
- Extract URLs, domains and IP addresses.
- Practise threat-intelligence lookups.
- Prepare an incident investigation report.

## Tools Used
- Kali Linux
- VirusTotal
- Email header analysis
- Linux command-line tools

## Investigation Workflow
1. Created a fictional phishing email.
2. Examined sender, Reply-To and Return-Path.
3. Reviewed simulated email authentication results.
4. Extracted URLs, domains and IP addresses.
5. Practised a VirusTotal URL lookup.
6. Documented findings and recommendations.

## Key Findings
- Sender and Reply-To domains differed.
- Urgency-based language was used.
- SPF and DMARC failures were simulated.
- A URL and IP address were extracted for practice.

## Important Disclaimer
This is a controlled educational exercise.
The email and authentication results are fictional.
The sample uses reserved example indicators and does
not demonstrate a real phishing attack or compromise.

## Project Structure
- samples/ - Sample email
- evidence/ - Header review and extracted indicators
- reports/ - Incident investigation report
- scripts/ - Analysis scripts

## Learning Outcomes
- Email header investigation
- Phishing indicator identification
- Basic IoC extraction
- Threat-intelligence lookup
- SOC L1 incident documentation
