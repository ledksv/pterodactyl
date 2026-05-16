# Pterodactyl — HackTheBox

**Platform:** HackTheBox

**Status: Active — walkthrough locked pending machine retirement.**

## Enumeration

```
nmap -sV -sC -p- <TARGET_IP>

PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 9.6
80/tcp open  http    nginx 1.21.5
```

Port 80 redirects to `http://pterodactyl.htb/`. Added to `/etc/hosts` and proceeded with further enumeration.

## 🔒 Walkthrough Locked

This machine is still active on HackTheBox. Full writeup will be published on [l3dsec.com](https://l3dsec.com) upon retirement.

> ⚠️ For educational purposes only. Only test systems you own or have explicit written permission to test.
