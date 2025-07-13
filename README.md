Features:

Web server for app control (/relay1/toggle to /relay8/toggle)

Local control of relays 1–4

IR remote reception (8 codes total)

Receives IR codes from Slave via ESP-NOW

Sends ESP-NOW toggle commands for relays 5–8 (on Slave)




✅ Master Code Highlights:

Cleanly separates logic for:

IR

Web toggle

ESP-NOW command send/receive

Uses /relay1/toggle to /relay8/toggle for app control

IR codes can come from either Master or Slave
