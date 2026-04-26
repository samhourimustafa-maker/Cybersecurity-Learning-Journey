# Hardware Notes

## Topic
CompTIA A+ Core 1 — Hardware Fundamentals

## Overview
This section covers the main hardware concepts an entry-level IT technician should understand: displays, cables, RAM, storage, motherboards, CPUs, power supplies, printers, and basic troubleshooting.

My focus is not only memorizing parts, but understanding what each component does, how it connects, and what to check when something fails.

---

## Displays

| Component | Purpose / Notes |
|---|---|
| LCD | Common display type that uses a backlight |
| IPS | Better colors and viewing angles |
| TN | Fast response time, often cheaper |
| VA | Better contrast than TN |
| OLED | Pixels create their own light, great contrast |
| Mini-LED | Improved backlighting with better brightness and contrast |
| Touch screen/digitizer | Detects touch input |
| Inverter | Powers the backlight in some older LCD screens |

Important display attributes:

- **Resolution:** Number of pixels on the screen
- **Refresh rate:** How many times the screen updates per second
- **Pixel density:** How sharp the image looks
- **Color gamut:** Range of colors the display can show

Example:
If a laptop screen is very faint but still shows an image, I would suspect the backlight or inverter before blaming the video card.

---

## Cables and Connectors

### Network cables

| Cable | Purpose |
|---|---|
| UTP | Common Ethernet cable |
| STP | Ethernet cable with shielding |
| Coaxial | Cable internet and TV |
| Fiber optic | High-speed data over longer distances |

Fiber types:

- **Single-mode:** Longer distance
- **Multimode:** Shorter distance, often inside buildings

Ethernet notes:

- **T568A/T568B:** Wiring standards for Ethernet cables
- **Plenum-rated:** Safer cable used in air-handling spaces
- **Direct burial:** Designed for underground use

### Common connectors

| Connector | Common Use |
|---|---|
| RJ11 | Phone line |
| RJ45 | Ethernet |
| F-type | Coax cable |
| ST / SC / LC | Fiber connectors |
| USB-C | Modern data, charging, and video |
| MicroUSB / MiniUSB | Older mobile devices/accessories |
| Lightning | Apple mobile devices |
| DB9 | Serial devices |
| Molex | Older internal power connector |

### Video and storage cables

| Cable | Purpose |
|---|---|
| HDMI | Audio/video, common for TVs and monitors |
| DisplayPort | Common for PC monitors |
| DVI | Older digital video |
| VGA | Older analog video |
| SATA | Internal storage |
| eSATA | External SATA storage |
| Thunderbolt | High-speed data, display, and power |

---

## RAM

RAM is temporary memory used while the computer is running.

| RAM Concept | Notes |
|---|---|
| DIMM | Desktop RAM |
| SODIMM | Laptop RAM |
| DDR | RAM generation/type |
| ECC | Detects and corrects some memory errors |
| Non-ECC | Common consumer RAM |
| Dual-channel | Uses matching RAM sticks for better performance |

Simple explanation:
RAM must match the motherboard. More RAM can help performance, but only if the system supports it.

---

## Storage

| Storage Type | Notes |
|---|---|
| HDD | Uses spinning disks, cheaper, slower |
| SSD | No moving parts, faster and more reliable |
| SATA SSD | Faster than HDD, uses SATA |
| NVMe SSD | Very fast SSD using PCIe |
| M.2 | Small SSD form factor |
| mSATA | Older small SSD form factor |
| Flash drive | Portable USB storage |
| Memory card | Used in cameras and mobile devices |
| Optical drive | Reads/writes CDs, DVDs, or Blu-ray |

### RAID basics

| RAID | Main idea |
|---|---|
| RAID 0 | Speed, no redundancy |
| RAID 1 | Mirroring for protection |
| RAID 5 | Striping with parity |
| RAID 6 | More fault tolerance than RAID 5 |
| RAID 10 | Speed and redundancy |

Simple explanation:
HDDs are cheaper but slower. SSDs are faster and better for performance. RAID can improve speed, protection, or both depending on the setup.

---

## Motherboards, CPUs, and Expansion Cards

The motherboard connects the main parts of the computer together.

### Motherboard form factors

| Form Factor | Notes |
|---|---|
| ATX | Standard desktop size |
| microATX | Smaller than ATX |
| ITX | Very small build size |

### Common motherboard connections

- PCI / PCIe expansion slots
- Power connectors
- SATA ports
- M.2 slots
- Front panel headers
- USB/audio/fan headers

### CPU notes

A CPU must be compatible with the motherboard socket.

Important CPU concepts:

- **Intel and AMD** use different socket types
- **x86/x64** is common for desktops and laptops
- **ARM** is common in phones, tablets, and some laptops
- More cores can help with multitasking and heavier workloads

### BIOS/UEFI settings

Common settings to know:

- Boot order
- Secure Boot
- TPM
- USB permissions
- Fan settings
- Temperature monitoring
- Virtualization support
- BIOS or boot passwords

Security note:
TPM and Secure Boot help protect the system during startup and support encryption features.

### Expansion cards

| Card | Purpose |
|---|---|
| Video card | Graphics/display processing |
| Sound card | Audio input/output |
| NIC | Network connection |
| Capture card | Captures video input |

---

## Cooling

Cooling prevents overheating.

Common cooling parts:

- Fans
- Heat sink
- Thermal paste or pads
- Liquid cooling

Troubleshooting note:
If a computer shuts down randomly or gets very hot, I would check dust buildup, fan operation, airflow, heat sink contact, and thermal paste.

---

## Power Supplies

A power supply converts wall power into usable power for computer components.

| Power Supply Concept | Notes |
|---|---|
| 110–120 VAC | Common in the United States |
| 220–240 VAC | Common in many other countries |
| 3.3V / 5V / 12V | Power outputs used by components |
| 20+4 pin | Main motherboard power connector |
| Modular PSU | Uses only needed cables |
| Redundant PSU | Backup PSU, common in servers |
| Wattage rating | Must support the system’s power needs |
| Efficiency rating | Better efficiency wastes less energy as heat |

Simple explanation:
When choosing a PSU, I need to check wattage, connectors, efficiency, and whether the system needs redundancy.

---

## Printers and Multifunction Devices

A multifunction device can print, scan, copy, and sometimes fax.

### Printer setup basics

- Unbox and place the printer properly
- Install the correct driver
- Connect by USB, Ethernet, or Wi-Fi
- Update firmware if needed
- Configure paper tray, quality, duplex, and orientation
- Test printing and scanning

### PCL vs. PostScript

| Driver | Notes |
|---|---|
| PCL | Common and fast for office printing |
| PostScript | Better for graphics and accurate layouts |

### Printer security

Important printer security features:

- User authentication
- Badge access
- Secured print release
- Audit logs

### Scanning options

Scans can be sent to:

- Email
- SMB shared folder
- Cloud services

---

## Printer Maintenance

| Printer Type | Maintenance |
|---|---|
| Laser | Replace toner, clean, calibrate, maintenance kit |
| Inkjet | Replace ink, clean printheads, clear jams |
| Thermal | Replace thermal paper, clean heating element |
| Impact | Replace ribbon, printhead, and paper |

Simple reminder:

- Laser = toner
- Inkjet = liquid ink
- Thermal = heat and special paper
- Impact = ribbon and physical impact

---

## Troubleshooting Examples

| Problem | What I would check |
|---|---|
| Faint laptop screen | Backlight or inverter |
| Computer will not boot after RAM upgrade | RAM seating and compatibility |
| SSD not detected | BIOS/UEFI, SATA/M.2 connection |
| PC shuts down randomly | Power supply, overheating, fans |
| Printer has streaks | Toner/ink, printhead, cleaning |
| Weak Wi-Fi after repair | Wireless card antenna cables |

---

## My simple explanation

Hardware troubleshooting is about checking the physical parts, connections, compatibility, power, cooling, and drivers. A good technician starts with simple checks before replacing parts.
