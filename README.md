
# Cloud Identity Security Monitoring & Investigation

## Overview
This project demonstrates a SOC-style investigation of cloud identity sign-in activity using identity monitoring logs. The objective was to identify, analyze, and assess potentially suspicious authentication behavior and document findings using standard SOC methodology and the MITRE ATT&CK framework.

This project focuses on identity-based security analysis rather than infrastructure deployment.

---

## Environment
- Cloud identity platform (admin visibility)
- Identity sign-in logs
- No paid cloud resources required

---

## Investigation Scope
- Review sign-in activity and authentication outcomes
- Identify suspicious sign-in patterns
- Analyze context including IP address, location, and client application
- Classify severity and determine appropriate response

---

## Detection Summary
Multiple failed sign-in attempts were identified for a user account within a short time window. Investigation focused on authentication context and sign-in metadata. No indicators of successful compromise or malicious automation were observed.

---

## MITRE ATT&CK Mapping
- **Tactic:** Credential Access
- **Technique:** Brute Force – Password Guessing
- **Technique ID:** T1110

---

## Outcome
The activity was assessed as low severity and consistent with authentication errors rather than confirmed malicious behavior. The incident was documented and closed with continued monitoring recommended.

---

## Skills Demonstrated
- Cloud identity log analysis
- SOC-style investigation and triage
- Risk-based severity classification
- Incident documentation
- MITRE ATT&CK mapping
