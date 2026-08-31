---
layout: default
title: Guild Ranks & Advancement Deeds
parent: Rules & Custom Tabs
nav_order: 1
---

# Guild Ranks & Advancement Deeds

The **Rules** tab in **DnD Guildhall** showcases the guild's hierarchy through modern, responsive 480px rank cards. This provides players with a transparent progression path, detailing the exact deeds and milestones required to achieve promotions.

---

## 1. The 480px Rank Cards Grid

Inside the **Rules** tab, all configured guild ranks are presented in a responsive grid:

- **Visual Rank Cards:** Each card features a colored header badge, custom border accent matching the rank's color code, and a formatted rich text description area.
- **Player Accessibility:** Players can inspect every rank tier to review the responsibilities, perks, and promotion requirements associated with that title.

---

## 2. Default Rank Tiers

By default, newly created guilds initialize with five established rank tiers:

| Rank | Default Color | Tier & Description |
| :--- | :--- | :--- |
| **Copper** | `#b87333` | Novices, initiates, and probationers performing basic tasks. |
| **Silver** | `#c0c0c0` | Proven adventurers with solid field experience and trusted status. |
| **Gold** | `#ffd700` | Elite veterans undertaking high-stakes, perilous contracts. |
| **Platinum** | `#e5e4e2` | Renowned guild champions and tactical squad leaders. |
| **Diamond** | `#b9f2ff` | Legendary figures, high commanders, and grandmasters of the order. |

---

## 3. Editing Rank Requirements & Perks

Game Masters can customize the text on any rank card:

1. Open the **"Rules"** tab in the Guildhall window.
2. Locate the rank card you want to modify.
3. Click the **Edit** icon on the card to open the **Rule Editor** (`GuildhallRuleEditorSheet`).
4. Enter the promotion criteria and benefits using the full ProseMirror rich text editor:
   - **Advancement Milestones:** Specify required deeds (e.g. *"Complete 5 Silver-tier bounties and gain the endorsement of an Officer"*).
   - **Guild Privileges:** Document unlocked benefits (e.g. *"Free lodging in guild chapterhouses, 10% discount on enchanted equipment"*).
   - **Responsibilities:** Outline duties expected of members holding that rank.
5. Click **"Save Changes"**. The updated rules immediately display on the rank card for all players.

---

## 4. Customizing the Rank Hierarchy in Settings

Game Masters can further modify the rank hierarchy via the guild's **Settings** tab:

- **Custom Rank Names:** Rename ranks to suit your campaign setting (e.g. *Apprentice*, *Journeyman*, *Adept*, *Archmage*).
- **Color Customization:** Choose custom HEX colors using the integrated color picker.
- **Adding / Removing Tiers:** Create additional intermediary ranks or trim the hierarchy down to fewer tiers.

