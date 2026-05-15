# Pterodactyl — HackTheBox

**Platform:** HackTheBox

## Enumeration

```
nmap -sV -sC -p- <TARGET_IP>

PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 9.6
80/tcp open  http    nginx 1.21.5
```

Port 80 redirects to `http://pterodactyl.htb/`. Added to `/etc/hosts` and enumerated further.

## 🔒 Walkthrough Locked

This machine is still active on HackTheBox. The full writeup will be published upon retirement.

Full walkthrough available at [l3dsec.vercel.app](https://l3dsec.vercel.app) upon retirement.