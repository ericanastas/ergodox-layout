# Ergodox Layout

My [ErgoDox](https://www.ergodox.io/) split keyboard layout

![ergodox-layout.png](./keyboard-layout-editor/ergodox-layout.png)

## Goals

- Stay as close to standard keyboards as possible so moving to other computers is not a challege
- When there is not a 1:1 match in keys try to at least use the same fingers

### Example Keyboards

- [Keychron K2 (84/75%)](https://www.keychron.com/collections/all-keyboards/products/keychron-k2-wireless-mechanical-keyboard)
- [Keycool 84 (84 key/75%)](https://drop.com/buy/keycool-kc84-wireless-rgb-hotswap-mechanical-keyboard)
- [Keychron K6 (65%)](https://www.keychron.com/collections/all-products/products/keychron-k6-wireless-mechanical-keyboard)
- [Thinkpad X270](https://www.lenovo.com/us/en/p/laptops/thinkpad/thinkpadx/thinkpad-x270/22tp2tx2700?orgRef=https%253A%252F%252Fwww.google.com%252F)

## Links

- [QMK Configurator](https://config.qmk.fm/#/idobao/id80/v3/ansi/LAYOUT_80_ansi)
  - [ErgoDox EZ Glow Layout](https://config.qmk.fm/#/ergodox_ez/glow/LAYOUT_ergodox_pretty)
  - [Test Keyboard](https://config.qmk.fm/#/test)
  - [QMK Basic Keycodes](https://docs.qmk.fm/keycodes_basic)
- [Keyboard Layout Editor](https://www.keyboard-layout-editor.com/#/)

## Design

### Letters [Green-100:#DCFCE7]

Standard querty layout

### Digits [Blue-100:#DBEAFE]

Standard querty layout

### Modifier Keys [Red-100:#FEE2E2]

- Shift
  - Standard location (Left & Right)
- Ctrl
  - Standard location (Left & Right)
- Alt
  - Standard location (Left & Right)
- Layer 1 (Left & Right)
  - Under Thumbs (Left & Right)
  - Hold for temp
  - Tap to toggle
- Win (Left & Right)

  - Windows key
  - Standard location (Left & Right)

  - Many keyboards only have left windows key
  - Mac equivlent is Command and there are usually a left and right

- Mouse Mode Layer (TBD)

  - Set with left hand
  - Control Mouse with right hand keyboard
  - Movment JKLI
  - Controls
    - Mouse Movement Up, Down, Left, Right
    - Mouse Click 1, 2, 3
    - Mouse Wheel Up, Down, Left, Right

- Menu
  - Open context menu
  - On Right side to match keyboards that have it
- Fn
  - Alt function like home, search, switch app, settings, vol up/down
  - On Left side on lenovo laptops
  - On Left side to match lenovo laptops
  - Possible Function
    - Power
    - Sleep
    - Wake
    - Help
    - Multimedia
      - Prev
      - Next
      - Mute
      - Vol UP
      - Vol Down
      - Stop
      - Play
      - Rewind
      - Fast Forward
    - X270
      - F1: Mute 🔊 🕩🔇
      - F2: Vol Down
      - F3: Vol Up
      - F4: Mute Mic (not standard)
      - F5/F6: Brightness
      - F7: External Dispalys
      - F8: Wifi
      - F9: Settings
      - F

### Other Characters

- Apostrophe (') / Quotation Mark (")
  - Right of Colon (:) / Semi Colon (;) like other keyboards
- Back Slash (\\) / Pipe (|)

  - Right of P like othe keyboards

- Grave Accent (`) / Tilde (~) (TBD)

  - This is usualy at top left under esc
  - Grave is used often in coding
  - Vs Code Short Cuts
    - Ctrl+` toggles terminal in vs code
    - Ctrl+SHIFT+` creates a new terminal
  - Possibly set to top right key next to 0
  - Keychron K6 Combines this with ESC

- Hyphen (-) / Underscore (\_) (TBD)

  - Usualy to the right of 0

- Equal (=) / Plus (+) (TBD)

  - Usualy to the right of 0

- Square Brackets ([]) / Curly Brackets ({}) (TBD)
  - These are usualy on keys betwen P and Backslash (\\)
  - Use right pinky
  - Need to do with one hand as curly brackets require shift modifier
  - Same as square brackes with shift modifier
  - Add to O and P keys on layer
    - use the same ring and pinky fingers

### Function Keys (F1-F12) [Cyan-100:#CFFAFE]

Layer 1 of Number keys

F11 and F12 on center keys are number row

### Arrow Keys [Violet-100:#EDE9FE]

Map to HJKL on layer 1 like Vim

### Text Nav Keys [Yellow-100:#FEF9C3]

Map to UOPL on layer 1

- Home
- End
- PgDn
- PgUp

### Text Editing [Orange-100:#FFEDD5]

- Space
  - left thumb
- Back Space
  - left thumb
- Enter
  - right thumb
- Tab

  - Standard location left of Q
  - Also right thumb

- Delete (TBD)
  - Typical at top right of keyboard
  - Can't be on layer, needed for CTRL+Alt+Delete
  - Actually could be ok if on bkpsace as CTRL+ALT+DEL could be done with left hand while right hand chooses layer. This is kind of akward though
  - Could Keep above BkSpc so same thumb is used for both backspace and delete
  - Could be above space as this also moves the cursor
- Insert (TBD)
  - Could be on
- Caps Lock
  - Standard Location left of A

### Misc [Pink-100:#FAE8FF]

- Esc
  - Keep as dedicated key on top left
  - Windows shortcut use this
    - Open Task Manager: Ctrl+Shift+Esc
    - Start Menu: Ctrl+Esc
    - Cycle Window: Alt+Esc

NmLk, PrtSc, ScrlLk, Pause/Break on top center keys.
You have to take your hand off

- Prt Scrn (TBD)
  - Should be left hand since right hand will be on mouse
  - not used that often
- Scroll Lock (TBD Low)
  - Rarely used
- Pause (TBD Low)

  - Rarely used

- Num Lock (TBD Low)
  - Rarely used

Some keyboard combine the following
NmLk (PrtSc), ScrLk (Pause), Insert (Delete)
