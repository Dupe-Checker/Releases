# Hypixel Skyblock Dupe Checker (ChatTriggers Module)

## Overview
The **Hypixel Skyblock Dupe Checker** is a **ChatTriggers** module designed to help players detect duplicated (duped) items in Hypixel Skyblock. By analyzing item metadata directly in your inventory, the module helps prevent the handling of duped items, which could result in account penalties.

## Features
- **Real-time Inventory Scanning**: Automatically checks items in your inventory for potential duplication.
- **Customizable Alerts**: Receive notifications based on detected dupe patterns.
- **Lightweight & Efficient**: Runs smoothly with ChatTriggers for minimal impact on performance.

## How It Works
The module checks for item metadata issues such as:
- Invalid UUIDs.
- Suspicious item properties (e.g., impossible enchantment levels, incorrect rarity).
- Known dupe patterns.

It then notifies the player if any potentially duped items are detected, helping you avoid the risk of penalties from Hypixel Skyblock.

## Installation

### Requirements
- Minecraft 1.8.9 (Optimized for Hypixel Skyblock)
- ChatTriggers mod (installed in your Minecraft mods folder)
- Dupe-Checker .jar module

### Steps
1. **Install ChatTriggers**: Download and install [ChatTriggers](https://www.chattriggers.com/) if you don't have it already.
2. **Install the Module**:
   - Place the jar into your mods folder then open Hypixel and type `/ct import dupeChecker` to install the module from ChatTriggers.
3. **Reload ChatTriggers**: After installation, type `/ct load` to reload all modules and enable the Dupe Checker.
   
## Commands
- `/checkdupes` — Manually scan your inventory for duplicated items.
- `/checkdupes help` — Displays help information for the module.
- `/checkdupes toggle` — Enable or disable automatic scanning of new items entering your inventory.

## Usage Example
1. Log into Hypixel Skyblock.
2. The module will automatically scan your inventory whenever you add or inspect new items.
3. Type `/checkdupes` if you'd like to manually trigger an inventory scan.

## Development & Contributing
This module is open source, and contributions are welcome! To contribute:
1. Fork this repository.
2. Clone your fork locally and create a new branch for your feature or bug fix.
3. Once done, submit a pull request explaining your changes.


## Disclaimer
This ChatTriggers module is **unofficial** and is not endorsed by Hypixel or Mojang. Use at your own risk. Detection of duped items is based on best-known patterns and does not guarantee accuracy.
