# Grid Combat System

## Overview

The Grid Combat System is the core tactical element of Pocket Tactics, creating deep strategic gameplay through positioning, terrain manipulation, and troop synergies. The system uses a 3x3 grid that rotates with the player, creating a dynamic battlefield that evolves throughout combat.

```
+------------------------------------------------------------------------------------+
|                           3x3 GRID COMBAT SYSTEM                                   |
+------------------------------------------------------------------------------------+
|                                                                                    |
|  +-------+-------+-------+       TERRAIN TYPES                                     |
|  |       |       |       |       +----------------+----------------+               |
|  |   1   |   2   |   3   |       | NEUTRAL        | FIRE           |               |
|  |       |       |       |       | No effects     | Damages non-   |               |
|  +-------+-------+-------+       |                | fire troops    |               |
|  |       |       |       |       +----------------+----------------+               |
|  |   4   |   P   |   5   |       | WATER          | ELECTRIC       |               |
|  |       |       |       |       | Slows movement | Chains damage  |               |
|  +-------+-------+-------+       +----------------+----------------+               |
|  |       |       |       |       | NATURE         | DARK/LIGHT     |               |
|  |   6   |   7   |   8   |       | Heals over time| Special effects|               |
|  |       |       |       |       +----------------+----------------+               |
|  +-------+-------+-------+                                                         |
|                                                                                    |
|  GRID FEATURES:                   TERRAIN COMBINATIONS:                            |
|  • Player (P) at center           • Fire + Water = Steam (stealth)                 |
|  • 8 deployable positions         • Water + Electric = Chain Lightning             |
|  • Grid rotates with player       • Fire + Nature = Ash (boosts dark troops)       |
|  • Terrain affects troop          • Light + Dark = Void (special abilities)        |
|    performance                                                                     |
|                                                                                    |
|  +----------------------------+   +----------------------------+                    |
|  |      ROTATION SYSTEM      |   |      DIRECTIVE SYSTEM      |                    |
|  +----------------------------+   +----------------------------+                    |
|  | • Rotate grid 90° once    |   | • Focus Fire               |                    |
|  |   per turn                |   | • Protect Me               |                    |
|  | • Creates new adjacency   |   | • Control Territory        |                    |
|  |   combinations            |   | • Conserve Energy          |                    |
|  | • Redirects hazards       |   | • Auto-battle following    |                    |
|  | • Aligns terrain types    |   |   player directives        |                    |
|  +----------------------------+   +----------------------------+                    |
|                                                                                    |
+------------------------------------------------------------------------------------+
```

## Core Grid Mechanics

### Grid Structure
- 3x3 grid with player character at center position (2,2)
- 8 deployable positions surrounding the player
- Grid is confined to the player's relative position and orientation
- Grid moves and rotates with the player, maintaining relative positioning
- Troops cannot leave their assigned grid coordinates

### Terrain Types
The grid cells can contain different terrain types that affect troop performance:

- **Neutral**: No special effects
- **Fire**: Damages non-fire troops over time, boosts fire troops
- **Water**: Slows movement speed, boosts water troops
- **Electric**: Chains damage between adjacent enemies, boosts electric troops
- **Nature**: Heals troops over time, boosts nature troops
- **Light/Dark**: Special effects for corresponding troop types

### Terrain Combinations
When certain terrain types are adjacent, they can create powerful combination effects:

- **Fire + Water = Steam**: Creates stealth opportunities
- **Water + Electric = Chain Lightning**: Enhanced damage chains
- **Fire + Nature = Ash**: Boosts dark troops' abilities
- **Light + Dark = Void**: Enables special abilities for all troops

## Rotation System

A unique feature of the Grid Combat System is the ability to rotate the entire grid:

- Players can rotate the grid 90° once per turn
- Rotation creates new adjacency combinations between troops
- Rotation can redirect hazards and align favorable terrain types
- Strategic rotation is key to maximizing troop synergies and avoiding threats

## Directive System

Troops auto-battle but follow "directives" set by the player before combat:

- **Focus Fire**: Troops prioritize a single target
- **Protect Me**: Troops focus on defending the player
- **Control Territory**: Troops prioritize holding specific grid positions
- **Conserve Energy**: Troops use abilities sparingly to save energy

These directives create strategic depth without requiring micromanagement of individual troops.
