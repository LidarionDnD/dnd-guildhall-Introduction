---
layout: default
title: The Immersive Quest Viewer
parent: Quests & Quest Board
nav_order: 3
---

# The Immersive Quest Viewer

The **Quest Viewer** (`quest-viewer`) delivers an atmospheric, parchment-styled interface for inspecting contract details, managing player workflow actions, viewing rewards, and reviewing secret Game Master notes.

---

## 1. Visual Design & Theme Integration

The Quest Viewer is styled as an authentic fantasy contract scroll:

- **Theme Palette Integration:** The parchment tone, text hues, borders, and accent colors automatically adapt to the guild's active color theme (from the 21 available presets).
- **Typography & Layout:** Styled fantasy headers with clear visual hierarchy, legible body text, and full text selection and copying capabilities.

---

## 2. Header Information & Badges

The top section of the Quest Viewer presents key contract metadata at a glance:

- **Quest Title:** Large header displaying the contract's name.
- **Guild Affiliation:** Indicates which guild issued the contract or marks it as a global World Quest.
- **Required Rank Badge:** Highlights the necessary guild rank tier (e.g. *Gold Rank*) glowing in that rank's custom color.
- **Issuer:** The client, noble house, or commander who commissioned the contract.
- **State Badge:** Dynamic status indicator displaying *Posted*, *Accepted*, or *Completed*.

---

## 3. Player Actions

Players with observer access can interact directly with the contract based on its current state:

- **Accept Quest:** When a contract is in the *Posted* state, players can click **"Accept Quest"** to claim the mission. The state transitions to *Accepted*, moving the card on the board and notifying the Game Master via socket.
- **Complete Quest:** When an accepted contract is fulfilled, players can click **"Complete Quest"** to submit the contract for archival.
- **Abandon Quest:** If the party must withdraw from an active contract, clicking **"Abandon Quest"** returns the contract to the *Posted* column for others to claim.

---

## 4. Game Master Controls

Game Masters have access to administrative controls directly within the viewer toolbar:

- **State Buttons:** Instantly override and set the contract's state to *Posted*, *Accepted*, or *Completed*.
- **Lock / Unlock:** Clicking the padlock icon locks the contract, preventing players from changing its state or modifying its status.
- **Live Share:** Clicking **"Share Quest with Players"** broadcasts the Quest Viewer window live onto all authorized players' screens.
- **Payout Rewards:** Clicking the coin icon opens the automated **Reward Dialog** to split the contract's currency rewards equally among the party.

---

## 5. Body Content & GM Secrets

The main body of the Quest Viewer presents contract details in dedicated sections:

### A. Public Briefing
The full text briefing describing the contract background, objectives, guidelines, and lore.

### B. Private GM Notes (Collapsible)
A dedicated, secure section that is **strictly visible only to the Game Master**:
- Contains secret encounter mechanics, trap solutions, NPC secrets, and plot twists.
- Hidden completely from player view, even during live window sharing.

### C. GM Entity Links & Attachments
Clickable entity links placed by the Game Master:
- Provides one-click access to target battlemaps/scenes, NPC and monster actor sheets, journals, and rollable tables.
- Visible only to the Game Master for rapid in-game referencing.

### D. Rewards Section
Displays all currency denominations (PP, GP, SP, CP) alongside interactive item cards with tooltips and sheet links.

