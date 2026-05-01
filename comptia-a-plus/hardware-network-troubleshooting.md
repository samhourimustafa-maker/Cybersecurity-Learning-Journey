# Hardware and Network Troubleshooting Notes

## Topic
CompTIA A+ Core 1 — Hardware and Network Troubleshooting

## Overview
This section focuses on recognizing common symptoms and knowing what to check first. A good technician does not guess right away. They look at the symptoms, check the simple causes first, and then move toward hardware replacement or deeper troubleshooting.

---

## Motherboard, RAM, CPU, and Power Issues

| Symptom | Possible Cause | What I would check |
|---|---|---|
| POST beeps | Hardware failure or missing component | Beep code, RAM, GPU, motherboard manual |
| Blank screen | Display, RAM, GPU, or power issue | Monitor, cables, RAM seating, GPU, power |
| No power | Bad outlet, PSU, cable, motherboard | Wall outlet, power cable, PSU switch, power supply |
| Sluggish performance | Low RAM, overheating, failing drive | Task Manager, RAM usage, temperatures, storage health |
| Overheating | Dust, bad fan, poor airflow, thermal paste | Fans, vents, heat sink, thermal paste |
| Burning smell | Electrical short or failing component | Shut down immediately and inspect safely |
| Random shutdown | Overheating or power issue | Temperatures, PSU, power cable, event logs |
| App crashes | RAM, storage, software, overheating | Memory test, updates, drive health, temperatures |
| Unusual noise | Fan, HDD, or power supply issue | Identify source of noise |
| Swollen capacitors | Motherboard damage | Inspect motherboard |
| Wrong date/time | Bad CMOS battery | Replace CMOS battery |

Simple note:  
If there is a burning smell, swollen capacitor, or repeated random shutdowns, I would stop using the device until it is inspected safely.

---

## Drive and RAID Issues

| Symptom | Possible Cause | What I would check |
|---|---|---|
| Grinding noise | Failing hard drive | Back up data and replace drive |
| Clicking sound | Mechanical drive failure | Back up data immediately |
| Bootable device not found | Drive not detected or OS issue | BIOS/UEFI, cables, boot order, drive health |
| Data loss/corruption | Failing drive or file system issue | Backups, SMART status, disk check |
| SMART failure | Drive predicting failure | Replace drive as soon as possible |
| Slow read/write times | Failing drive or full drive | Drive health, free space, performance |
| Missing drive in OS | Loose cable, failed drive, driver issue | Disk Management, cables, BIOS/UEFI |
| RAID failure | One or more failed drives | RAID controller, drive status, rebuild process |
| Array missing | RAID config/controller issue | RAID settings, controller, drive order |
| Audible alarm | RAID or storage warning | Check RAID/storage management tool |
| LED status indicator | Drive status or failure warning | Match LED pattern with manufacturer guide |

Simple note:  
Clicking or grinding from an HDD is serious. The priority is to protect the data first, then replace the drive.

---

## Video, Projector, and Display Issues

| Symptom | Possible Cause | What I would check |
|---|---|---|
| Incorrect input source | Wrong source selected | HDMI/DisplayPort/VGA input |
| No image/blank display | Cable, monitor, GPU, power | Power, cable, input, external display |
| Fuzzy image | Bad cable or wrong resolution | Cable quality, resolution settings |
| Dim image | Backlight, brightness, inverter | Brightness, backlight, inverter |
| Flashing screen | Cable, refresh rate, driver | Cable, display settings, drivers |
| Incorrect colors | Cable, color settings, display issue | Cable, color profile, monitor settings |
| Dead pixels | Physical screen defect | Confirm with solid color test |
| Burn-in | Static image damage | Display type, screen saver, replacement if severe |
| Distorted image | Resolution, cable, GPU issue | Resolution, cable, display driver |
| Audio issues | Wrong output or cable issue | Audio output, HDMI/DisplayPort audio |
| Projector shuts down | Overheating or bad bulb | Airflow, filter, bulb, temperature |
| Sizing issues | Scaling or resolution problem | Display scaling, projector/monitor settings |

Simple note:  
For display problems, I would check the input source and cable before assuming the screen or GPU is bad.

---

## Mobile Device Issues

| Symptom | Possible Cause | What I would check |
|---|---|---|
| Poor battery health | Old or failing battery | Battery health settings, charging behavior |
| Swollen battery | Battery failure | Stop using device and replace safely |
| Broken screen | Physical damage | Screen replacement options |
| Improper charging | Cable, port, adapter, battery | Charger, cable, charging port, battery |
| Poor connectivity | Wi-Fi, cellular, Bluetooth issue | Airplane mode, signal, settings, SIM/eSIM |
| Liquid damage | Internal corrosion or short | Power off, inspect, avoid charging |
| Overheating | Battery, apps, charging, environment | Apps, battery, charger, temperature |
| Digitizer issues | Touchscreen input problem | Touch test, screen damage, calibration |
| Damaged ports | Physical wear or debris | Inspect and clean carefully |
| Malware | Suspicious apps or behavior | Uninstall apps, scan, update OS |
| Cursor drift | Calibration or touchpad issue | Calibration, drivers, touchpad settings |
| Cannot install apps | Storage, OS version, restrictions | Free space, app compatibility, MDM settings |
| Stylus not working | Battery, pairing, compatibility | Stylus battery, Bluetooth, supported device |
| Degraded performance | Storage, apps, battery, malware | Storage space, background apps, updates |

Simple note:  
For mobile devices, I would check settings, battery health, storage, app permissions, and physical damage before replacing parts.

---

## Network Issues

| Symptom | Possible Cause | What I would check |
|---|---|---|
| Intermittent Wi-Fi | Weak signal or interference | Distance, channel, router placement |
| Slow network speeds | Bandwidth, signal, cable, ISP issue | Speed test, Wi-Fi signal, Ethernet cable |
| Limited connectivity | DHCP or IP issue | IP address, gateway, DHCP, APIPA |
| Jitter | Unstable network timing | Wi-Fi quality, latency, congestion |
| Poor VoIP quality | Jitter, latency, packet loss | Network load, QoS, Wi-Fi signal |
| Port flapping | Bad cable or switch port | Cable, switch port, NIC |
| High latency | Network congestion or routing issue | Ping, traceroute, ISP, Wi-Fi |
| External interference | Wireless interference | Nearby devices, channels, 2.4GHz congestion |
| Authentication failures | Wrong credentials or server issue | Password, account status, RADIUS/AAA |
| Intermittent internet | ISP, modem, router, signal issue | Modem, router, logs, ISP status |

Simple note:  
For network issues, I would start with the basics: cable, Wi-Fi signal, IP address, DNS, gateway, and whether other devices have the same problem.

---

## Printer Issues

| Symptom | Possible Cause | What I would check |
|---|---|---|
| Lines on pages | Dirty printer, toner, printhead issue | Clean printer, toner, printhead |
| Garbled print | Wrong driver or corrupt job | Correct driver, restart print job |
| Paper jams | Bad paper, rollers, debris | Paper path, rollers, paper type |
| Faded prints | Low toner/ink or wrong settings | Toner/ink level, print quality |
| Paper not feeding | Tray or roller issue | Paper tray, rollers, paper alignment |
| Multipage misfeed | Worn rollers or wrong paper | Rollers, paper type, humidity |
| Jobs stuck in queue | Print spooler or connectivity issue | Restart spooler, clear queue |
| Speckling | Dirty printer or toner issue | Clean printer, replace toner |
| Double/echo image | Drum or fuser issue | Imaging drum, fuser |
| Grinding noise | Mechanical issue | Paper path, gears, rollers |
| Staple jam | Finisher issue | Clear staple path |
| Hole punch issue | Finisher or paper alignment | Check finisher and paper settings |
| Wrong orientation | Print setting issue | Portrait/landscape settings |
| Tray not recognized | Tray sensor or configuration | Reseat tray, check printer settings |
| Connectivity issue | Network, USB, or driver problem | Cable, Wi-Fi, IP, driver |
| Frozen print queue | Spooler problem | Restart print spooler, clear queue |

Simple note:  
Printer troubleshooting usually starts with paper, toner/ink, drivers, queue status, and connectivity.

---

## My Troubleshooting Mindset

When troubleshooting, I should not jump straight to replacing hardware. I should first check:

1. Power
2. Cables and connections
3. Settings
4. Error messages or lights
5. Recent changes
6. Drivers or firmware
7. Hardware health

## My simple explanation

Troubleshooting is about matching symptoms to likely causes. The best technicians stay calm, check the simple things first, protect user data, and only replace parts when there is enough evidence.
