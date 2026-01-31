# Vesperfall Documentation

Welcome to the official documentation for **Vesperfall**. This repository contains **all design, narrative, and technical documentation** for the project, structured to support developers, designers, writers, and contributors.

> ⚠️ This repository documents the **game’s design, mechanics, world, and systems**. It is **not the game itself**. No executable game code or assets are included here.

---

## Purpose

The documentation serves to:

* Provide a **single source of truth** for Vesperfall’s mechanics, classes, world, and systems.
* Support **team collaboration** across narrative, design, and programming disciplines.
* Make onboarding new contributors **fast and clear**.
* Ensure design decisions are **traceable, modular, and maintainable**.

---

## Structure

The documentation is organized into **perspectives**, separating story, gameplay, systems, and infrastructure:

```
.
├── <ROOT>.md              # Entry point for the documentation
├── Intentions/            # Design goals, philosophy, and thematic direction
├── World/                 # Story, lore, factions, and world-building
├── Gameplay/              # Player-facing experience, classes, and UI/UX
├── Systems/               # Game mechanics, entities, networking, and clients/servers
└── Infrastructure/        # Technical infrastructure and environment notes
```

> Each folder contains files grouped by purpose. For example, classes have a **mechanical perspective** in `Gameplay/Classes` and a **narrative perspective** in `World/Factions`.

---

## Conventions

* **Wikilinks** are used throughout to cross-reference files within the documentation.
* **Perspective separation**:

  * Narrative (World/Factions, Story, Lore)
  * Mechanics (Systems/Entities, Game Mechanics)
  * Player-facing (Gameplay/Classes, UI-UX)
* **Do not mix perspectives** — each file represents a single view of the game to maintain clarity.

---

## How to Use

* Start with `<ROOT>.md` for an overview.

* Follow folders based on your role:

  * **Writer / Narrative Designer** → World/Story, World/Lore, World/Factions
  * **Gameplay Designer / Class Designer** → Gameplay/Classes, Gameplay/Game Play
  * **Programmer / System Engineer** → Systems/Entities, Systems/Game Mechanics, Systems/Network

* Use the **wikilinks** to navigate between related topics easily.

---

## Contribution

* Add new content in the appropriate folder.
* Link new files using wikilinks to maintain cross-reference integrity.
* Follow the **perspective separation** rules to prevent documentation drift.
* Ensure any updates to mechanics or narrative are reflected in the Overview or Class tables for consistency.

---

## License
© 2026 CasuallyDreamin. All rights reserved.

This repository contains the design, narrative, and technical documentation for the game Vesperfall.

No part of this documentation may be copied, reproduced, distributed, published, or used for any purpose without the explicit written permission of the author.

For inquiries regarding usage, collaboration, or licensing, please contact: <dream.the.casual@gmail.com>.

