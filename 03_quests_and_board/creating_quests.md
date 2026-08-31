---
layout: default
title: Creating Quests & Quest Editor
parent: Quests & Quest Board
nav_order: 2
---

# Creating Quests & Quest Editor

The **Quest Editor** (`quest-sheet`) provides Game Masters with a dedicated sheet for crafting detailed contracts, configuring rewards, setting required ranks, and embedding private encounter notes.

---

## 1. Creating a New Contract

You can initiate quest creation from two convenient locations:

1. **From the Questboard:** In the active guild's **"Quests"** tab, click **"+ Create Quest"** in the top action header.
2. **From the Quest Sidebar:** Open the right Quest Sidebar tab and click **"+ Create Quest"** in the top directory header.

Upon clicking, Foundry opens a new Quest Editor sheet.

---

## 2. The 2x2 Header Matrix

The top section of the Quest Editor features a structured 2x2 configuration matrix:

- **Issuer:** The patron, merchant, commander, or organization issuing the contract (e.g. *"Captain Varis of the City Watch"*).
- **State:** The initial lifecycle status of the quest (*Posted*, *Accepted*, or *Completed*).
- **Guild Affiliation:** A dropdown selector allowing you to assign the contract to any created guild or designate it as an unassigned global **World Quest**.
- **Required Rank:** A dynamic dropdown listing the configured rank hierarchy of the chosen guild (e.g. *Copper*, *Silver*, *Gold*, *Platinum*, *Diamond*). Selecting a rank marks the contract as restricted to adventurers of that tier or higher.

---

## 3. Rewards Configuration

Directly beneath the header matrix, you can define the tangible rewards for completing the contract:

### A. Coin Rewards
Enter exact numerical currency amounts into the four denomination inputs:
- **PP:** Platinum Pieces
- **GP:** Gold Pieces
- **SP:** Silver Pieces
- **CP:** Copper Pieces

### B. Item Rewards
- **Drag-and-Drop Items:** Drag weapon, armor, potion, scroll, or custom item documents directly from Foundry's Items Directory or Compendiums into the item drop area.
- **Linked Display:** Assigned items appear as interactive badges showing their official icon, name, and quantity.

---

## 4. Rich Text Content & GM Secrets

The body of the Quest Editor is divided into three distinct content areas:

### A. Public Briefing (Description)
A full ProseMirror rich text editor where you write the publicly visible contract details:
- Background story and mission briefing.
- Primary and secondary mission objectives.
- Formatting tools for bold headings, bullet points, and flavor text.

### B. Private GM Notes
A dedicated rich text editor whose contents are **strictly hidden from players**:
- Behind-the-scenes plot twists and NPC motivations.
- Trap DCs, secret password clues, and alternate resolution paths.
- Encounter strategies and difficulty scaling tips.

### C. GM Entity Links & Attachments
A drop zone allowing Game Masters to link campaign resources directly to the quest:
- Drop target scenes, monster/NPC actor sheets, journal entries, rollable tables, or loot containers.
- Clicking any attached link during play instantly opens that document without needing to search through Foundry's directories.

---

> **Tip for Game Masters:**
> All changes in the Quest Editor save automatically upon closing or submitting the sheet. Once saved, the contract immediately appears on the corresponding guild board and in the Quest Sidebar!

