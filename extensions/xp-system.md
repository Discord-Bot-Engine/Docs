# XP System

**Description:**\
XP and level tracking system for members. Awards XP for messages, levels up users, and increases XP requirements dynamically.

**Inputs:**

* Is enabled?
* XP member data field
* Max XP member data field
* Level member data field
* Max XP multiplier
* XP multiplier

**Behaviour:**\
When enabled, listens for user messages in guilds. Randomly increments user XP per message by a value scaled by the XP multiplier. Levels are increased when current XP reaches the max XP threshold, which is then multiplied by the max XP multiplier for the next level. Emits a levelUp event upon leveling. Stores level, XP, and max XP values persistently.
