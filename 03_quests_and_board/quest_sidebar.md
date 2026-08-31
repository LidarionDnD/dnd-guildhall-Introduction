---
layout: default
title: The Dedicated Quest Sidebar
parent: Quests & Quest Board
nav_order: 5
---

# The Dedicated Quest Sidebar

The **Quest Sidebar** (`quest-sidebar-tab`) adds a dedicated tab directly into Foundry VTT's primary right sidebar navigation, giving players and Game Masters instant access to all contracts without opening the main Guildhall window.

---

## 1. Sidebar Navigation & Access

- **Sidebar Tab Icon:** Located in Foundry's right sidebar alongside Chat, Combat, Actors, and Journals, represented by a parchment scroll icon (`fas fa-scroll`).
- **Always Accessible:** Allows players to track their active objectives while simultaneously managing character sheets, combat turns, or map exploration.

---

## 2. Level 1: Guild Accordions & World Quests

Contracts are organized into top-level collapsible groups:

- **Frosted Glass Styling:** Each guild accordion is styled with modern semi-transparent frosted glass headers with backdrop blur effects.
- **Header Elements:** Shows the guild icon, guild name, and total contract count badge.
- **World Quests Section:** A dedicated category for global contracts not tied to a specific guild organization.
- **Guild Right-Click Context Menu:**
  - **Enter Guild:** Opens the main Guildhall window and switches directly to that guild's headquarters.
  - **Delete Guild (GM only):** Prompts a safety dialog to permanently delete the guild.

---

## 3. Level 2: State Subgroups

Inside each guild accordion, contracts are divided into three collapsible state groups:

- **Posted:** Open contracts available for acceptance.
- **Accepted:** Ongoing quests undertaken by the party.
- **Completed:** Finished and archived contracts.
- **Status Counts:** Each state header displays the exact number of contracts in that category.

---

## 4. Quick-Hover Tooltips & Quest Cards

- **Interactive Quest Cards:** Display contract titles and colored rank badges.
- **Parchment Tooltip Preview:** Hovering the mouse over any quest card immediately displays an enlarged parchment pop-up containing the public briefing, required rank, and rewards preview without needing to open the full sheet.
- **Opening Contracts:** Left-clicking a card opens the full Quest Viewer.
- **Drag-and-Drop:** Drag quest cards between state groups, across different guilds, or directly onto the main Guildhall board.

---

## 5. Global Search & Directory Tools

The top header of the Quest Sidebar provides quick management controls:

- **Real-Time Search Bar:** Instantly filters the contract tree across all guilds as you type.
- **Expand All / Collapse All Button:** A single button toggle that expands all guilds and state categories at once or collapses them down into compact headers.
- **Create Quest Button (GM only):** Quickly opens a fresh Quest Editor sheet to draft new global or guild contracts on the fly.

