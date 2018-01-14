# GH60-RevCHN

Everything I need for my GH60. Kudos to [dr_derivative](https://www.reddit.com/user/dr_derivative)
on Reddit [for his help](https://www.reddit.com/r/MechanicalKeyboards/comments/7qbqos/gh60_azerty_iso_layout/dso0xau/).

# Editing layout:

Load ```layout/GH60_RevCHN_azerty_iso.json``` into http://kbfirmware.com/.
Download .hex formatted firmware after you've applied your changes.

# Flashing firmware:

```
$ git clone https://github.com/kairyu/tkg-toolkit
$ tkg-toolkit/mac/setup.sh
  select the options "2", "N", "1" and press any key.
  Copy and rename the firmware to tkg-toolkit/common/firmware/gh60-revchn.hex
$ tkg-toolkit/mac/reflash.sh
```
