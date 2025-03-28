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
