# QLC+ configuration
Q Light Controller+ configuration files used to control DMX lights at various venues and events.

http://qlcplus.org/

## H62
H62 has a BitWizard DMX interface connected to Raspberry Pi 2 UART pins and a Korg NanoKontrol2 USB MIDI controller as the user interface.

http://bitwizard.nl/shop/DMX-interface-for-Raspberry-pi

output universe 1: UART
input universe 2: nanoKontrol2
feedback universe 2: nanoKontrol2

## Fixtures
### connected
- 2x Octafly XS ("beams")
- 1x Rotobeam w. DMX ofF/on switch ("spinner")
- 3x LED bars w. 3 RGB segments each ("led bars"
- 1x Strobe ("strobe"
- 1x UV bar ("uv)
- 1x Blinder bar ("blinder")
- 1x Fog Fury Jett ("co2 smoke")
- 1x Entoruage Hazer ("hazer") (only connected during Syntax Error events)

### not connected (yet)
- 2x UV Floods
- 1x Pocket Roll
- 1x twin laser
- 1x Cubix 2.0

### todo
- Switch to TouchOSC for the user interface using a 10" Android tablet and the new stable WiFi (separate VLAN?)

![NanoKontrol2 Mapping](/H62.png)
