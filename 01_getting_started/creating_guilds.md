---
layout: default
title: Creating & Managing Guilds
parent: Getting Started
nav_order: 3
---

# Creating & Managing Guilds

This guide explains how Game Masters can create new guilds, customize guild banners, configure player visibility, and delete guilds when no longer needed.

---

## 1. Creating a New Guild

1. Open the Guildhall from the left toolbar (Token Controls -> Parchment icon `fas fa-scroll`).
2. On the **Guilds Overview** dashboard, click **"+ Create Guild"** in the top right corner.
3. In the creation prompt, enter the desired **Guild Name** (e.g. *"Order of the Golden Griffin"*).
4. Click **"Create Guild"**.
5. The module automatically instantiates the guild document, initializes the default rank hierarchy and initial member group, and opens the new headquarters window.

---

## 2. Customizing the Guild Banner

You can customize the visual banner and adjust its positioning at any time:

1. Open the headquarters of the desired guild.
2. In the header area, click the **Edit Banner** button to select a new image file from your Foundry storage via FilePicker.
3. Click the **Adjust Banner** button to enter positioning mode:
   - Click and drag the image to adjust its horizontal and vertical alignment.
   - Use the zoom slider to scale the banner.
4. Click the checkmark button to save the banner positioning.

---

## 3. Player Visibility & Permissions

By default, newly created guilds become visible to players once they are granted `OBSERVER` ownership through Foundry's permission system:

- **Default Ownership:** Can be configured to `OBSERVER` (all players see the guild) or `NONE` (hidden by default).
- **Player-Specific Checkboxes:** The Game Master can toggle visibility for individual players (e.g. giving access to specific party members while hiding it from others).
- **Full Visibility Indicator:** When all players have observer access, the guild card on the dashboard displays a **solid eye** (`fas fa-eye`).
- **Partial Visibility Indicator:** When only specific players have access (e.g. a secret thieves' guild known only to the rogue), the guild card displays a **hollow eye** (`far fa-eye`).
- **Hidden Guilds:** Players without permission will not see the guild card on the dashboard or in the Quest Sidebar.

---

## 4. Deleting a Guild

When a guild is disbanded or permanently removed from your campaign:

### Method 1: Via Guild Settings
1. Open the guild headquarters.
2. Navigate to the **"Settings"** tab and scroll to the bottom **"Danger Zone"**.
3. Click **"Permanently Delete Guild"**.
4. Confirm the safety dialog prompt.

### Method 2: Via Quest Sidebar
1. Open the right **Quest Sidebar** (`fas fa-scroll`).
2. **Right-click** the header of the guild you wish to remove.
3. Select **"Delete Guild"** from the context menu.
4. Confirm the deletion prompt.

> **Caution:**
> Deleting a guild permanently removes its journal entry and all contained member assignments, groups, ranks, and contracts. World Quests (unassigned contracts) remain unaffected.

