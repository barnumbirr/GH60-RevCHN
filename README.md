# GH60-RevCHN

Everything I need for my GH60-RevCHN/Satan. Kudos to [dr_derivative](https://www.reddit.com/user/dr_derivative)
on Reddit [for his help](https://www.reddit.com/r/MechanicalKeyboards/comments/7qbqos/gh60_azerty_iso_layout/dso0xau/).

## Parts

### Bangood

*   [GH60 DIY Mechanical Keyboard PCB](https://www.banggood.com/GH60-DIY-Mechanical-Keyboard-PCB-Support-Breathing-LED-60-Cherry-MX-Poker2-Poker3-p-1084998.html)
*   [6.25x PCB Mount Mechanical Keyboard Cap Stabilizer](https://www.banggood.com/2x-6_25x-PCB-Mount-Mechanical-Keyboard-Cap-Stabilizer-For-Cherry-MX-Switch-p-1086051.html)
*   [Aluminium Plate for GH60](https://www.banggood.com/Aluminium-Board-Plate-Mechanical-Keyboard-Universal-Frame-for-RS60-GH60-PCB-p-1077451.html)

### MecKey Alpha

*   [Aluminium CNC case for GH60](https://meckeyalpha.com/collections/keyboard-cases/products/60-cnc-aluminium-case)

### WASD Keyboards

*   [Cherry MX Red Plate Mounted Keyswitch](http://www.wasdkeyboards.com/index.php/products/keyboard-parts/cherry-mx-red-keyswitch-mx1a-l1nn-linear.html)
*   [62-Key ISO Custom Cherry MX Keycap Set](http://www.wasdkeyboards.com/index.php/products/keycap-set/62-key-cherry-mx-keycap-set.html)

## Editing layout:

Load ```layout/GH60_RevCHN_azerty_iso.json``` into http://kbfirmware.com/.
Download .hex formatted firmware after you've applied your changes.

## Flashing firmware:

```
$ git clone https://github.com/kairyu/tkg-toolkit
$ tkg-toolkit/mac/setup.sh
  select the options "2", "N", "1" and press any key.
  Copy and rename the firmware to tkg-toolkit/common/firmware/gh60-revchn.hex
$ tkg-toolkit/mac/reflash.sh
```
