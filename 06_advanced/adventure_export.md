---
layout: default
title: Adventure Compendium Export & Import
parent: Advanced Features
nav_order: 1
---

# Adventure Compendium Export & Import

**DnD Guildhall** features native integration with Foundry VTT's **Adventure Compendium** architecture (`adventure-integration.js`), allowing Game Masters and commercial content creators to package entire guildhalls, quest networks, and linked campaign assets into distributable adventure packs.

---

## 1. How Adventure Packaging Works

When exporting a guild into an Adventure document, the module automatically packages:

- **Guild Journal Structure:** Guild title, banner path, positioning flags, trust rating, and custom tab configurations.
- **Roster & Hierarchies:** Configured member groups and rank hierarchies.
- **Rules & Custom Sections:** All custom rule sections, custom icons, and rank advancement deeds.
- **All Embedded Contracts:** All quest pages categorized into their respective workflow states (*Posted*, *Accepted*, *Completed*).
- **Linked Dependencies:** Attached scenes, monster actors, NPC sheets, magic items, and referenced journal entries.

---

## 2. Exporting a Guild via Drag-and-Drop

1. Create or open an **Adventure** document in Foundry VTT's Compendium Packs tab (using the native Adventure Builder).
2. Open the Guildhall or Guilds Overview dashboard.
3. Drag the desired **Guild card** or **Quest card** directly into the Adventure Builder window.
4. The module intercepts the drop event and automatically adds the Guild Journal and its complete folder hierarchy into the Adventure bundle.
5. **Dependency Resolution:** The module scans all quest briefings, private GM notes, and attachment links for `@UUID` references, pulling linked scenes, actors, items, and rollable tables into the Adventure pack automatically.
6. A notification confirms the successful addition of the guild and the count of resolved dependencies.

---

## 3. Custom Adventure Sheet Badges

When viewing an Adventure document that contains guildhall data:

- The Adventure sheet displays a custom **Guildhall Badge** indicating the number of packaged guilds (e.g. *1 Guild* or *3 Guilds*).
- Displays included quest counts and linked document categories.

---

## 4. Importing into a Fresh Campaign World

When importing an Adventure compendium pack into a new Foundry world:

1. Open the Adventure in the Compendium tab and click **"Import Adventure"**.
2. Foundry instantiates the journal entries, actors, items, and scenes into the world.
3. **DnD Guildhall** detects the imported guild documents and instantly initializes the guildhall dashboard, quest boards, and Quest Sidebar entries without requiring manual setup.

