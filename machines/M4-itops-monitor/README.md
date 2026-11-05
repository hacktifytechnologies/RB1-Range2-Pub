# M4 — Monitoring portal

**Project:** Prabhal Urja Limited — Range 2  
**Machine:** `M4-itops-monitor`  
**Scope:** Security documentation for the local lab; do not treat scenario text as independently verified exploitation.

Monitoring service setup initially failed because scripts had CRLF line endings. The Flask app subsequently ran locally on 127.0.0.1:9090. The root route redirected and /metrics returned 200.

- [Red Team — observations and scenario context](RED-TEAM.md)
- [Blue Team — local validation and remediation](BLUE-TEAM.md)

## Evidence presentation

Each documented command is followed immediately by its corresponding screenshot in the Red/Blue Markdown. Image files exist only as local assets needed for GitHub inline rendering; there is **no separate screenshot gallery**.

## Verification boundaries

- Red Team attack narratives from the original range are contextual and were not necessarily reproduced during the local validation.
- A running service or 200 response is not proof of authorization or security remediation.
- Original challenge scripts and scenario reports remain in the existing GitHub repository and are not overwritten by this ZIP.
- Sensitive values were omitted from reproduced commands, and selected private identifiers were masked in screenshots.
