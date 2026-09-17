# Ninja Gaiden Sigma 2 Mods

## Special Thanks

Special thanks to the mod writers:

- **Nozomi Miyamori**
- **Fiend Busa**
- **Lyall** ([Codeberg](https://codeberg.org/Lyall/NinjaGaidenMCFix))

---

## Mods 4:3 Aspect Ratio (Optimized for RP Nova)
Editing the .ini file can force lock it to any resolution and aspect ratio, ignoring Winlator's limits

### 1. Black Mod
- **Source:** [Nexus Mods #37](https://www.nexusmods.com/ninjagaidenmastercollection/mods/37)

### 2. Gore Effects
- **Source:** [Nexus Mods #236](https://www.nexusmods.com/ninjagaidenmastercollection/mods/236?tab=description)

> ⚠️ **Use only ONE of the above mods — do not combine them.** The Black Mod (#1) already includes the Gore Effects from #2 but with additional features (more complicated).

### 3. Winlator Load Container Config & Driver Settings
- Refer to the screenshots for setup guidance. 

---

## Setup

1. Copy all files from **one** of the mod folders into your game root directory.
2. Refer to the screenshots for Winlator (GameHub/Light, Ludashi etc.) container config and driver setup. 
3. Set the Winlator environment variable:

```
WINEDLLOVERRIDES=dinput8=n,b
```
If controller not working:
a. In input mapping: set **Left Stick Push**(any unused) = `ALT`, **Right Stick Push** = `ENTER`.
b.  At the game's beginning screen, **push both mapped keys twice** to pick up the controller. (fullscreen switch)
