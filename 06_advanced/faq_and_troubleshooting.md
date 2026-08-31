---
layout: default
title: FAQ & Troubleshooting
parent: Advanced Features
nav_order: 3
---

# FAQ & Troubleshooting

Find answers to common questions and practical solutions for troubleshooting **DnD Guildhall**.

---

## 1. Frequently Asked Questions (FAQ)

### Can I run multiple guilds simultaneously in one world?
Yes. You can create unlimited independent guilds. Each guild maintains its own custom banner, member roster, group divisions, rank hierarchy and quest board.

### How do World Quests differ from Guild Quests?
Guild Quests belong to a specific organization and appear on that guild's board. World Quests are unassigned global contracts that appear in the top-level **World Quests** section of the Quest Sidebar and are accessible across all factions.

### What happens when an Actor is deleted from Foundry?
**DnD Guildhall** listens to the `deleteActor` hook. When an actor is deleted from the world, the module automatically purges all references to that character across all guild rosters, groups, and rank assignments, preventing orphaned UI elements or database errors.

### Are private GM notes safe from player inspection?
Yes. GM Notes, GM Links, and encounter attachments are rendered exclusively on Game Master clients and are completely omitted from player views and live socket broadcasts.

### Does the module support D&D 5.5e (2024 rules)?
Yes. **DnD Guildhall** is fully compatible with Foundry VTT Version 14 and the `dnd5e` system (including the 2024 core rules update).

---

## 2. Troubleshooting Solutions

### Players cannot see a newly created guild or quest
- **Cause:** Document ownership is set to `NONE`.
- **Solution:** Right-click the quest card (or check guild settings) and verify that the default ownership is set to **Observer**, or check the individual player's access box.

### Drag-and-drop does not register when adding members or items
- **Cause:** Dragging from an unverified compendium or invalid DOM element.
- **Solution:** Ensure you are dragging directly from Foundry VTT's native **Actors Directory** (for members) or **Items Directory** (for rewards).

### Frosted glass headers look solid or lack backdrop blur
- **Cause:** Browser hardware acceleration or CSS backdrop filters are disabled.
- **Solution:** Enable hardware acceleration in your browser settings (Chrome, Edge, Firefox, Brave) and ensure your graphics drivers are up to date.

### Live Share does not open on player screens
- **Cause:** Sockets require an active Game Master session to validate and broadcast.
- **Solution:** Verify that a user with the **Gamemaster** role is logged in and connected to the world session.

### The UI does not reflect recently edited settings
- **Cause:** Stale browser stylesheet cache.
- **Solution:** Perform a hard refresh in your browser using **Ctrl + F5** (Windows/Linux) or **Cmd + Shift + R** (macOS).

