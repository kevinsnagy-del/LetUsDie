# Changelog

## 0.9.10-beta
- The automatic escalator ride also runs outside a party.
- Enemy counts skip a mid boss's hidden spare pawns and enemies that are already gone.

## 0.9.9-beta
- For the LET IT DIE update of November 2026 (game 5.0.6). Needs Mod Drive 9000 1.4.4.
- New option: **Posture bars over allies** (with Heavenly Designs). Health bars over allies are on by default.
- The co-op sync check also compares boss variants and events, so a mismatch shows in the log.

## 0.9.8-beta
- Everyone needs this version: players on an older one cannot join (the network format changed).
- Needs Mod Drive 9000 1.4.2.
- **Fixed: members did not get the host's floor.** A floor record bigger than 16 KB arrived damaged, so the member built its own floor instead: other enemies (on POSTMORTEM's first floors, level-60 enemies hitting very hard), other materials and chests, kills that did not match, and an "enemy nearby" lock on the pause menu. It could also freeze or crash the member's game on arrival.
- Fixed: some of a member's hits never reached the host's enemies.
- Fixed: on the member's screen, every hit was counted twice.
- Items picked up from the floor disappear for the whole party.
- Teammates walk and run instead of sliding around.
- A teammate's body changes less often (it used to be rebuilt on every item use, showing it without gear for a moment).
- Teammates' bodies are hidden while you ride an elevator or escalator.
- Your own map ping reads "Your marker" instead of "You".
- A room whose host left is listed again at once with the new host (it used to be missing from the room list for up to 5 minutes).
- The live party panel editor uses the game's own menu art.

## 0.9.7-beta
- Everyone needs this version: players on an older one cannot join (the network format changed).
- Needs Mod Drive 9000 1.4.1.
- **Fixed: POSTMORTEM floors were different for every player.** The floor layout was too big to send and was skipped without a word; now everyone gets the host's floor.
- Fixed: joining a room could crash (a floor record cut in the middle of a character). A member who rejoins gets the floor again, and a member whose host leaves the floor follows to the hub instead of being sent to the title.
- **Sync check:** every machine compares what must match (the floor layout, enemies, chests, the POSTMORTEM run) and writes SYNC MISMATCH to the log when something differs; a different floor layout is also shown on screen.
- **Enemies are run by the host:** everyone sees the same enemy animations and guards (members' copies only play what the host's enemies do).
- Teammates' paired moves and finishers (grabs, stomps, back drops, carries, gore finishes), eating, healing, doors and levers are shown on their body.
- Items and mines a teammate throws or sets down are shared.
- Solo Shelter cannot be used in a party (the game's own "cannot be used"). The host's Tryptamine D takes the whole party home.
- **Multiplayer menu:** a room opens a page in the game's own style with the room's rules and every player's real rank card; a listed room shows a summary with Join / Back first. Your own room reads "(your room)" and its button says Details.
- New: **Edit the party panels live** (Let Us Die settings): shows sample members and lets you move and size the panels with the same controls as DeatHUD's live editor.

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
