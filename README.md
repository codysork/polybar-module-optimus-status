# polybar-module-optimus-status
Displays the current selected graphics card for an optimus laptop.

<img src="https://github.com/codysork/polybar-module-optimus-status/blob/master/2020-04-23-130807_1920x1080_scrot.png"/>

## Requirements

- [Optimus Manager](https://github.com/Askannz/optimus-manager)
- [Font Awesome](https://github.com/FortAwesome/Font-Awesome)

## Setup
### Font
For any bars you will be adding this module to, make sure you include Font Awesome as a font.
```
[bar/example]

font-0 = "Font Awesome 5 Free:style=Solid:size=10;1"
```

### Module
```
[module/optimus-status]
type=custom/script
exec = /path/to/optimus-status.sh
```
