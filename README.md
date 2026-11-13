# Tinker Pixel Dungeon

**Your dungeon. Your rules.**

Tinker Pixel Dungeon is an open-source, customizable roguelike based on [Shattered Pixel Dungeon](https://github.com/00-Evan/shattered-pixel-dungeon), which itself is based on the original [Pixel Dungeon](https://github.com/watabou/pixel-dungeon) by Watabou.

The goal is to let players choose the kind of Pixel Dungeon experience they enjoy, customize the gameplay rules, and share their favorite configurations with others.

## The Idea

Different Pixel Dungeon variants have introduced interesting changes over the years: new monsters, additional items, expanded dungeons, different difficulty levels, and unique gameplay mechanics.

But what if you like the dungeon generation from one variant, the item availability from another, and the difficulty of a third?

Tinker Pixel Dungeon aims to let you mix and match these elements without requiring you to play an entirely different game.

**Choose a starting point. Adjust the rules. Make the dungeon your own.**

### Planned Features

- **Gameplay presets:** Start with a familiar experience inspired by Classic, Shattered, Soft, Sprouted, or other Pixel Dungeon variants.
- **Customizable dungeons:** Adjust level size, room counts, vegetation, monster density, and other generation parameters.
- **Adjustable loot:** Change the frequency and availability of items such as Potions of Strength and Scrolls of Upgrade.
- **Optional content:** Enable additional monsters, items, and mechanics inspired by other Pixel Dungeon forks.
- **Relaxed or extreme gameplay:** Make the game easier, more challenging, or deliberately unbalanced for fun.
- **Shareable configurations:** Generate a compact code that other players can use to reproduce your selected rules.

Presets will serve as starting points. Players will eventually be able to customize them rather than being restricted to a fixed set of game variants.

### Share Your Rules

A planned feature is the ability to encode gameplay settings into a short, shareable configuration code.

These codes are intended to remain compatible with future versions. When new optional features are introduced, older configurations should continue to work with those features disabled unless the player chooses to enable them.

Configuration codes will describe gameplay rules. Dungeon seeds may be used separately to share particular randomized adventures.

## Development Status

**Early development — not yet released.**

Tinker Pixel Dungeon currently begins with the Shattered Pixel Dungeon codebase. Its proposed customization features have not yet been implemented.

Development will initially focus on Android, using Android Studio on Windows.

### Development Roadmap

| Version | Goal |
|---|---|
| 0.1 | Establish Tinker branding, application identity, and custom title screen |
| 0.2 | Introduce gameplay preset selection and the underlying rules system |
| 0.3 | Add customization menus, adjustable gameplay parameters, and shareable configuration codes |
| 0.4+ | Expand available items, monsters, mechanics, and presets using ideas from other Pixel Dungeon variants |

Versions and features are planning targets and may change as development progresses. Presets will be introduced as their underlying mechanics become available.

## Development and Documentation

In addition to developing the game, this project aims to document the process of customizing Shattered Pixel Dungeon.

Planned documentation topics include:

- Setting up and building Shattered Pixel Dungeon
- Changing the application name, icon, and title screen
- Understanding the game's source-code organization
- Modifying potions, scrolls, and item generation
- Adjusting dungeon size and room generation
- Adding and modifying monsters
- Creating configurable gameplay rules
- Building backward-compatible configuration codes

Documentation will be added to the `docs/` directory as features are developed.

### Building the Project

Until Tinker-specific build instructions are available, refer to the existing Shattered Pixel Dungeon development guides:

- [Building for Android](docs/getting-started-android.md)
- [Building for Desktop](docs/getting-started-desktop.md)
- [Building for iOS](docs/getting-started-ios.md)
- [Recommended Changes for Derivative Projects](docs/recommended-changes.md)

## Origins and Credits

Tinker Pixel Dungeon builds on the work of the Pixel Dungeon open-source community.

Special thanks to:

- **Watabou**, creator of the original [Pixel Dungeon](https://github.com/watabou/pixel-dungeon).
- **Evan Debenham (00-Evan)**, creator of [Shattered Pixel Dungeon](https://github.com/00-Evan/shattered-pixel-dungeon).
- The developers and contributors of the many Pixel Dungeon variants that continue to explore new ideas and gameplay mechanics.

Features incorporated from other forks will be credited as they are researched and integrated.

Tinker Pixel Dungeon is an independent derivative project and is not an official release of Shattered Pixel Dungeon.

## License

Tinker Pixel Dungeon is distributed under the [GNU General Public License version 3](LICENSE.txt), consistent with its upstream projects.

Copyright and attribution notices from the original projects will be preserved. Imported third-party content will be reviewed for license compatibility and appropriate attribution.

---

**Tinker Pixel Dungeon — Your dungeon. Your rules.**
