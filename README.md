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
    * Secure over the air updatable userspace, kernel and bootloader
    * Provides container runtime for user applications
  * [gpsd](https://git.savannah.gnu.org/cgit/gpsd.git)
    * A utility that can listen to a GPS or AIS receiver and re-publish the positional data in a simpler format.
  * [rtl-ais](https://github.com/dgiardini/rtl-ais)
    * A simple AIS tuner and generic dual-frequency FM demodulator
    * [Automatic identification system](https://en.wikipedia.org/wiki/Automatic_identification_system)
  * [OpenCPN](https://opencpn.org)
    * Concise and robust Chart Plotter Navigation software

# OTA

Operating system updates managed by [Foundries.io](https://foundries.io) dashboard 
  * Note: Only microPlatform subscribers can have managed devices

![OTA](/images/ota.png)

# Goals

  * Create a functioning marine navigation system with [Open Navigation](https://github.com/open-nav)
  * Follow best practices for software and hardware security
  * Plotter UI for data display
  * NMEA data bridge via WIFI
  * Boat data transmitted to blockchain/dlt over LTE in deep buffer mode

# TODOs

- [x] Install Linux microPlatform on d410c
- [x] Review Linux driver support for LTE mezzanine
- [x] Order Project Fi data sim for testing
- [ ] Get data sheet / schematic for LTE mezzanine and uart protocol reference
- [ ] Test Project Fi sim card
- [ ] Containerize service for extracting sensors data from mezzanine and conver to NMEA 0183 message format
- [ ] Store marine data on blockchain / dlt
