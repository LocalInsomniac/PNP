# PNP

A universal gameplay mod for GZDoom that adds Zombies perks and powerups from
various Call of Duty games.

## Perks

Perk-a-Colas spawn next to big powerups, huge health items (Soulsphere) and
custom inventory items that count towards the item percentage (Berserk and
Megasphere) if there is enough space. When picked up, it will give you a unique
perk or a Teddy Bear. The chances of getting a Teddy Bear will increase the more
perks you have.

**Currently implemented:** Double Tap Root Beer II, Juggernog, PHD Flopper,
Speed Cola, Stamin-Up, Quick Revive, Widow's Wine

## Powerups

Any monster that is killed by a player has a low chance to drop a powerup,
provided that the spawn limit per map has not been reached.

**Currently implemented:** Death Machine, Instakill, Max Ammo, Nuke

## Console Commands

- `sv_pnp_powerChance`: The chance of a powerup dropping from a monster killed by
a player, in percentage. Default is `2`.

- `sv_pnp_maxPowers`: How many powerups can spawn in a map. Default is `4`.

- `sv_pnp_maxPerks`: How many perks a player can have. Default is `4`.