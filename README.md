<div align="center">

<br>

<img src="logo.png" width="160" alt="Nexus+">

<br><br>

# NEXUS+

### External Rust Overlay v1.2.2 Updating 6.3.26

<br>

[![Status](https://img.shields.io/badge/STATUS-UNDETECTED-00ff88?style=for-the-badge&labelColor=0d1117)](https://github.com)
[![Game](https://img.shields.io/badge/GAME-RUST-cd412b?style=for-the-badge&labelColor=0d1117)](https://store.steampowered.com/app/252490/Rust/)
[![Type](https://img.shields.io/badge/TYPE-EXTERNAL-7c5cbf?style=for-the-badge&labelColor=0d1117)](https://github.com)
[![Overlay](https://img.shields.io/badge/RENDER-DX9%20%2B%20IMGUI-3388ff?style=for-the-badge&labelColor=0d1117)](https://github.com)

<br>

<sub>Kernel-driven memory access &bull; Custom ImGui interface &bull; Electron loader &bull; Discord auth</sub>

<br>

---

</div>

<br>

## `>` Overview

Nexus+ is a fully external overlay for Rust with kernel-level memory access, a custom-styled ImGui menu, and an Electron-based loader with Discord OAuth2 authentication. Everything from ESP to exploits — configured in a polished GUI with accent colors, particle effects, and a built-in radar.

<br>

## `>` Feature Map

<table>
<tr>
<td width="50%" valign="top">

### Aimbot
- Smart target lock with adjustable smoothing & FOV
- Interactive bone selector (click on player model)
- Multi-bone cycling (auto-switches every 3s)
- Dedicated bow aimbot with gravity prediction
- Movement prediction with smooth interpolation
- Configurable FOV circle & target line

### Player ESP
- Box / Corner Box / Skeleton
- Health bar (color-coded, auto-offset detection)
- Name, distance, held weapon icon
- Inventory belt display (hotbar items)
- Snaplines & head circle
- Per-type colors (enemy, sleeper, wounded)

### Team & Scientists
- Full independent teammate ESP config
- Scientist/NPC ESP with separate settings
- Ignore Scientists toggle (Misc)
- Per-type distance sliders

</td>
<td width="50%" valign="top">

### World ESP
- **Animals** — Bear, Boar, Wolf, Horse, Deer, Chicken, Shark, Snake
- **Ore Nodes** — Stone, Metal, Sulfur, HQM
- **Hemp Plants** — Dedicated toggle with custom color & distance
- **Dropped Items & Collectables**
- **Crate ESP** — Normal, Military, Elite, Locked, Heli, Supply, Underwater

### Deployables
- Patrol Heli, Sleeping Bags, Tool Cupboard
- Auto Turret, Flame Turret, Shotgun Trap, SAM Site

### Exploits
- **Movement** — Spiderman, Super Jump, Infinite Jump, Speed Hack, Walk on Water
- **Player** — Third Person, Bright Night, Fake Admin, Long Neck, Freeze, Shoot Mounted
- **Weapons** — No Spread, No Sway, No Recoil, Instant Compound, Fat Bullet, Fast Med, Rapid Fire

### Radar
- Real-time minimap (round / square)
- Adjustable zoom (50m–500m)
- Player names, distance, accent color sync

</td>
</tr>
</table>

<br>

## `>` Loader Pipeline

```
Discord Login ──▶ License Key ──▶ Driver Map ──▶ Download Build ──▶ Stealth Launch
```

| Step | Detail |
|:-----|:-------|
| **Auth** | Discord OAuth2 — no password shared |
| **Driver** | Auto-downloads mapper + driver, maps to kernel, cleans temp files |
| **Delivery** | Downloads latest build to hidden dir with randomized filename |
| **Verify** | Checks file size + MZ header to catch corrupt downloads |
| **Launch** | Spawns cheat detached & hidden, closes loader |

<br>

## `>` Pricing

<div align="center">

| | 1 Day | 1 Week | 1 Month |
|:--|:--:|:--:|:--:|
| **Price** | €4 | €10 | €25 |
| **All Features** | ✓ | ✓ | ✓ |
| **Priority Support** | — | ✓ | ✓ |

</div>

<br>

## `>` Quick Start

```
1.  Download the Nexus+ Loader
2.  Launch  →  Login with Discord
3.  Enter license key  (NEXUS-XXXX-XXXX-XXXX)
4.  Click Inject  →  Loader handles everything
5.  Join a server  →  Press INSERT to open menu
```

<br>

## `>` Keybinds

| Key | Action |
|:----|:-------|
| `Insert` | Toggle menu |
| `Aim Key` | Configurable (default: RMB) |
| `F2` | Launch from Loader |

<br>

## `>` Tech Stack

```
Cheat          C++20  ·  DirectX 9  ·  Custom ImGui
Memory         Kernel driver 
Overlay        Transparent DX9 window + ImGui render
Loader         Electron + Node.js
Auth           Node.js + Discord OAuth2
Config         JSON save/load (3 slots)
```

<br>

## `>` Requirements

- Windows 10 / 11 (64-bit)
- Rust (Steam)
- VC++ Redist 2015–2022 (auto-installed)
- Run as Administrator
- Internet connection

<br>

## `>` Settings Highlights

| Feature | Detail |
|:--------|:-------|
| **Accent Color** | Global theme — logo, radar, watermark, UI all sync |
| **Custom Crosshair** | Length, gap, thickness, color — works scoped |
| **Anti Screenshot** | Overlay hidden from screenshots |
| **Particle FX** | Animated menu background |
| **Config Slots** | 3 save slots with auto-load |
| **Discord Profile** | Avatar, name, and license timer in GUI |
| **Unload Button** | Clean exit from Settings tab |

<br>

---
<img width="2560" height="1440" alt="Full_1" src="https://github.com/user-attachments/assets/4f3e98a1-e069-4d08-a893-965114f44381" />
<img width="945" height="612" alt="_8" src="https://github.com/user-attachments/assets/ef07b719-1092-4bad-b77d-fe5054c6a4c5" />
<img width="934" height="609" alt="_7" src="https://github.com/user-attachments/assets/0235b12f-e40e-4875-9270-75fd422d981f" />
<img width="940" height="615" alt="_6" src="https://github.com/user-attachments/assets/4dbe3b7c-ba1c-4f56-99e1-1ae9203438ba" />
<img width="933" height="611" alt="_5" src="https://github.com/user-attachments/assets/ad0ca483-6e6a-41c7-a0c6-57046a22fbe6" />
<img width="932" height="610" alt="_4" src="https://github.com/user-attachments/assets/8fdc6f69-f334-4502-9fc5-8ba3ee2698ab" />
<img width="956" height="618" alt="_3" src="https://github.com/user-attachments/assets/96e7310f-3623-44fd-9649-b7203cf860fb" />
<img width="941" height="626" alt="_2" src="https://github.com/user-attachments/assets/d879b134-36ff-428f-bb00-90d2285c5e57" />
<img width="1199" height="654" alt="_1" src="https://github.com/user-attachments/assets/1e84eb9a-febc-4e8b-9161-754876a9d4f5" />
<img width="2560" height="1440" alt="Full_2" src="https://github.com/user-attachments/assets/f9a076e5-e6e3-4d32-bd09-b4f7fa0292d9" />

<div align="center">

<br>

<sub>

**Disclaimer** — Educational purposes only. Use at your own risk.
The developers are not responsible for bans, suspensions, or other consequences.

</sub>

<br>

**NEXUS+** — Built for performance. Designed for stealth.

<br><br>

</div>
