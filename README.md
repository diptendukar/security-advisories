# Security Advisories

Public technical advisories for vulnerabilities discovered and reported by
Diptendu Mohan Kar ([@diptendukar](https://github.com/diptendukar)).

Each advisory documents the vulnerability, affected and fixed versions, root cause,
impact, and credited references. These pages serve as the public reference records
for the corresponding CVE identifiers.

| CVE | Package | Type | Severity |
|-----|---------|------|----------|
| [CVE-2026-106971](CVE-2026-106971.md) | rybakit/msgpack (msgpack.php) | Integer overflow leading to DoS (32-bit PHP) | High (CVSS 3.1 7.5)\* |
| [CVE-2026-106972](CVE-2026-106972.md) | rybakit/msgpack (msgpack.php) | Uncontrolled recursion leading to DoS | High (CVSS 3.1 7.5) |

\* Suggested score. The condition is 32-bit PHP only; final scoring is deferred to the assigning CNA.

## Disclosure

All issues were reported to the respective maintainers and fixed upstream before
publication. CVE identifiers were assigned by the MITRE CVE Assignment Team.
