---
layout: default
title: Custom Rule Sections & Icons
parent: Rules & Custom Tabs
nav_order: 2
---

# Custom Rule Sections & Icons

Beneath the rank hierarchy, the **Rules** tab allows Game Masters to craft unlimited custom regulation sections to document guild bylaws, codes of conduct, and party agreements.

---

## 1. Practical Use Cases

Custom rule sections are ideal for documenting campaign guidelines:

- **Code of Conduct:** Expected behavior when representing the guild in public, rules on collateral damage, and treatment of prisoners.
- **Loot & Bounty Division:** Formulas for splitting dungeon treasure, handling quest reward remainders, and contributing to the guild treasury.
- **Guild Charter & History:** The founding lore of the organization, notable historic victories, and ancestral mottos.
- **Bounties & Disciplinary Actions:** Penalties for breaking guild rules, temporary suspensions, or bounty fines.

---

## 2. Adding a New Rule Section

1. Open the **"Rules"** tab in the Guildhall window.
2. Scroll to the bottom of the rules list and click **"+ Add Section"**.
3. In the section configuration dialog, enter:
   - **Section Title:** The headline for the rule category (e.g. *"Code of Conduct"* or *"Loot Division"*).
   - **Section Icon:** A FontAwesome icon class (e.g. `fas fa-gavel`, `fas fa-coins`, `fas fa-shield-alt`) or a custom SVG/Image file selected via Foundry's FilePicker.
4. Click **"Save"**. The new section block is created immediately.

---

## 3. Editing Section Content

To author or update the text of any rule section:

1. Click the **Edit** icon in the header of the rule section.
2. The **Rule Editor** (`GuildhallRuleEditorSheet`) opens with a full ProseMirror rich text editor.
3. Write your rules using rich text formatting, bulleted lists, numbered clauses, and clickable Foundry document links (e.g. linking to specific items or journal pages).
4. Click **"Save Changes"**. The formatted text renders live in the Guildhall.

---

## 4. Reordering & Deleting Rule Sections

Game Masters have complete control over section organization:

- **Move Up / Move Down:** Use the vertical arrow icons in the section header to reorder sections.
- **Edit Icon / Title:** Click the pen icon to change the title or icon of an existing section.
- **Delete Section:** Click the red trash can icon and confirm the prompt to remove the section and its contents.

