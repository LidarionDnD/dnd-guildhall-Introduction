---
layout: default
title: The 3-Column Quest Board Workflow
parent: Quests & Quest Board
nav_order: 1
---

# The 3-Column Quest Board Workflow

The **Quests** tab in **DnD Guildhall** organizes campaign contracts through an interactive, 3-column Kanban board. This structure provides a clear, visual lifecycle for every bounty, mission, and guild task.

---

## 1. The Three Contract Columns

The board categorizes contracts into three distinct workflow states:

1. **Posted (`posted`):** Open contracts pinned to the board, available for adventurers to review and accept.
2. **Accepted (`accepted`):** Active missions currently undertaken by the party.
3. **Completed (`completed`):** Successfully accomplished or archived contracts serving as the guild's historical record.

---

## 2. Interactive Quest Cards

Every contract on the board is represented by an interactive quest card displaying vital mission information at a glance:

- **Quest Title:** The primary name of the contract.
- **Required Rank Badge:** A badge showing the minimum rank tier needed to undertake the contract, highlighted in that rank's custom color.
- **Reward Summary:** Quick coin counters (Platinum, Gold, Silver, Copper) and linked reward item icons.
- **Brief Excerpt:** A preview snippet of the contract's public description.
- **Visibility Indicator (GM only):**
  - **Solid Eye (`fas fa-eye`):** The quest is visible to all connected players with observer access.
  - **Hollow Eye (`far fa-eye`):** The quest is restricted to specific designated players.

---

## 3. Drag-and-Drop Workflow

Moving contracts through their lifecycle is handled through smooth drag-and-drop:

- **Reclassifying States:** Click and hold any quest card, then drag it into another column (*Posted*, *Accepted*, or *Completed*).
- **Visual Feedback:** While dragging, the card transitions to a semi-transparent 70% ghost preview to clearly indicate the drop target.
- **Sidebar Integration:** You can also drag quest cards directly from Foundry's right Quest Sidebar and drop them onto the board to move or reclassify them.
- **Real-Time Synchronization:** Any state change instantly updates across all connected clients via Foundry VTT Sockets.

---

## 4. Game Master Right-Click Context Menu

Right-clicking any quest card on the board opens a context menu with management actions:

1. **Edit Quest:** Opens the full Quest Editor sheet to adjust objectives, text, rewards, or requirements.
2. **Share Quest with Players:** Broadcasts the quest via socket; the parchment Quest Viewer pops open simultaneously on all authorized players' screens accompanied by a sound notification.
3. **Configure Visibility:** Opens a permission dialog to toggle access for individual players.
4. **Duplicate Quest:** Clones the contract page within the current guild.
5. **Transfer to another Guild:** Reassigns the contract to another registered guild or moves it into global World Quests.
6. **Delete Quest:** Prompts a confirmation dialog to permanently remove the contract.

---

## 5. Viewing Contracts

Left-clicking any quest card immediately opens the immersive, parchment-styled **Quest Viewer**, allowing players and Game Masters to read full mission briefings, inspect linked items, and claim rewards.

