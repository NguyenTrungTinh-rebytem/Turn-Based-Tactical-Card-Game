# Turn-Based-Tactical-Card-Game/TurnBased-BattleEngine-CPP
Turn-based RPG Battle Engine in C++20 and Raylib. Built with OOP, Design Patterns, and Smart Pointers for DSA & OOP Course.
## ⚔️ Gameplay Mechanics
- **Grid-Based Combat (4x6):** Strategic positioning and movement.
- **Link Arrow System:** Inspired by Yu-Gi-Oh Link Summoning. Connect hero orientation arrows to unlock powerful card combos and formation mechanics.
- **Linked Movement Chain:** Moving a linked unit pushes/pulls adjacent linked allies. Collision with obstacles snaps the link and triggers the `Disrupted` debuff.
- **Deckbuilding Action System:** Slay the Spire inspired card draw/discard loop with Unique Hero Cards, Action Cards, and Item Cards.

## 🛠️ Architecture & Technical Highlights
- **C++20 Features:** Concepts, Smart Pointers (`std::unique_ptr`, `std::shared_ptr`), Ranges.
- **Design Patterns:** Command Pattern (Card Execution & Undo), Observer Pattern (Link Status Monitoring), Factory Method (Card/Monster Generation).
- **Data Structures:** Graphs & BFS for Link Chain Movement, Stacks for Turn Undo, Priority Queues for Speed-based Turn Ordering.
