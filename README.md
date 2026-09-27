# DragonLinkX Royale

A top-down battle royale shooter you play in the browser. Twenty players drop onto an island, the storm closes in, and the last one standing wins. You pick a pet before each match, and it fights at your side.

## Play

Open `index.html` in any modern browser. There is nothing to install or build.

To serve it locally instead:

```sh
npx serve .
```

## Pets

| Pet | Species | What it does | Ability (Q) |
| --- | --- | --- | --- |
| Ember | Dragon | Flies over walls and shoots fireballs at your enemies | **Inferno Ring**: 16 fireballs in every direction |
| Fang | Wolf | Fast melee hunter that chases enemies down | **Pack Howl**: you run 45% faster for 5s and Fang bites for double damage |
| Luna | Owl | Heals you when you are out of combat and shoots feathers | **Moonlight**: heals 50 HP and shows every enemy on the minimap for 8s |
| Boulder | Turtle | Stands between you and the enemy to block bullets | **Shell Dome**: +50 shield and half damage taken for 5s |

If your pet is knocked out, it comes back after 15 seconds. About half of the bots bring pets too.

## Controls

**Keyboard and mouse**

- `WASD` / arrow keys: move
- Mouse: aim, click to shoot
- `R`: reload
- `E`: pick up or swap a weapon
- `1` / `2`, `X`, or the mouse wheel: switch weapon
- `F`: use a med kit, or drink a shield if your health is full
- `Q`: pet ability
- `Esc`: pause
- `M`: mute

**Touch**

- Left thumb: move
- Right thumb: aim; drag farther out to shoot
- Buttons: heal, reload, swap, pick up, pet ability

## Game rules

- **Weapons:** Pistol, SMG, Pump Shotgun, Assault Rifle, Sniper Rifle. Each drops in Common, Rare, Epic or Legendary rarity. Higher rarity means more damage.
- **Loot:** buildings have better loot. Med kits restore 50 HP, and shields add 50 shield. You can carry up to 5 of each.
- **Storm:** it closes in six phases. The dashed white circle shows the next safe zone. Storm damage gets stronger each phase and goes straight to your health.
- **Bots:** Easy, Normal and Hard settings change how accurate they are, how fast they react, and how much damage they do.
