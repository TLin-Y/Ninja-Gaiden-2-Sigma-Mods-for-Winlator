# Ninja Gaiden Sigma 2 Mods

## Special Thanks

Special thanks to the mod writers:

- **Nozomi Miyamori**
- **Fiend Busa**
- **Lyall** ([Codeberg](https://codeberg.org/Lyall/NinjaGaidenMCFix))

---

## Mods

### 1. Black Mod
- **Source:** [Nexus Mods #37](https://www.nexusmods.com/ninjagaidenmastercollection/mods/37)

### 2. Gore Effects 4:3 Aspect Ratio (Optimized for RP Nova)
- **Source:** [Nexus Mods #236](https://www.nexusmods.com/ninjagaidenmastercollection/mods/236?tab=description)

> ⚠️ **Use only ONE of the above mods — do not combine them.** The Black Mod (#1) already includes the gore effects from #2 but with additional features (more complicated).

### 3. GameHub Load Container Config & Driver Settings
- Load this into your GameHub container.

---

## Installation

1. Copy **all files** from a mod folder into your **game root directory**.

## GameHub / Winlator Setup

### Driver Installation
Import the driver files (`winexinput.inf`, `winehid.pnf`, `input.pnf`) into your Winlator container for proper controller support.

### Save Data
Save files included:
- `USER_SETTING/WINSTATE.DAT` — controller/window state
- `SYSTEMSAVE.DAT` — system save data
- `STORYSAV0.DAT` — story progress save

### DXVK Config
DXVK cache files (`*.dxvk.bin`, `.dxvk.lut`) are included for shader optimization.

---

## Controller Setup (Winlator)

To fix the RP Nova Xbox controller issue, set the following Winlator environment variable:

```
WINEDLLOVERRIDES=dinput8=n,b
```

### GameHub Input Mapping

Configure the following mapping in GameHub:

| Action | Key Binding |
|---|---|
| Left Stick Push | `ALT` |
| Right Stick Push | `ENTER` |

### Controller Detection

At the game's beginning screen, **push both mapped keys twice** to select and pick up the controller.
