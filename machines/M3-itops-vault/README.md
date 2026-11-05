# M3 — HashiCorp Vault

**Project:** Prabhal Urja Limited — Range 2  
**Machine:** `M3-itops-vault`  
**Scope:** Security documentation for the local lab; do not treat scenario text as independently verified exploitation.

Vault 1.15.4 was initialized, unsealed and active, with an in-memory storage backend and a listener on all IPv4 interfaces at port 8600. Four policies were visible.

- [Red Team — observations and scenario context](RED-TEAM.md)
- [Blue Team — local validation and remediation](BLUE-TEAM.md)

## Evidence presentation

Each documented command is followed immediately by its corresponding screenshot in the Red/Blue Markdown. Image files exist only as local assets needed for GitHub inline rendering; there is **no separate screenshot gallery**.

## Verification boundaries

- Red Team attack narratives from the original range are contextual and were not necessarily reproduced during the local validation.
- A running service or 200 response is not proof of authorization or security remediation.
- Original challenge scripts and scenario reports remain in the existing GitHub repository and are not overwritten by this ZIP.
- Sensitive values were omitted from reproduced commands, and selected private identifiers were masked in screenshots.
