---
layout: default
title: Creating & Configuring Custom Tabs
parent: Rules & Custom Tabs
nav_order: 3
---

# Creating & Configuring Custom Tabs

The **Custom Tabs** system in **DnD Guildhall** allows Game Masters to expand the Guildhall interface with entirely new, dedicated navigation tabs tailored to their campaign's specific lore and mechanics.

---

## 1. Custom Tab Possibilities

Custom tabs can turn your Guildhall into a specialized faction hub:

- **Hall of Fame:** Memorialize fallen heroes, document legendary contract completions, and display guild trophies.
- **Guild Crafting & Workshop:** Document specialized crafting recipes, magical forge upgrades, and guild alchemist formulas.
- **Allied Factions & Diplomacy:** Detail relationships with city guards, merchant cartels, nobility, or rival guilds.
- **Stronghold Upgrades:** Track chapterhouse facilities, library research bonuses, barracks capacity, and defense fortifications.

---

## 2. Managing Tabs in Settings

To configure the guild navigation tabs:

1. Open the Guildhall and click the **"Settings"** tab (gear icon, visible to the Game Master).
2. Navigate to the **"Tabs"** configuration panel.
3. **Default Tab Controls:**
   - **Toggle Visibility:** Enable or disable standard tabs (*Members*, *Quests*, *Rules*) if your faction doesn't use them.
   - **Rename Standard Tabs:** Customize tab names to match your world flavor (e.g. rename *Quests* to *"Bounties"*, or *Members* to *"Crew"*).
4. **Create a New Custom Tab:**
   - Click **"+ Add Custom Tab"**.
   - Enter the **Tab Label** (e.g. *"Hall of Fame"*).
   - Choose a **Tab Icon** (a FontAwesome class like `fas fa-trophy` or a custom SVG/image file path).
   - Click **"Save"**.
5. The new tab appears immediately in the Guildhall's top navigation bar, styled with an enlarged (+30% scaled) icon for clear visibility.

---

## 3. Adding Content Inside Custom Tabs

Custom tabs utilize the modular section architecture:

1. Click on your newly created custom tab in the navigation bar.
2. Click **"+ Add Section"** to create a content block.
3. Provide a section headline and icon.
4. Click the **Edit** icon on the section to open the **Rule Editor** (`GuildhallRuleEditorSheet`).
5. Compose rich text descriptions, lore entries, formatting tables, and clickable Foundry document links.
6. Click **"Save Changes"**.

---

## 4. Reordering & Deleting Custom Tabs

- **Navigation Order:** Tabs can be reordered in the Settings panel to control their display sequence.
- **Deleting Tabs:** In the Settings panel, click the trash can icon next to a custom tab to remove it along with all contained sections after confirming the prompt.

