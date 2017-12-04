# QLC+ configuration
Q Light Controller+ configuration files used to control DMX lights at various venues and events.

http://qlcplus.org/

## H62
H62 has a BitWizard DMX interface connected to Raspberry Pi 2 UART pins and a Korg NanoKontrol2 USB MIDI controller as the user interface.

http://bitwizard.nl/shop/DMX-interface-for-Raspberry-pi

output universe 1: UART
input universe 2: nanoKontrol2
feedback universe 2: nanoKontrol2

### wishlist
- Inno Pocket Roll actually rolling, it's currently working more like a moving head which looks dumb and lacks energy
- Color choices for the LED bars, most animations are preset to red, would be great with an RGB knob selection
- Animation mapping choices for the LED bars, only 6 are mapped and half are good, half are useless
- Speed presets for Pocket Roll, low, mid and high intensity or a speed knob for the rolling and a tap button for pattern change interval
  - Or presets for: dansgolvsjenga, warmup and high energy
- FX Smoke machine can do a lot more than just puff some red smoke
- Cubix 2.0 and the twin laser is not yet connected, would be useful to be able to black those out using Grand Master at least
- Pocket Roll moving head aim, use two knobs or faders to control roll and pan so it can be used as a search light without going to simple desk
- a simple way to update the mapping image, or a text table that's understandable

![NanoKontrol2 Mapping](/H62.png)
