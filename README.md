[![Cozy Tales Logo](img/Logo.png)](https://s4g.itch.io/cozytales)

## Cozy Tales (Student Project)
- Itch Page: https://s4g.itch.io/cozytales

#### Open World Exploration

Cozy Tales is an open-world exploration game, intended to be a laid-back
and cozy experience for the player. The player will meet several NPCs on
their journey, which might have interesting information for the player
about where they might find interesting things. The player also has access
to a map, which, initially, is enshrouded by a fog of war. An overarching
event system will dynamically trigger quests, which the player can mark on
their map. If the players puts down a correct map marker, the world will
react to it accordingly.

#### Gameplay
- decelerating gameplay, meant to be played without any stressful game-mechanic
- main focus on exploration and interacting with the world
- paying attention to what NPCs tell you, since the game will not give the player a lead, such as a quest marker

#### Roles
- Gameplay Mechanic
- Engineering

#### Engine / Languages
- Unreal Engine 5 / Blueprints, C++

#### Responsibilities

- **Movement Mechanic**: I implemented the movement mechanics, including walking, sprinting, and gliding. This involved creating a fluid and intuitive system for player navigation in the game environment.

- **Stamina**: Added a Stamina Bar that depletes when sprinting and regenerates when walking. This feature introduces a strategic element to the game, requiring players to manage their stamina wisely during exploration and combat.

- **Reaction to Slopes**: The character moves faster when descending slopes and significantly slower when ascending. At certain angles, the character will slide, adding a realistic and dynamic element to movement across varied terrains.

- **Inventory & Items**: I was responsible for developing the inventory system and item management. This includes creating a user-friendly interface for item storage and usage within the game.

- **Fishing**: Implemented a fishing mechanic where fish spawn and swim towards the player. Players must catch the fish at the right moment, adding a skill-based mini-game to the overall experience.

- **Harvesting**: Developed a planting mechanic for various seeds that grow into plants. Plants have multiple growth stages, and the system is flexible enough to support an unlimited number of plant types, growth stages, and growth durations.

- **Code Clean-up**: Regularly reviewed and refactored code to ensure it is clean, understandable, and maintainable. This includes optimizing existing code and removing unnecessary or redundant code segments.

- **Performance Optimization**: Ensured the code is highly performant, minimizing CPU and memory usage to provide a smooth gaming experience even on lower-end hardware.

- **Event System Implementation**: Implemented an event system for quests, including a QuestBoard mechanic that triggers events and checks if a quest has been completed correctly. Depending on the quest's status (complete, not complete, failed, etc.), the board executes different events, adding depth and variability to quest outcomes.

- **Telekinesis System**: Initially designed a telekinesis system allowing players to move objects without physical contact. This system was intended for puzzle mechanics and bridge-building but was abandoned early in production.


