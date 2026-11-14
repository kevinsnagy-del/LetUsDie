# Changelog

## 0.9.6-beta
- **Shared world.** Things that happen in one player's game now happen in everyone's: level mines and explosives (stepped on, armed, exploded), fire and gasoline, breakable objects, the mines you set down and the mushrooms and items you throw. Crates shatter for everyone (each player still gets their own loot). A teammate's copy of a thrown item vanishes when it lands, so only the thrower can pick it up again; coin mushrooms are not copied.
- Damage from these shared things counts once (on the host), not once per player.
- Join your party: a member rides the elevator and is sent straight to the host's floor.
- Fixed: every YES in the ready check counted as a decline, and a dead or spectating teammate held the ready check forever.
- Escalators work in a party, and nobody is thrown out of the session during an escalator ride.
- A room handed over to a new host is listed again under the new owner.
- Messages from another floor are ignored (an old enemy state could warp or kill an enemy on the new floor).
- Security: the game only accepts network connections from members of your room.
- Everyone needs this version: players on an older one cannot join (the network format changed, and a version mismatch is shown on screen). Needs Mod Drive 9000 1.3.8 or newer.

## 0.9.5-beta
- Slow motion: a bullet-time mushroom (Slowmungus, Cateye Shroom) one player eats now slows the whole party on that floor, for the same time. Before, only the eater's game slowed down.
- Slow motion: while teammates are on the host's floor, the host's game no longer slows down for kill cams and scripted slow motion (enemy positions follow the host's clock, so a slowed host put them out of step for everyone else).

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
