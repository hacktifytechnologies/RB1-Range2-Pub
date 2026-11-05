# Prabhal Urja Limited — Range 2 documentation index

**Existing repository:** https://github.com/hacktifytechnologies/RB1-Range2-Pub  
**Machine scope:** M1 LDAP · M2 Gitea · M3 Vault · M4 Monitor · M5 AWX-style portal

This package is **documentation-only** and is designed to merge into the existing public GitHub repository. It does **not** replace the source scripts, site templates or original red/blue challenge reports.

## How screenshots are displayed

Every documented terminal command is directly followed by an inline Markdown image. Each screenshot file under `machines/<machine>/evidence/screenshots/` is an **asset** GitHub needs to render the picture; there is no screenshot gallery. Markdown files without commands (the index READMEs) intentionally contain no screenshots.

## Report links

| Machine | Overview | Red Team | Blue Team |
|---|---|---|---|
| `M1-itops-ldap` | [Overview](machines/M1-itops-ldap/README.md) | [Red Team](machines/M1-itops-ldap/RED-TEAM.md) | [Blue Team](machines/M1-itops-ldap/BLUE-TEAM.md) |
| `M2-itops-git` | [Overview](machines/M2-itops-git/README.md) | [Red Team](machines/M2-itops-git/RED-TEAM.md) | [Blue Team](machines/M2-itops-git/BLUE-TEAM.md) |
| `M3-itops-vault` | [Overview](machines/M3-itops-vault/README.md) | [Red Team](machines/M3-itops-vault/RED-TEAM.md) | [Blue Team](machines/M3-itops-vault/BLUE-TEAM.md) |
| `M4-itops-monitor` | [Overview](machines/M4-itops-monitor/README.md) | [Red Team](machines/M4-itops-monitor/RED-TEAM.md) | [Blue Team](machines/M4-itops-monitor/BLUE-TEAM.md) |
| `M5-itops-ansible` | [Overview](machines/M5-itops-ansible/README.md) | [Red Team](machines/M5-itops-ansible/RED-TEAM.md) | [Blue Team](machines/M5-itops-ansible/BLUE-TEAM.md) |

## Verified boundaries

- **M1:** LDAP base entry present and bind failure recorded; intended directory population not verified.
- **M2:** Historical Git configuration exposure was investigated; credentials were not republished.
- **M3:** Vault active/unsealed using in-memory storage; remediation not confirmed.
- **M4:** Loopback Flask endpoint `/metrics` responded 200; monitoring authentication issue not shown remediated.
- **M5:** Local Flask health endpoint responded 200 on port 8085; full systemd service and security controls not validated.

**Publication precautions:** No raw token IDs, root tokens, passwords, private keys or credential-bearing `solve_red.md` files should be copied into new public documentation. Review all screenshots before publication, especially screenshots already present in the repository.
