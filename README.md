<div align="center">
  <img src="./assets/banner.svg" alt="Parse, pentester in progress, red teamer by design" width="100%">
</div>

<div align="center">

![status](https://img.shields.io/badge/status-learning_in_public-39ff88?style=flat-square&labelColor=0a0c0f)
![focus](https://img.shields.io/badge/focus-red_teaming-ff3d3d?style=flat-square&labelColor=0a0c0f)
![base](https://img.shields.io/badge/base-bengaluru-8b95a3?style=flat-square&labelColor=0a0c0f)
![grad](https://img.shields.io/badge/graduating-april_2027-8b95a3?style=flat-square&labelColor=0a0c0f)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-profile-ff3d3d?style=flat-square&logo=tryhackme&logoColor=white&labelColor=0a0c0f)](https://tryhackme.com/p/parodyparse)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-connect-8b95a3?style=flat-square&logo=linkedin&logoColor=white&labelColor=0a0c0f)](https://www.linkedin.com/in/YOUR_LINKEDIN_HANDLE)

</div>

<br>

<img src="./assets/h-briefing.svg" width="100%" alt="01 Briefing">

I run Windows and Active Directory infrastructure for a living and spend my nights learning how to break it. The plan is simple: land a junior pentest role by graduation in April 2027, then grow into red team work. Everything I learn gets written up in public, minus flags and answer keys.

```text
name      : Parse
base      : Bengaluru, India
day job   : Residential Engineer, on-site at a large organization (since April 2024)
studying  : BCA, evening classes
mission   : junior pentester by graduation, red teamer after
method    : labs, CTFs, breaking things on purpose, then writing it down
```

<div align="center">
  <img src="./assets/terminal.svg" alt="Terminal session: who I am, the mission, the stack and current progress" width="100%">
</div>

<br>

<img src="./assets/h-telemetry.svg" width="100%" alt="02 Telemetry">

<div align="center">
  <img src="./assets/stats.svg" alt="440 systems migrated into Active Directory, 16 plus TryHackMe rooms, 10 Bandit levels, 98 percent homelab uptime" width="100%">
</div>

<br>

<img src="./assets/h-mission.svg" width="100%" alt="03 Mission map">

<div align="center">
  <img src="./assets/path.svg" alt="Mission map from Pre Security to red team" width="100%">
</div>

| Phase | What is on the board |
|:--|:--|
| **Now** | TryHackMe Cyber Security 101 (Exploitation Basics), rolling out Wazuh at work, a write-up for every room |
| **Next** | First solo CTF run, finish Cyber Security 101, Junior Penetration Tester path, wire Wazuh into my IT assistant, turn the homelab into a cyber range, attend a null / OWASP Bangalore meetup |
| **Later** | eJPT, then PNPT, then OSCP, then red team roles |

<br>

<img src="./assets/h-field.svg" width="100%" alt="04 Field experience">

**Residential Engineer** | on-site at a large organization | April 2024 to now

- Migrated 440 local-account Windows systems into Active Directory with USMT, keeping each user's local profile alongside the new domain profile.
- Built the supporting stack on ESXi: Active Directory, print management, GLPI issue tracking, phpIPAM, MECM, remote desktop services and Zabbix monitoring, all LAN only.
- Started rolling out Wazuh for endpoint security monitoring.
- Built and run a local AI assistant (Qwen 3.5 35B with RAG and LibreChat) wired into GLPI, AD and MECM to flag issues and help fix them.
- Wrote a serial-to-database bridge for a lab analyzer, moving its COM port output into a LAN database over ODBC.

Why this matters for red teaming: knowing how AD, profiles, monitoring and ticketing work from the admin side shows me what defenders see and what attackers abuse.

<br>

<img src="./assets/h-builds.svg" width="100%" alt="05 Builds">

<table>
<tr>
<td width="50%" valign="top">

**Sentinel** `proposal done, build next`

Internal network vulnerability and asset management platform, built with a team. Finds what is on the network, ranks what matters, validates it safely, and hands the result to a human instead of replacing one.

</td>
<td width="50%" valign="top">

**Beat the AI** `college open day`

Real-time emotion detection and music recommender. A Pi Zero W streams video to an OpenCV DNN pipeline running a FERPlus ONNX model, and visitors compete on a scoreboard to fool it.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**Homelab** `98% uptime over the first 4 weeks`

Nextcloud, Jellyfin, Immich and monitoring in Docker, behind SELinux, hardened SSH and UFW. Runs on its own hotspot, LAN only. Becomes a cyber range once the basics are solid.

</td>
<td width="50%" valign="top">

**Hardware lab** `pi zero w and friends`

Pwnagotchi, Bjorn, P4wnP1 ALOA and ESP32 Marauder, to be folded into the red team track later. Also fixes dead hardware for fun, like tracing a POST error to a BIOS fix.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**Analyzer bridge** `python, serial, odbc`

Takes the serial output of a lab analyzer and pushes it into a LAN database, so results land where the lab staff can use them without manual entry.

</td>
<td width="50%" valign="top">

**IT copilot** `qwen 3.5 35b, rag, librechat`

A locally hosted LLM trained on our own applications through RAG. It helps staff resolve IT issues and write code, and it is connected to GLPI, AD and MECM so it can raise alerts and suggest fixes. Wazuh integration is next.

</td>
</tr>
</table>

<br>

<img src="./assets/h-rooms.svg" width="100%" alt="06 Rooms cleared">

<details open>
<summary><b>Cyber Security 101</b> (in progress)</summary>
<br>

| Room | Topic | Status |
|:--|:--|:--|
| John the Ripper | Hash cracking, wordlists, rules | done |
| MonikerLink (CVE-2024-21413) | Outlook moniker bug, NTLM leak | done |
| Metasploit: Introduction | msfconsole, modules, sessions | done |
| Metasploit: Exploitation | Exploit modules, payloads, shells | done |
| Hydra | Online password attacks | done |
| Gobuster | Directory and file enumeration | done |

**Lesson from Gobuster:** I lost time to a "can't connect" error because I forgot to restart dnsmasq after editing its config. Check that the name resolves before blaming the tool.

</details>

<details>
<summary><b>Pre Security</b> (complete)</summary>
<br>

Offensive Security Intro, Defensive Security Intro, Careers in Cyber, Inside a Computer System, Computer Types, Client-Server Basics, Virtualisation Basics, Cloud Computing Fundamentals, Operating Systems: Introduction, Windows Basics, plus the rest of the path.

</details>

Also done: **OverTheWire Bandit**, levels 0 to 10 so far.

Full notes live in [`pentest-portfolio`](https://github.com/sparse-pirate/pentest-portfolio) and the day-by-day record in [`red-team-journey`](https://github.com/sparse-pirate/red-team-journey).

<br>

<img src="./assets/h-stack.svg" width="100%" alt="07 Stack">

| | |
|:--|:--|
| **lab-tested offense** | ![Gobuster](https://img.shields.io/badge/Gobuster-ff3d3d?style=flat-square) ![Hydra](https://img.shields.io/badge/Hydra-ff3d3d?style=flat-square) ![John the Ripper](https://img.shields.io/badge/John_the_Ripper-ff3d3d?style=flat-square) ![Metasploit](https://img.shields.io/badge/Metasploit-ff3d3d?style=flat-square) ![Nmap](https://img.shields.io/badge/Nmap-ff3d3d?style=flat-square) |
| **defense** | ![SELinux](https://img.shields.io/badge/SELinux-1f9d55?style=flat-square) ![UFW](https://img.shields.io/badge/UFW-1f9d55?style=flat-square) ![Hardened SSH](https://img.shields.io/badge/Hardened_SSH-1f9d55?style=flat-square) ![Wazuh](https://img.shields.io/badge/Wazuh-1f9d55?style=flat-square) ![Zabbix](https://img.shields.io/badge/Zabbix-1f9d55?style=flat-square) |
| **infra** | ![Active Directory](https://img.shields.io/badge/Active_Directory-3a4350?style=flat-square&logo=windows&logoColor=white) ![VMware ESXi](https://img.shields.io/badge/VMware_ESXi-3a4350?style=flat-square&logo=vmware&logoColor=white) ![USMT](https://img.shields.io/badge/USMT-3a4350?style=flat-square) ![MECM](https://img.shields.io/badge/MECM-3a4350?style=flat-square) ![GLPI](https://img.shields.io/badge/GLPI-3a4350?style=flat-square) ![phpIPAM](https://img.shields.io/badge/phpIPAM-3a4350?style=flat-square) |
| **build** | ![Python](https://img.shields.io/badge/Python-3a4350?style=flat-square&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-3a4350?style=flat-square&logo=docker&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-3a4350?style=flat-square&logo=opencv&logoColor=white) ![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-3a4350?style=flat-square&logo=raspberrypi&logoColor=white) ![MSSQL](https://img.shields.io/badge/MSSQL-3a4350?style=flat-square&logo=microsoftsqlserver&logoColor=white) ![LLM + RAG](https://img.shields.io/badge/Qwen_%2B_RAG-3a4350?style=flat-square) ![LibreChat](https://img.shields.io/badge/LibreChat-3a4350?style=flat-square) |

<br>

<img src="./assets/h-learn.svg" width="100%" alt="08 How I learn">

1. **Hands-on first.** Labs and CTFs beat reading. Theory gets pulled in when a task needs it.
2. **Every room gets written up.** In my own words, with the commands, the mistakes and why it matters for red teaming. No flags, no answer keys.
3. **Small daily sessions.** Showing up for 15 minutes beats a marathon I never start.
4. **Break it on purpose.** My own homelab is the first target I harden and the first one I try to break.
5. **Authorized targets only.** TryHackMe, CTF platforms, intentionally vulnerable labs and my own gear.

<br>

<img src="./assets/h-connect.svg" width="100%" alt="09 Connect">

[![TryHackMe](https://img.shields.io/badge/TryHackMe-profile-ff3d3d?style=for-the-badge&logo=tryhackme&logoColor=white&labelColor=0a0c0f)](https://tryhackme.com/p/parodyparse)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-connect-8b95a3?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0a0c0f)](https://www.linkedin.com/in/YOUR_LINKEDIN_HANDLE)
[![Journey](https://img.shields.io/badge/repo-red--team--journey-39ff88?style=for-the-badge&labelColor=0a0c0f)](https://github.com/sparse-pirate/red-team-journey)

<img src="./assets/divider.svg" width="100%" alt="">

<div align="center">
  <sub>learn it. break it. write it up.</sub>
</div>
