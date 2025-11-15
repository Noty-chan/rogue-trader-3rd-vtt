# Dark Heresy 2nd Edition

This is my _unofficial_ system for playing mine Rogue Trader 3rd Edition on [Foundry VTT](https://foundryvtt.com/). This now requires Foundry VTT 13.313 or a newer V13 build.

It offers extensive support for character sheets, compendium packs, and automated management to save you time and allow you to focus on role playing. The existing system listed on Foundry was character sheet only and thus this system was created to facilitate the automation features I desired.



## Features

🗡️ The system includes a variety of compendium packs, such as weapons, weapon mods, talents, armor, psychic abilities, ammunition, tools, traits, attack specials (toxic, corrosive, etc.), and consumables and drugs.

💪 During character creation, there are automated bonuses for backgrounds, roles, and elite advances.

🧰 You can easily manage your inventory by dragging and dropping items, such as weapon mods and custom ammunition to build weapons, or storing items in a location on your ship to reduce encumbrance.

🔫 You can also drag weapons and skills to the macro bar for easy access, and the system offers automation support for weapon specials, most talents, attack types, and custom ammunition when you attack. Modifiers like distance and character size are automatically taken into account when targeting an attack.


## Foundry V13 Support

The 0.1.1 release was re-tested on Foundry VTT 13.313. When upgrading an existing world, allow the migration dialog to finish and then confirm the following smoke tests:

- Actor and item sheets load without errors, with nested items (ammo, specials, etc.) behaving as expected.
- Weapon and psychic attack workflows (attack rolls, damage rolls, and chat messages) continue to function.
- Release-note driven migrations complete successfully on first launch.
- Automatic and manual active effects tick correctly when turns advance.

If any of these checks fail, please open an issue with logs and reproduction steps so the compatibility fix can be expanded.

## Install
 - Go to the setup page and choose _Game Systems_.
 - Click the _Install System_ button, and paste in this [manifest link](https://github.com/MortarionUA/rogue-trader-3rd-vtt/releases/download/0.1.1/system.json)
 - Create a Game World using the "Rogue Trader 3rd Edition" system.

## Links
  - [Foundry VTT](https://foundryvtt.com/)
  - [Dark Heresy 2nd Edition Rules](https://www.drivethrurpg.com/browse/pub/54/Cubicle-7-Entertainment-Ltd/subcategory/179_21610/Dark-Heresy-Second-Edition)

## Screenshots

| ![Character Sheet](.github/char_sheet.png)   | ![Weapon Sheet](.github/weapon_sheet.png) |
|:---------------------------------------------|:---:|
| ![Attack Prompt](.github/attack_prompt.png)  | ![Damage Chat](.github/damage_chat.png) |


### Thanks
- First and foremost author of the original [Dark Heresy 2](https://github.com/mrkeathley/dark-heresy-2nd-vtt/tree/main) system by mrkeathley
- Also author of [Rogue Trader 2](https://drive.google.com/drive/folders/1jzXQay3PSbPVBAATmuqPLHBvrghhq3bQ?usp=drive_link) unofficial update 

## License
[GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/)
