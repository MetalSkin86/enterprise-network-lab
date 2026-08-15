# Enterprise Network Lab

A hands-on enterprise network lab built from scratch in VirtualBox, simulating a small company's IT infrastructure — from Active Directory to perimeter security.

## What's inside
- **Active Directory & GPO** — domain setup, OUs, security groups, drive mapping, software restrictions (AppLocker), account lockout policy
- **Network Segmentation** — OPNsense firewall separating departments (Marketing/Office) into isolated subnets, with controlled access to shared server resources
- **DNS Content Filtering** — Unbound DNS blocklists to restrict access to specific domains
- **Intrusion Detection (Suricata)** — IDS configured on OPNsense, including a custom detection rule for internal network scans
- **VPN Remote Access (WireGuard)** — secure remote access into the internal network, scoped by department

## Why I built this
I built this lab to gain hands-on experience with enterprise IT infrastructure while studying cybersecurity at university, and to be ready to contribute from day one in an IT support/networking role.

## Full documentation
— full write-up with screenshots, configuration steps, and troubleshooting for every component above.

## Key skills demonstrated
Windows Server & AD DS · Group Policy · OPNsense firewall administration · network segmentation · DNS filtering · IDS/Suricata · WireGuard VPN · systematic troubleshooting
