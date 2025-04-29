# Home Lab 🏠🛡️

## Project Overview 🎯

This project builds a small but fully functional home Security Operations Center (SOC) environment using leftover hardware, open-source software, and persistence.  
The goals are:
- Set up a functional SOC environment. 🛡️
- Test SOAR-lite functionality. 🤖
- Keep costs as close to zero as possible. 💸

---

## Current Lab Architecture 🖥️📡

| Component | Description |
|:---|:---|
| **Router** | "Slightly" used Linksys router flashed with OpenWRT, firewall rules configured, mirroring port to the SIEM. 🔥 |
| **Syslog Server** | A decade-old cow laptop running rsyslog, still energetic enough to collect logs from the network. 🐄📜 |
| **SIEM Server** | An old gaming laptop, now living its second life as a shelf unit — similar to the Museum of Heads from *Futurama*. 🎮🧠 |
| **Kali Box** | Offensive testing platform for internal network validation. 🧨 |
| **Winnie the Pooh's HoneyPot** | A designated honeypot to observe and investigate attack attempts. 🍯🐻 |

---

## Core Functions ⚙️

| Function | Purpose |
|:---|:---|
| **SOC Functionality** | Should functionally mirror basic SOC environments. 🏢 |
| **SOAR Automation** | Explore what can be done automatically in this barebones environment. 🤖 |
| **HoneyPot** | Investigate intrusion attempts and evaluate network defense effectiveness. 🕵️‍♂️🐝 |

---

## Project Status 📋

- Power cable obtained for broken screen gaming laptop. 🔌
- Ubuntu Server setup for the syslog server. 🐧
- Router still in procurement phase. 📦
- Honeypot still in procurement. 🍯
- Network diagrams in progress. 🗺️
- Proposal draft finished, upload soon. 📝

---

## Planned Future Improvements 🚀

- <span style="color:gold">**All the $$$**</span> 💰
  - Desktop with multiple Intel NICs flashed and built into a functional IPS interacting with the SIEM/SOAR-lite.
  - Upgrade hardware for the syslog server and SIEM.

- <span style="color:deepskyblue">**All the Time**</span> 🕰️😵
  - Ticketing system with notifications.
  - Automated logic syncing discovered threats and write-ups directly to the repo.
  - Pentest madness: attempt red team operations against the environment, document successes and failures.

---

## Guiding Philosophy 📖

> *"Security is a process, not a product."*  
> — Bruce Schneier 🔐

This is a learning project designed to demonstrate real-world security engineering skills on a shoestring budget.

---

## License 📜

MIT License — feel free to reuse, modify, or adapt anything useful for your own home lab projects.

