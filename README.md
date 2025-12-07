GhostCore — USB Firewall + Hardware Vault (WIP)

GhostCore is a pocket-sized USB security device I’m building through Hack Club OnBoard.
It sits between a laptop and any USB peripheral, acting as a hardware firewall that lets me inspect, allow, or block USB behavior in real time.

It also includes an offline encrypted vault using an ATECC608B secure element for TOTP and password storage.

Current Status:

Project proposal stage.
Hardware + firmware design coming soon.

Planned Structure
/hardware   → Schematics + PCB (soon)
/firmware   → RP2040 firmware
/case       → 3D/CNC enclosure files

Next Steps

Draft USB MITM architecture
Choose components
Build first schematic
Start firmware (USB parsing + UI)
