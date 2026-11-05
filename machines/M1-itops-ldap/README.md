# M1 — LDAP directory service

**Project:** Prabhal Urja Limited — Range 2  
**Machine:** `M1-itops-ldap`  
**Scope:** Security documentation for the local lab; do not treat scenario text as independently verified exploitation.

LDAP directory enumeration and setup-integrity checks. The base DN was present, but the expected populated directory entries were absent during verification. An administrator bind failed with LDAP result 49.

- [Red Team — observations and scenario context](RED-TEAM.md)
- [Blue Team — local validation and remediation](BLUE-TEAM.md)

## Evidence presentation

Each documented command is followed immediately by its corresponding screenshot in the Red/Blue Markdown. Image files exist only as local assets needed for GitHub inline rendering; there is **no separate screenshot gallery**.

## Verification boundaries

- Red Team attack narratives from the original range are contextual and were not necessarily reproduced during the local validation.
- A running service or 200 response is not proof of authorization or security remediation.
- Original challenge scripts and scenario reports remain in the existing GitHub repository and are not overwritten by this ZIP.
- Sensitive values were omitted from reproduced commands, and selected private identifiers were masked in screenshots.
