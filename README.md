# GH60-RevCHN

Everything I need for my GH60.

# Editing layout:

Load ```layout/GH60_RevCHN_azerty_iso.json``` into http://kbfirmware.com/.

# Flashing firmware:

```
$ git clone https://github.com/kairyu/tkg-toolkit
$ tkg-toolkit/mac/setup.sh
  select the options "2", "N", "1" and press any key.
  Copy and rename the firmware to tkg-toolkit/common/firmware/gh60-revchn.hex
$ tkg-toolkit/mac/reflash.sh
```
