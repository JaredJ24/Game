# Troop System

## Overview

Troops are the collectible units that players deploy on the 3x3 grid during combat. Each troop occupies exactly 1 cell on the grid but has different deployment costs based on their power level and abilities. This resource management system is inspired by Clash of Clans' housing space and Clash Royale's elixir system, creating strategic depth in troop selection and deployment.

```
+------------------------------------------------------------------------------------+
|                           TROOP SYSTEM                                             |
+------------------------------------------------------------------------------------+
|                                                                                    |
|  DEPLOYMENT MECHANICS                     TROOP AFFINITIES                         |
|  +-------------------------+             +-------------------------+               |
|  | ENERGY COST             |             | FIRE                    |               |
|  | • Regenerates over time |             | • High damage           |               |
|  | • Higher for powerful   |             | • Creates fire terrain  |               |
|  |   troops                |             | • Strong vs Nature      |               |
|  | • Strategic deployment  |             | • Weak vs Water         |               |
|  |   decisions             |             +-------------------------+               |
|  +-------------------------+             | WATER                   |               |
|  | SQUAD CAPACITY          |             | • Control focus         |               |
|  | • Limited total capacity|             | • Movement abilities    |               |
|  | • Higher-rarity troops  |             | • Strong vs Fire        |               |
|  |   take more capacity    |             | • Weak vs Electric      |               |
|  | • Upgradable via        |             +-------------------------+               |
|  |   backpack improvements |             | ELECTRIC                |               |
|  +-------------------------+             | • Speed focus           |               |
|                                          | • Chain attacks         |               |
|  TROOP CATEGORIES                        | • Strong vs Water       |               |
|  +-------------------------+             | • Weak vs Nature        |               |
|  | ATTACKERS               |             +-------------------------+               |
|  | • High damage           |             | NATURE                  |               |
|  | • Low defense           |             | • Sustain focus         |               |
|  | • Single-target or AoE  |             | • Healing abilities     |               |
|  +-------------------------+             | • Strong vs Electric    |               |
|  | DEFENDERS               |             | • Weak vs Fire          |               |
|  | • High health           |             +-------------------------+               |
|  | • Taunt abilities       |             | LIGHT/DARK              |               |
|  | • Damage reduction      |             | • Support/Debuff        |               |
|  +-------------------------+             | • Special terrain       |               |
|  | SUPPORT                 |             | • Unique interactions   |               |
|  | • Healing               |             +-------------------------+               |
|  | • Buffs                 |                                                       |
|  | • Terrain manipulation  |                                                       |
|  +-------------------------+                                                       |
|                                                                                    |
+------------------------------------------------------------------------------------+
```

## Deployment System

### Energy Cost
- Each troop requires a specific amount of Energy to deploy
- Energy regenerates over time during battle (similar to Clash Royale's elixir)
- More powerful troops cost more Energy
- Strategic decisions must be made about deploying fewer powerful troops or more weaker troops

### Squad Capacity
- Players have a limited Squad Capacity for each battle (similar to Clash of Clans' housing space)
- Each troop takes up a certain amount of Squad Capacity
- More powerful troops require more Squad Capacity
- Squad Capacity can be increased through progression and backpack upgrades