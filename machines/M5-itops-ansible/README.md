# M5 — Ansible AWX-style portal

**Project:** Prabhal Urja Limited — Range 2  
**Machine:** `M5-itops-ansible`  
**Scope:** Security documentation for the local lab; do not treat scenario text as independently verified exploitation.

Port 8080 was occupied by another lab service, and the M5 app initially failed to create /var/log/pul-ansible. After correcting the log directory permissions, the local app ran on port 8085 and /health returned 200.

- [Red Team — observations and scenario context](RED-TEAM.md)
- [Blue Team — local validation and remediation](BLUE-TEAM.md)

## Evidence presentation

Each documented command is followed immediately by its corresponding screenshot in the Red/Blue Markdown. Image files exist only as local assets needed for GitHub inline rendering; there is **no separate screenshot gallery**.

## Verification boundaries

- Red Team attack narratives from the original range are contextual and were not necessarily reproduced during the local validation.
- A running service or 200 response is not proof of authorization or security remediation.
- Original challenge scripts and scenario reports remain in the existing GitHub repository and are not overwritten by this ZIP.
- Sensitive values were omitted from reproduced commands, and selected private identifiers were masked in screenshots.
