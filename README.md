MASTER ESP8266 CODE
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




//////////////////////////////////////////////////////////////////////


SLAVE ESP8266 CODE
Features:

IR receiver

Sends received IR codes to Master via ESP-NOW

Listens for relay toggle commands from Master

Controls relays 5–8 (connected to D6, D1, D2, D3)

/////////////////////////////////////////////////////////////////////

ESP8266 MAC Address: 08:F9:E0:6A:EE:30


WEMOS D1 MINI MAC Address: C4:5B:BE:6F:95:EA
