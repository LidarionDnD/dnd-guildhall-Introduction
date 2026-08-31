---
layout: default
title: Interface Overview & Navigation
parent: Getting Started
nav_order: 2
---

# Interface Overview & Navigation

**DnD Guildhall** seamlessly blends into the Foundry VTT interface. This tour walks you through each window, toolbar button, and interface panel provided by the module.

---

## 1. The Scene Controls Button (Quick Access)

You can launch the Guildhall at any moment from Foundry's left control toolbar:

1. Select the **Token Controls** group (the character portrait icon in the left toolbar).
2. Click the **Parchment Scroll** icon (`fas fa-scroll` – *Open Guildhall*).
3. The **Guilds Dashboard** (or currently selected active guild) will immediately render on your canvas.

---

## 2. The Guilds Dashboard (`guildhall-overview`)

When no specific guild is selected or when browsing multiple factions, the Dashboard welcomes you with a high-level overview displaying all created guilds as cards in a responsive grid.

### Guild Card Components:
- **Guild Banner:** Visual image representing the organization.
- **Guild Name:** Official name of the organization.
- **Counters:** Real-time counters showing total enrolled members and active contracts.
- **Visibility Indicator (GM only):**
  - **Solid Eye (`fas fa-eye`):** The guild is visible to all connected players.
  - **Hollow Eye (`far fa-eye`):** The guild is only visible to specific designated players.
- **Clicking a Card:** Instantly enters the active guild headquarters.

---

## 3. The Active Guild Interface (`guildhall-active`)

Upon entering a guild, the view switches to its full headquarters interface:

### A. Header Section
- **Guild Banner:** Top banner with image picker and drag-positioning controls.
- **Guild Title:** Organization title styled in customized typography.
- **Trust Status Badge:** Real-time color-coded badge indicating the party's standing with the guild (e.g. *Hostile*, *Suspicious*, *Neutral*, *Friendly*, *Allied*).
- **"All Guilds" Button:** Returns to the top-level overview dashboard.

### B. Tab Navigation
The interface is structured into modular, switchable tabs:
- **Members (`👥 Members`):** Enrolled character roster, departmental group breakdowns, rank assignments, and actor drag-and-drop.
- **Quests (`📜 Quests`):** 3-column Kanban quest board (*Posted*, *Accepted*, *Completed*) with drag-and-drop reordering.
- **Rules (`⚖️ Rules`):** Guild hierarchy cards (480px responsive cards), advancement deeds, and custom regulation sections.
- **Custom Tabs:** GM-created custom tabs for lore, allied factions, crafting recipes, or hall of fame.
- **Settings (GM only):** Navigation configuration, 21 color themes, trust levels, and danger zone.

---

## 4. The Dedicated Quest Sidebar (`quest-sidebar-tab`)

In addition to the main window, **DnD Guildhall** integrates a dedicated tab directly into Foundry VTT's right sidebar:

- **Dedicated Tab Icon:** Parchment scroll (`fas fa-scroll`) positioned alongside Chat, Combat, Actors, and Journals.
- **Level 1 Guild Accordions:** Each guild forms a collapsible group styled with semi-transparent frosted glass headers.
- **World Quests:** Dedicated section for global, unassigned world contracts.
- **Level 2 State Subgroups:** Compact categories for *Posted*, *Accepted*, and *Completed* contracts.
- **Real-Time Search Bar:** Instant filtering across all guilds and contract titles.
- **"Expand All / Collapse All" Button:** Toggles all guild and state trees with one click.
- **Quick-Hover Tooltips:** Hovering over any quest card displays an instant parchment pop-up showing the full brief, required rank, and rewards without opening a separate window.

---

> **Tip for Game Masters:**
> The active Guildhall window and the Quest Sidebar stay synchronized in real time! Moving a quest in the sidebar immediately updates the board in the Guildhall window and vice-versa.

