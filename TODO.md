# Bird Simulator — TODO / Open Questions

---

## 🔴 Pre-Production Blockers

_None. All blockers resolved._

---

## 🟢 V2 Backlog (Parked, Not Forgotten)

- [ ] Food caching mechanic (corvids, woodpeckers)
- [ ] Woodpecker class (drumming/excavation input design)
- [ ] Migration mechanic (multi-biome run architecture)
- [ ] Multiplayer / co-op
- [ ] Seasonal weather events (hurricanes, blizzards)
- [ ] Photo mode
- [ ] Daily seed / challenge runs
- [ ] Owls class (nocturnal lighting system)
- [ ] Shorebirds class (tidal mechanic)
- [ ] Waterfowl class (swimming locomotion state)
- [ ] Nintendo Switch port

---

## ✅ Resolved

- [x] **Hatchling/nestling phase** — Cut. Run begins at fledgling. Tighter gameplay, no tutorial phase needed.
- [x] **Switch target** — Deferred to post-launch port. Not a day-one platform.
- [x] **Starter species select** — Pokémon-style choice of 3 at session start: House Sparrow, American Robin, Rock Pigeon. All other species/classes unlock via milestones.
- [x] **Egg/chick count** — Species-accurate ranges confirmed, capped at 3 for gameplay clarity.
- [x] **Mate killed during breeding** — Second mate possible. Short window, high stamina cost. Rescue mechanic, not a mulligan.
- [x] **Run clock** — No clock, no UI timer. Purely environmental. "One game you can't speedrun."
- [x] **Death card design** — Dark Souls "YOU DIED" riff. Black and white, Sanrio-style font. Predation = "{SPECIES} LUNCH". Starvation = "VULTURE FOOD". Human threats: no message first occurrence — fade to black and white, silence. Subsequent human deaths show message.
- [x] **Corvid tool use mechanic** — Rhythm game (God of War style). Hold B near interactable object → button sequence → match it → mega stamina reward.
- [x] **Corvid tool use object list** — Full table defined: ant stick, car nutcracker, bird feeder lever, dumpster (with friends), steal from tourist, steal from hunter, scarecrow (false threat), shiny object (90% useless, 10% [SHINY OBJECT] achievement). See §06.
- [x] **Corvid NPC recruitment** — Tap B (caw) to recruit ambient corvids. Required for dumpster. Sequence complexity decreases with more crows present.
- [x] **Human type spectrum** — Tourist (harmless), Indigenous hunter (ambiguous, never visually signaled), trophy hunter (immediately lethal), poisoner/pest control (silent lethal), farmer (seasonal risk/reward).
- [x] **Scarecrow** — Threat border fires, no actual threat. Inert. The fear is the mechanic.
- [x] **Shiny object reward** — 1-in-10 triggers Dark Souls achievement overlay: [SHINY OBJECT] + small stamina bump. Other 9: stamina cost only. Crow happy regardless.
- [x] **Farmer ecology** — Full seasonal system: Spring (turned soil + broadcast seed, moderate threat), Summer (crop-edge insects, silent spray poison, high threat), Fall (grain spill, distracted farmer, low threat), Winter (barn access via tool use, cat risk, low threat).
