# 🌌 Eldritch Game

An independent digital board game project inspired by *Eldritch Horror*, developed as a learning and experimentation project using **HTML, CSS, and JavaScript**.

The project started as an HTML prototype and is gradually being rebuilt into a modular architecture, with the goal of making its mechanics easier to understand, maintain, test, and expand.

> ⚠️ **Disclaimer:** This is an independent project created for educational and development purposes. It is not an official product and is not affiliated with the owners of *Eldritch Horror*.

---

## 🎮 About the Project

The goal of this project is to create a digital experience based on the concepts of **cooperative investigation and cosmic horror**.

Players take on the role of investigators who explore the world, encounter monsters, solve mysteries, and deal with supernatural events while attempting to prevent an ancient threat from awakening.

### Planned Systems

- 🕵️ Investigators
- 👁️ Ancient Ones
- 🗺️ Map and travel locations
- 🚂 Movement and transportation
- 💰 Resources
- 🔮 Artifacts
- ✨ Spells
- ⚠️ Conditions
- 👹 Monsters
- 🌀 Gates
- 🔍 Clues
- 📜 Mythos Cards
- 🧩 Mysteries
- 📖 Research Cards
- ⚔️ Combat
- 🎴 Encounters
- 🔄 Turns and game phases
- 🏆 Victory and defeat conditions

---

## 🧪 Project Status

> **🚧 In Development**

The project currently has a **functional prototype** that serves as a reference for the modular version.

### Prototype

The original prototype keeps most of the game logic inside a single HTML file. It was created to quickly test game mechanics and the overall structure of the project.

The prototype will remain in the repository as a reference version.

### Modular Version

The project is being reorganized into a modular structure:

```text
src/
├── index.html
├── css/
│   ├── style.css
│   ├── board.css
│   ├── cards.css
│   └── investigators.css
│
└── js/
    ├── main.js
    ├── game.js
    ├── setup.js
    ├── map.js
    ├── movement.js
    ├── combat.js
    ├── encounters.js
    ├── mythos.js
    │
    └── data/
        ├── investigators.js
        ├── ancients.js
        ├── resources.js
        ├── artifacts.js
        ├── spells.js
        ├── conditions.js
        ├── monsters.js
        ├── mythos-cards.js
        ├── mysteries.js
        └── research.js
```

The main goal is to separate:

**Game data** → `data/`

**Game logic and systems** → `js/`

This makes it possible to add new investigators, cards, monsters, and other content without modifying the core systems.

---

## 🛠️ Technologies

The project currently uses:

- **HTML5**
- **CSS3**
- **JavaScript**
- **SVG** for map elements
- **Git**
- **GitHub**

The project is currently being developed without frameworks in order to focus on learning the fundamentals of JavaScript and web development.

---

## 🗺️ Roadmap

### 🏗️ Architecture

- [x] Create functional prototype
- [ ] Separate HTML, CSS, and JavaScript
- [ ] Build modular architecture
- [ ] Separate game data from game systems
- [ ] Create centralized game state management
- [ ] ~~Add save/load functionality~~

### 🕵️ Investigators

- [ ] Implement all investigators
- [ ] Implement investigator attributes
- [ ] Implement active abilities
- [ ] Implement passive abilities
- [ ] Implement 1–8 player setup
- [ ] Implement investigator states

### 🗺️ Map

- [ ] Implement the complete map
- [ ] Implement all travel locations
- [ ] Implement routes
- [ ] Implement travel system
- [ ] Implement transportation
- [ ] Implement gates
- [ ] Implement clues
- [ ] Implement monster movement

### 🎴 Cards

- [ ] Resources
- [ ] Artifacts
- [ ] Spells
- [ ] Conditions
- [ ] Monsters
- [ ] Mythos
- [ ] Mysteries
- [ ] Research

### ⚙️ Game Systems

- [ ] Turn system
- [ ] Action system
- [ ] Encounter system
- [ ] Combat system
- [ ] Test system
- [ ] Effect system
- [ ] Mythos system
- [ ] Mystery system
- [ ] Victory conditions
- [ ] Defeat conditions

### 🎨 Interface

- [ ] Main game interface
- [ ] Card display
- [ ] Investigator panels
- [ ] Ancient One information
- [ ] Game indicators
- [ ] Accessibility improvements
- [ ] Responsive interface

---

## 📚 Educational Purpose

This project also serves as a **hands-on programming learning project**.

During development, the following concepts will be studied and practiced:

- JavaScript
- HTML
- CSS
- Functions
- Objects and arrays
- Object-oriented programming
- Modularization
- DOM manipulation
- State management
- Git
- GitHub
- Testing
- Software architecture
- Game development

The goal is not only to make the game work, but also to **understand how each system works and how to structure a larger software project**.

---

## 📁 Repository Structure

```text
eldritch-game/
│
├── prototype/       # Original functional prototype
│
├── src/             # Main game implementation
│   ├── css/         # Styles
│   └── js/          # Game systems and logic
│       └── data/    # Game data
│
├── assets/          # Images, icons, and other resources
│
├── docs/            # Documentation
│
└── tests/           # Tests
```

---

## 🚧 Development

This project is under active development.

The architecture, systems, and code structure may change as the project evolves and new features are implemented.

The existing prototype **does not necessarily represent the final architecture** of the game.

---

## 📜 License

This is an independent project intended primarily for educational and personal development purposes.

*Eldritch Horror* and its associated intellectual property belong to their respective owners. This project does not claim ownership of copyrighted materials belonging to third parties.
