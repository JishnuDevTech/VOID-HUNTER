# VOID HUNTER ⚡

> **Destroy everything. Leave nothing.**

A top-down space shooter built entirely in vanilla HTML, CSS, and JavaScript — no frameworks, no dependencies, no install. One file. Open and play.

---

## Play

Just open `VoidHunter.html` in any modern browser. No server needed.

---

## Controls

| Input | Action |
|---|---|
| `W A S D` or Arrow Keys | Move ship |
| Mouse | Aim |
| Left Click (hold) | Shoot |
| `Space` | Nova Special (when charged) |

---

## Weapons

Choose your loadout before each mission. Each weapon has a distinct playstyle.

| Weapon | Fire Rate | Damage | Style |
|---|---|---|---|
| **Cannon** | Slow | High | Precision burst fire |
| **Laser** | Fast | Low | Sustained rapid fire |
| **Scatter** | Medium | Medium | Shotgun spread |

---

## Enemies

| Enemy | Behavior | Threat |
|---|---|---|
| **Drone** | Direct charge, no shooting | Low |
| **Fighter** | Strafes side to side, shoots | Medium |
| **Speeder** | Zigzag approach, very fast | Medium |
| **Tank** | Slow, very tanky, rapid fire | High |
| **Boss** | Multi-phase AI, spiral bullet patterns | Extreme |

Bosses appear every 4th wave and have two phases — at 50% HP they enter rage mode with increased speed and a full bullet spiral.

---

## Progression

### Waves
Enemies scale in count and HP each wave. Every wave cleared triggers an **upgrade pick**.

### Upgrades (14 total)

| Upgrade | Rarity | Effect |
|---|---|---|
| Overdrive | Rare | Damage ×1.4 |
| Annihilator | Epic | Damage ×1.8 |
| Afterburner | Common | Speed ×1.3 |
| Ghost Drive | Rare | Speed ×1.6 |
| Overclocked | Rare | Fire rate ×1.4 |
| Full Auto | Epic | Fire rate ×2 |
| Hull Plate | Common | +40 max HP |
| Tri-Shot | Rare | Fire 3 bullets at once |
| Armor Pierce | Epic | Bullets pass through enemies |
| Smart Rounds | Legendary | Bullets home in on enemies |
| Nanobots | Rare | HP regenerates over time |
| Collector | Common | Auto-attract nearby powerups |
| Nova Boost | Epic | Special charges 50% faster |
| Deflector | Rare | Adds regenerating energy shield |

### Combo Multiplier
Killing enemies in quick succession builds your combo (up to ×8 at high level). Combo decays if you stop getting kills. All score is multiplied by current combo.

### XP & Leveling
Each kill grants XP. Leveling up increases your max combo cap and triggers a visual effect.

---

## Powerup Drops

Enemies have a 15% chance to drop a powerup on death. Bosses always drop 4.

| Powerup | Effect |
|---|---|
| ♥ Repair | +30 hull HP |
| 🛡 Shield | +30 shield energy |
| ⚡ Nova | +40% special charge |
| ★ Bonus | Score burst based on wave × combo |

---

## Nova Special

Fill the **NOVA** bar by getting kills. When full, press `Space` to release a 24-bullet omnidirectional burst that pierces all enemies and deals massive damage. Guaranteed to clear a room.

---

## Scoring & Ranks

Your final rank is calculated from total score + wave reached + max combo.

| Rank | Score Threshold |
|---|---|
| S | 8,000+ |
| A | 4,000+ |
| B | 2,000+ |
| C | 800+ |
| D | Below 800 |

---

## Technical Details

- **Single file** — `VoidHunter.html` contains all HTML, CSS, and JS (~70KB)
- **Canvas 2D rendering** — custom game loop at 60fps
- **Web Audio API** — fully synthesized sound engine, zero audio files
- **Particle system** — physics-based explosions with sparks, embers, and glow
- **Screen shake** — magnitude-scaled trauma system
- **No dependencies** — runs offline, no CDN required (except Google Fonts for typography)

---

## Browser Support

Works in all modern browsers. Chrome and Firefox recommended for best audio performance. Mobile playable via touch controls (tap and drag to move/aim).

---

*Built with vanilla JS · Inspired by classic arcade shooters · No AI libraries were harmed in the making of this game*
