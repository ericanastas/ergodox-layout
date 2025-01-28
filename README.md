# Ergodox Layout

My [ErgoDox](https://www.ergodox.io/) split keyboard layout

![ergodox-layout.png](./keyboard-layout-editor/ergodox-layout.png)

## Goals

Stay as close to standard keyboards as possible

### Example Keyboards

- [Keychron K2 (84/75%)](https://www.keychron.com/collections/all-keyboards/products/keychron-k2-wireless-mechanical-keyboard)
- [Keycool 84 (84 key/75%)](https://drop.com/buy/keycool-kc84-wireless-rgb-hotswap-mechanical-keyboard)
- [Keychron K6 (65%)](https://www.keychron.com/collections/all-products/products/keychron-k6-wireless-mechanical-keyboard)
- [Thinkpad X270](https://www.lenovo.com/us/en/p/laptops/thinkpad/thinkpadx/thinkpad-x270/22tp2tx2700?orgRef=https%253A%252F%252Fwww.google.com%252F)

## Links

- [QMK Configurator](https://config.qmk.fm/#/idobao/id80/v3/ansi/LAYOUT_80_ansi)
  - [ErgoDox EZ Glow Layout](https://config.qmk.fm/#/ergodox_ez/glow/LAYOUT_ergodox_pretty)
  - [Test Keyboard](https://config.qmk.fm/#/test)
- [Keyboard Layout Editor](https://www.keyboard-layout-editor.com/#/)

## Design

### Querty Letters [Green-100:#DCFCE7]

Standard querty layout

### Digits [Blue-100:#DBEAFE]

Standard querty layout

### Modifier Keys (TBD) [Red-100:#FEE2E2]

- Shift
  - Standard location (Left & Right)
- Ctrl
  - Standard location (Left & Right)
- Alt
  - Standard location (Left & Right)
- Layer 1 (Left & Right)
  - QMK layer
- Win (TBD)
  - Windows key
  - Many keyboards only have left windows key
  - Mac equivlent is Command and there are usually a left and right
- Menu (TBD)
  - Open context menu
- Fn (TBD)
  - Alt function like home, search, switch app, settings, vol up/down
  - could skip this

### Function Keys (F1-F12) [Cyan-100:#CFFAFE]

Layer 1 of Number keys

F11 and F12 on center keys are number row

### Arrow Keys [Violet-100:#EDE9FE]

Map to JKLI on layer 1

### Text Nav Keys [Yellow-100:#FEF9C3]

Map to UOPL on layer 1

- Home
- End
- PgDn
- PgUp

### Text Editing (TBD) [Orange-100:#FFEDD5]

- Space
  - left thumb
- Back Space
  - left thumb
- Enter
  - right thumb
- Tab (TBD)
  - Standard location left of Q
  - could also add to thumb
  - maybe layer 1 space
- Delete (TBD)
  - Can't be on layer, needed for CTRL+Alt+Delete
  - actually could be ok if on bkpsace as CTRL+ALT+DEL could be done with left hand while right hand chooses layer
- Insert (TBD)
- Caps Lock
  - Standard Location left of A

### Misc (TBD) [Pink-100:#FAE8FF]

- Esc (TBD)
  - Reach with out moving hand off home row
- Prt Scrn (TBD)
  - Should be left hand since right hand will be on mouse
- Scroll Lock (TBD)
  - Rarely used
- Break / Pause (TBD)
  - Rarely used
- Num Lock (TBD)
  - Rarely used

### Other Characters (TBD)

- APOSTROPHE (') / QUOTATION MARK(")
  - right of : ; like other keyboards
- Grave Accent (`) / Tilde (~)
- Square Brackets ([])
  - Need to do with one hand as curly brackets require shift modifier
- Curly Brackets ({})

  - Same as square brackes with shift modifier

- Back Slash (\\) / Pipe (|)
- Hyphen (-) / Underscore (\_)
- Equal (=) / Plus (+)
