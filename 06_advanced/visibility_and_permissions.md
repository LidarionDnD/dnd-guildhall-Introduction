---
layout: default
title: Visibility Matrix & Permissions
parent: Advanced Features
nav_order: 2
---

# Visibility Matrix & Permissions

**DnD Guildhall** implements a granular, document-level security and visibility architecture to support diverse play styles, including secret factions, rogue-only underworld jobs, and tiered party access.

---

## 1. Document Ownership Hierarchy

The module leverages Foundry VTT's native document ownership system with tailored permissions:

| Ownership Level | Value | Role | Capabilities |
| :--- | :--- | :--- | :--- |
| **None** | `0` | Hidden | Guild or contract is completely invisible in the dashboard and Quest Sidebar. |
| **Observer** | `2` | Player Access | Can view guildheadquarters, read public briefings, and interact with workflow actions (Accept, Complete, Abandon). Private GM notes and administrative settings remain hidden. |
| **Owner** | `3` | Game Master | Full administrative access: create/delete guilds, edit contracts, access secret GM notes & entity links, adjust trust, distribute payouts, and configure themes. |

---

## 2. Granular Player Visibility Controls

Game Masters can adjust access on both a guild level and an individual quest level:

- **Default Ownership:** Sets the baseline visibility for all connected players (e.g. setting default to `OBSERVER` makes the contract public to the entire party).
- **Player-Specific Checkboxes:** Right-clicking any quest card and selecting **"Configure Visibility"** allows the Game Master to grant or revoke access for specific player accounts.
- **Visual Status Indicators (GM only):**
  - **Solid Eye (`fas fa-eye`):** The item is visible to all active players.
  - **Hollow Eye (`far fa-eye`):** The item is visible only to a subset of players.

---

## 3. Secure Socket Architecture

Player-driven workflow interactions (such as claiming a bounty or clicking *Accept Quest*) utilize Foundry VTT's socket event pipeline:

- **Server-Side Validation:** When a player changes a contract state in the Quest Viewer, a socket payload is emitted to the active Game Master client.
- **Permission Verification:** The GM client verifies the player's ownership rights before committing changes to the world database.
- **Live Broadcasts:** Legitimate state updates and live window shares are immediately synced to all authorized clients with zero risk of database corruption.

