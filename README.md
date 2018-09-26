# Open Marine Navigation

Open Source Marine Navigation Platform for [96boards](96boards.org). YVR18 Hackathon contest project.

![OpenCPN Plotter](/images/opencpn.jpg) 

# Hardware

  * Dragonboard 410c
  * Shiratech LTE Mezzanine (Connectivity, GPS, Sensors)
  * Realtek RTL2832U (AIS)
  * RS422 USB to serial converter (NMEA 0183)

![d410c](/images/d410c.jpg)

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

# TODOs

- [x] Install Linux microPlatform on d410c
- [x] Review Linux driver support for LTE mezzanine
- [x] Order Project Fi data sim for testing
- [ ] Get data sheet for LTE mezzanine and uart protocol?!?
