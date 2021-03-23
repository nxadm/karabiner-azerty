# karabiner-azerty
Setup for AZERTY keyboards on MacOS + [Karabiner elements](https://pqrs.org/osx/karabiner/).

## Complex modifications

Put `azerty_fixes.json` in `~/.config/karabiner/assets/complex_modifications/`
and enable the desired rules in Karabiner Elements:
- remapping of ù to the accute accent deadkey (´), next to the grave accent deadkey (\`). 
This allows to type accents characters like ó as ù  + o, a lot easier than the default 
Alt + Shift + 1 + letter.
- remapping of the keypad comma to period.

## Simple modifications

Use `simple_modifications.json` as an example of what keys to modify in the
Simple Modifications GUI for your specific device (e.g. external keyboard).
The modifications here are for an external BE Azerty PC-keyboard and switches
the left Alt and Command keys, and put the '@' and '<' in the same place as a
Mac keyboard.
