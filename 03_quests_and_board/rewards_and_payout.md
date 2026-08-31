---
layout: default
title: Rewards & Automatic Payout Split
parent: Quests & Quest Board
nav_order: 4
---

# Rewards & Automatic Payout Split

Rewarding adventurers for completed contracts is streamlined with **DnD Guildhall's** automated **Reward Dialog** (`RewardDialog`), which calculates equal currency shares and deposits coins directly onto character sheets.

---

## 1. Types of Contract Rewards

Contracts can offer two categories of rewards:

- **Currency Rewards:** Exact numerical amounts of Platinum (`PP`), Gold (`GP`), Silver (`SP`), and Copper (`CP`) coins.
- **Item Rewards:** Linked equipment, weapons, magic items, potions, and scrolls attached directly to the contract.

---

## 2. The Payout Rewards Dialog (`RewardDialog`)

When a contract is completed, the Game Master can distribute the coin reward with automated math:

1. Open the contract in the **Quest Viewer**.
2. Click the **"Payout Rewards"** button in the header toolbar.
3. The **Reward Dialog** opens, displaying:
   - **Total Bounty:** The full currency reward listed on the contract.
   - **Party Member Selection:** A list of all party characters with toggle checkboxes.
   - **Calculated Split per Character:** The exact coin share calculated for each selected party member.
4. Check or uncheck specific characters to adjust who receives a share of the payout.
5. Click **"Distribute Rewards"**.

---

## 3. Direct Character Sheet Deposit

Upon confirming the payout dialog:

- **Automated Currency Deposit:** The module directly increments the currency values (`system.currency.pp`, `gp`, `sp`, `cp`) on each selected actor document in your Foundry world.
- **Audit Notification:** A confirmation message is posted, verifying how many coins were credited to each individual adventurer.
- **Zero Math Errors:** Eliminates manual bookkeeping errors or forgotten coin distributions at the end of a session.

---

## 4. Distributing Item Rewards

Item rewards attached to the contract can be awarded directly during the session:

- Clicking on an item card in the Quest Viewer opens its full Foundry item sheet.
- The Game Master can drag the item directly from the Quest Viewer or the linked document into a player character's inventory tab.

---

> **Tip for Game Masters:**
> The payout split handles remainders cleanly so no copper piece is lost when dividing odd amounts among uneven party sizes!

