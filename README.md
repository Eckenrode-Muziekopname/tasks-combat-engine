# T.A.S.K.S. Combat Engine

**Unified TTRPG combat system for Obsidian.md** combining initiative tracking and integrated dice rolling with optional Discord integration.

> **Fork Notice**: This plugin combines two excellent Obsidian plugins:
> - [Initiative Tracker](https://github.com/javalent/initiative-tracker) by Jeremy Valentine
> - [Dice Roller](https://github.com/javalent/dice-roller) by Jeremy Valentine
>
> Full credit to the original authors. This fork integrates both systems into a unified combat experience.

## Features

### Core Features (No external dependencies)

✅ **Initiative Tracking**
- Track combat rounds and turn order
- Manage HP, AC, temp HP, and status effects
- Support for multiple parties and encounters
- Automatic sorting by initiative
- Combat logging to markdown files

✅ **Integrated Dice Rolling**
- Roll dice directly in combat view
- Automatic attribution to active combatant
- Full D&D dice notation support (XdY+Z, advantage, disadvantage, etc.)
- Roll history for the current encounter
- Visual dice rendering (3D dice animations)

✅ **Combat Log**
- Track all rolls and combat events
- Export combat history to markdown
- Review past encounters

### Optional Integrations

🔗 **Discord Webhooks** (Simple Setup)
- Post combat updates to Discord channels
- Share dice rolls with your party in real-time
- Just paste your webhook URL - no server needed!
- Supports multiple webhooks for multi-campaign setups

🚀 **T.A.S.K.S. API Integration** (Advanced)
- For users running the T.A.S.K.S. consciousness server
- Multi-campaign character management
- Advanced party detection and channel routing
- Cross-platform combat sync

## Installation

### Manual Installation
1. Download the latest release
2. Extract to `<vault>/.obsidian/plugins/tasks-combat-engine/`
3. Reload Obsidian
4. Enable "T.A.S.K.S. Combat Engine" in Settings → Community Plugins

### Building from Source
```bash
git clone https://github.com/Eckenrode-Muziekopname/tasks-combat-engine.git
cd tasks-combat-engine
npm install
npm run build
```

## Quick Start

### 1. Basic Combat Tracking
1. Click the sword icon in the left ribbon
2. Click "Start Combat"
3. Add combatants using the "+" button
4. Click "Next Turn" to advance through combat

### 2. Rolling Dice in Combat
- Click the dice icon in combat view
- Enter your roll (e.g., `1d20+5`)
- Roll is attributed to active combatant
- Results appear in combat log

### 3. Discord Integration (Optional)
1. Settings → T.A.S.K.S. Combat Engine
2. Enable "Discord Integration"
3. Paste your Discord webhook URL
4. Done!

## License

GPL-3.0 (inherited from upstream projects)

## Credits

- **Initiative Tracker & Dice Roller**: [Jeremy Valentine](https://github.com/valentine195)
- **Integration**: Eckenrode Muziekopname
