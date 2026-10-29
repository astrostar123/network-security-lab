# Network Security Lab

An interactive, browser-based cyber security learning lab. Open it and click around a small office network to learn how the core defenses actually work. No install, no build step, no dependencies everything runs locally in your browser.

**Live demo:** enable GitHub Pages (Settings → Pages → deploy from `main`) and it will be served from `index.html`.

## What's inside

1. **The Network** a clickable topology (Internet, Firewall, Switch, Web Server in a DMZ, Staff/Finance PCs, Guest Wi-Fi). Click any device to see its role and its biggest security risk.
2. **Firewall Rule Builder** add allow/deny rules and send test packets to see the firewall decide. Demonstrates why a *default-deny* policy is safer than default-allow.
3. **Device Hardening Checklist** tick real controls (MFA, patching, least privilege, backups…) and watch a defense score rise.
4. **Attack Simulator** play the attacker: port scan, password brute-force, phishing, and malware/ransomware. Whether each attack succeeds depends on the hardening controls you ticked, so it rewards improving your defenses.
5. **Quick Quiz** five questions with instant feedback.

## Concepts covered

Firewalls and default-deny, network segmentation / VLANs, the DMZ, MFA, patching, least privilege, phishing, and ransomware backups.

## Run it

Just open `index.html` in any modern browser that's it.

---
*Built as a hands-on learning project. Educational use only.*
