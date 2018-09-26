# Open Marine Navigation

Open Source Marine Navigation Platform for [96boards](96boards.org). YVR18 Hackathon contest project. 

# Hardware

  * Dragonboard 410c
  * Shiratech LTE Mezzanine (Connectivity, GPS, Sensors)
  * Realtek RTL2832U (AIS)
  * RS422 USB to serial converter (NMEA 0183)

# Software

  * [Foundries.io](https://foundries.io) Linux microPlatform
  * gpsd (GPS parsing)
  * rtl-ais (AIS Parsing)
  * OpenCPN (Plotter)

# Goals

  * Create a functioning marine navigation system with [Open Navigation](https://github.com/open-nav)
  * OpenCPN based plotter
  * Dragonboard 410c creates NMEA data bridge via WIFI
  * Boat data transmitted to blockchain/dlt over LTE on demand
