# SOC Home Lab – SIEM Detection & Attack Simulation

## Overview
This project demonstrates a Security Operations Center (SOC) home lab built on Proxmox to simulate real-world attack scenarios and analyze detections using a SIEM. The lab focuses on defensive security skills including log analysis, alert triage, and incident response.

All activities were conducted in a fully isolated virtual network for educational purposes.

## Lab Architecture
- **Hypervisor:** Proxmox VE
- **SIEM:** Wazuh
- **Attacker:** Kali Linux
- **Targets:** Windows 10
- **Network:** Isolated internal bridge (vmbr1, no external access)

## Objectives
- Simulate common attack techniques used in real environments
- Analyze security alerts and logs in a SIEM
- Understand attacker behavior and detection logic
- Document findings and recommend mitigations

## Attack Scenarios
1. Network Reconnaissance
2. Authentication Abuse (Brute Force / Password Spray)
3. Privilege Escalation Simulation
4. Malware Behavior Simulation (Non-destructive)

Each scenario includes:
- Attack objective
- Tools used
- Observed SIEM alerts
- Relevant logs
- Mitigation recommendations

## Skills Demonstrated
- SIEM log analysis and alert investigation
- Windows security event analysis
- Network segmentation and isolation
- Incident detection and response thinking
- Clear technical documentation

## Disclaimer
All attacks were performed in a controlled, isolated lab environment for defensive security learning only.
