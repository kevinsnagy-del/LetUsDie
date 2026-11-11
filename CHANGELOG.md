# Changelog

## 0.9.4-beta
- Heaven rush arenas (several bosses in a row): the host now decides when the next boss comes in, so every player sees the same one at the same time.
- **Chests and loot boxes are shared now.** A chest one player opens opens for everyone, and a box one player breaks breaks for everyone (it worked in neither direction before). Any player can open them, not only the host.
- In POSTMORTEM only the player who opens a chest gets its reward; for the others the chest just disappears.
- Heaven boss arenas: the opening scene at the Uncle Death statue now plays for the whole party.
- POSTMORTEM no longer re-opens escalators that co-op keeps closed (a follower could ride off alone).
- Everyone needs this version: players on an older one cannot join (the network format changed).

## 0.9.3-beta
- Less work every frame while you are not in a co-op room (the Steam connection is checked 5 times a second instead of every frame).

## 0.9.2-beta
- **Bosses and mid-bosses scale with the party one for one**: x2 HP with two players, x4 with four (ordinary enemies keep x1.6 / x2.8). The party scaling multiplies the difficulty's HP, so each player still feels the difficulty they chose.

## 0.9.1-beta
- Supports the LET IT DIE update of 2026-10-20 (Steam build 25923506).

## 0.9.0-beta (first public beta)
- Steam lobbies from the pause menu's MULTIPLAYER button.
- Peer avatars and character exchange; the follower uses the host's floor layout and enemies.
- No friendly fire (switchable), boss-door ready check, co-op notices and error codes.
