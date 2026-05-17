# Pterodactyl — HackTheBox

**Platform:** HackTheBox | **OS:** Linux

Full walkthrough published on [l3dsec.com](https://l3dsec.com).

## Summary

Pterodactyl Panel path traversal (CVE-2025-49132) leaks the Laravel app key and database credentials unauthenticated. Cracking the extracted hash gives SSH access. Privilege escalation chains PAM environment poisoning via CVE-2025-6018 (polkit bypass) with an XFS resize race condition via CVE-2025-6019 to land a SUID root shell.

**Tags:** CVE-2025-49132 · Path Traversal · Config Disclosure · CVE-2025-6018 · PAM Poisoning · Polkit Bypass · CVE-2025-6019 · XFS Race Condition

> ⚠️ For educational purposes only. Only test systems you own or have explicit written permission to test.
