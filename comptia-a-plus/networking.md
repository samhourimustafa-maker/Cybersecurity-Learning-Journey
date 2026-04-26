# Networking Notes

## Topic
CompTIA A+ Core 1 — Networking fundamentals

## What I learned
Networking is how devices communicate with each other. For A+, I need to understand common ports, TCP vs. UDP, wireless basics, IP addressing, network hardware, server roles, and basic troubleshooting.

---

## TCP vs. UDP

| TCP | UDP |
|---|---|
| More reliable | Faster |
| Checks that data arrives correctly | Sends data without as much checking |
| Used for web, email, file transfer, remote access | Used for DNS, streaming, gaming, voice/video calls |

My simple way to remember it:

- **TCP** = reliable delivery
- **UDP** = fast delivery

---

## Common Ports

| Port | Protocol | Purpose |
|---|---|---|
| 20/21 | FTP | File transfer |
| 22 | SSH | Secure remote access |
| 23 | Telnet | Unsecure remote access |
| 25 | SMTP | Sending email |
| 53 | DNS | Name to IP address |
| 67/68 | DHCP | Assigns IP addresses |
| 80 | HTTP | Unsecure web traffic |
| 110 | POP3 | Downloads email |
| 143 | IMAP | Syncs email |
| 389 | LDAP | Directory services |
| 443 | HTTPS | Secure web traffic |
| 445 | SMB/CIFS | File and printer sharing |
| 3389 | RDP | Remote desktop |

Security note: Telnet, FTP, and HTTP are not secure because they do not encrypt traffic like SSH or HTTPS.

---

## Wireless Basics

| Frequency | Best for | Notes |
|---|---|---|
| 2.4 GHz | Longer range | Slower, more interference |
| 5 GHz | Faster Wi-Fi | Shorter range than 2.4 GHz |
| 6 GHz | Newer high-speed Wi-Fi | Fast, but shorter range and needs newer devices |

Other wireless technologies:

- **Bluetooth:** Short-range connection for headsets, keyboards, mice, speakers, and cars.
- **NFC:** Very short-range communication, like tap-to-pay.
- **RFID:** Used for tracking, badges, inventory, and access control.

---

## Important Network Services

| Service | Purpose |
|---|---|
| DNS | Turns website names into IP addresses |
| DHCP | Gives devices IP settings automatically |
| File share | Stores shared files |
| Print server | Manages printers |
| Mail server | Handles email |
| Web server | Hosts websites |
| AAA | Authentication, Authorization, and Accounting |
| NTP | Keeps device time synchronized |

---

## DNS and DHCP Concepts

### DNS records

| Record | Purpose |
|---|---|
| A | Points a name to an IPv4 address |
| AAAA | Points a name to an IPv6 address |
| CNAME | Alias for another name |
| MX | Mail server record |
| TXT | Text record used for verification and email security |

Email security records:

- **SPF:** Says which servers can send email for a domain.
- **DKIM:** Helps prove an email was not changed.
- **DMARC:** Tells servers what to do if SPF or DKIM fails.

### DHCP terms

- **Lease:** How long a device can keep an IP address.
- **Reservation:** Gives the same IP to a specific device.
- **Scope:** Range of IP addresses DHCP can give out.
- **Exclusion:** Addresses DHCP should not hand out.

---

## Network Hardware

| Device | Purpose |
|---|---|
| Router | Connects different networks, like home network to internet |
| Switch | Connects devices inside a LAN |
| Access point | Provides Wi-Fi |
| Firewall | Allows or blocks traffic |
| Patch panel | Organizes network cables |
| PoE | Sends power and data over Ethernet |
| Cable modem | Internet through coax cable |
| DSL modem | Internet through phone line |
| ONT | Used for fiber internet |
| NIC | Network card for wired or wireless connection |

---

## IP Addressing

- **IPv4:** Common address format, like `192.168.1.10`
- **IPv6:** Newer, longer address format
- **Private IP:** Used inside local networks
- **Public IP:** Used on the internet
- **Static IP:** Manually assigned
- **Dynamic IP:** Automatically assigned by DHCP
- **Subnet mask:** Defines the network range
- **Gateway:** Usually the router
- **APIPA:** Starts with `169.254.x.x` and usually means DHCP failed

---

## Internet and Network Types

### Internet connection types

- **Fiber:** Very fast and reliable
- **Cable:** Common home internet
- **DSL:** Uses phone lines
- **Cellular:** Uses 4G/5G mobile networks
- **Satellite:** Useful in remote areas but higher latency
- **WISP:** Wireless internet provider, often used in rural areas

### Network types

- **LAN:** Local network
- **WAN:** Large network, like the internet
- **PAN:** Personal network, like Bluetooth
- **MAN:** City-sized network
- **SAN:** Storage network
- **WLAN:** Wireless local network

---

## Networking Tools

| Tool | Purpose |
|---|---|
| Crimper | Attaches connectors to Ethernet cables |
| Cable stripper | Removes cable jacket |
| Wi-Fi analyzer | Checks wireless signal and channels |
| Toner probe | Traces cables |
| Punchdown tool | Connects wires to patch panels or jacks |
| Cable tester | Tests if a cable works correctly |
| Loopback plug | Tests a network port |
| Network tap | Copies traffic for monitoring |

---

## Troubleshooting Examples

| Problem | Possible Cause | What I would check |
|---|---|---|
| IP starts with `169.254` | DHCP failed | Router, DHCP, cable, Wi-Fi |
| Website works by IP but not name | DNS issue | DNS settings |
| Weak Wi-Fi | Distance or interference | Router placement, frequency, channel |
| Cannot remote into PC | RDP/firewall issue | Port 3389, firewall, permissions |
| File sharing not working | SMB issue | Network sharing, firewall, permissions |

---

## My simple explanation

Networking is about how devices find each other, talk to each other, and share resources. When troubleshooting, I should start with the basics first: cables, Wi-Fi, IP address, gateway, DNS, DHCP, and firewall settings.
