# vsftpd 2.3.4 Backdoor — Exploitation & Remediation Report

A hands-on vulnerability assessment and exploitation exercise targeting the vsftpd 2.3.4 backdoor (CVE-2011-2523) on a Metasploitable 2 virtual machine, performed in a fully isolated, authorized lab environment.

## Summary
- **Target:** Metasploitable 2 (intentionally vulnerable VM, training use only)
- **Vulnerability:** vsftpd 2.3.4 backdoor — CVE-2011-2523
- **Tools used:** Nmap, Metasploit Framework, Suricata
- **Outcome:** Identified the vulnerable service via version fingerprinting, exploited the backdoor to obtain a root-level Meterpreter session, and reviewed network traffic to confirm detection artifacts.

## What's in this repo
The full report — methodology, exploitation steps, verification, network analysis, and remediation recommendations — is available here:
[`vsftp-2.3.4-report/`](./vsftp-2.3.4-report)

## Disclaimer
This exercise was performed entirely in an isolated, authorized lab environment using Metasploitable 2, a virtual machine intentionally built with known vulnerabilities for security training. No unauthorized systems were accessed.
