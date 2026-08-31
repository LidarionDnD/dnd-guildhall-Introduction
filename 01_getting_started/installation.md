---
layout: default
title: Installation & Requirements
parent: Getting Started
nav_order: 1
---

# Installation & Requirements

Follow this guide to install, activate, and configure **DnD Guildhall** in your Foundry VTT environment.

---

## 1. System Requirements

To ensure optimal performance and complete feature availability, verify that your Foundry VTT setup meets the following requirements:

| Component | Recommended Version | Notes |
| :--- | :--- | :--- |
| **Foundry VTT** | **Version 14** (or compatible from V13+) | Utilizes modern `ApplicationV2`, `TypeDataModel`, and native socket communication. |
| **Game System** | **`dnd5e`** (D&D 5e / D&D 5.5e 2024+ rules) | Integrated with standard D&D 5e character sheets, currency attributes, and party actors. |
| **Web Browser** | Chrome, Edge, Firefox, Brave (latest) | Hardware acceleration recommended for CSS backdrop blur effects and glass styling. |

---

## 2. Installation Methods

### Method A: Manual Installation
1. Download or clone the `dnd-guildhall` module repository.
2. Place the `dnd-guildhall` directory into your Foundry user data folder at:
   ```text
   <FoundryData>/Data/modules/dnd-guildhall/
   ```
3. Ensure the folder contains `module.json`, `scripts/`, `styles/`, `templates/`, `languages/`, and `assets/`.
4. Restart Foundry VTT.

### Method B: Manifest URL Installation
1. Open Foundry VTT and navigate to the **"Add-on Modules"** tab on the setup screen.
2. Click **"Install Module"** at the bottom.
3. Paste the module's manifest URL into the **"Manifest URL"** field.
4. Click **"Install"**.

---

## 3. World Activation

1. Launch your D&D 5e game world as a Gamemaster.
2. Open the Game Settings menu via the gear icon in the right sidebar.
3. Click **"Manage Modules"**.
4. Locate **DnD Guildhall** and check its enable box.
5. Click **"Save Module Settings"**. Foundry VTT will reload your world with the module active.

---

## 4. Permissions & Security Overview

> **Important Note for Game Masters:**
> The module maintains strict separation between Game Master controls and Player permissions:
> - **Game Masters:** Full administrative access to create/delete guilds, edit quests, configure ranks, access private GM notes and links, distribute reward currency, and adjust visibility.
> - **Players:** View only guilds and contracts for which they have at least `OBSERVER` permissions. Players can accept, complete, and abandon quests from the Quest Viewer.
> 
> All player-initiated state transitions and window broadcasts are securely routed and validated through Foundry VTT Sockets.

