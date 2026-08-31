---
layout: default
title: Assigning Characters & Drag-and-Drop
parent: Members & Groups
nav_order: 1
---

# Assigning Characters & Drag-and-Drop

Enrolling characters in your guild takes full advantage of Foundry VTT's intuitive drag-and-drop system.

---

## 1. Adding Characters via Drag & Drop

1. Open the Guildhall from the left toolbar (`fas fa-scroll`) and select the desired guild.
2. Click the **"Members"** tab.
3. Open the **Actors Directory** in Foundry's right sidebar.
4. Click on an Actor (Player Character, NPC, or creature) and **drag it with your left mouse button** into the Guildhall window.
5. Drop the actor onto a specific group or into the general roster area.
6. The character instantly appears as a new member card with their token portrait, name, and default rank!

---

## 2. Supported Actor Types

- **Player Characters (PCs):** Visualized with their active token portrait, full character name, and assigned rank badge.
- **Non-Player Characters (NPCs):** Guild masters, quartermasters, scouts, and patrons can be managed alongside player characters.
- **Group Actors (D&D 5e Group Actors):** Automatically synchronized with D&D 5e group mechanics to avoid stale member references.

---

## 3. Member Cards & Sheet Access

Each member is represented by a responsive card:
- **Portrait & Name:** Clicking the name or image directly opens their full Foundry character sheet.
- **Rank Badge:** Displays the member's current guild rank with its assigned color code.
- **Reorganizing:** Drag a member card directly from one group to another to reassign them.

---

## 4. Removing Members from a Guild

To remove a character from the guild:

1. Hover over the member card of the character you wish to remove.
2. Click the red **trash can icon** (`fas fa-trash`) in the upper corner of the card.
3. Confirm the safety dialog prompt (*"Are you sure you want to remove this member?"*).
4. The character is removed from the guild roster. The actual Actor document in your world remains completely untouched.

---

## 5. Automated World Actor Cleanup

> **Background Architecture:**
> When an Actor is deleted from the world in Foundry's main directory, **DnD Guildhall** catches this event using the `deleteActor` hook. All references across guild rosters, member groups, ranks, and custom permissions are purged automatically, preventing broken links or orphaned UI elements.

