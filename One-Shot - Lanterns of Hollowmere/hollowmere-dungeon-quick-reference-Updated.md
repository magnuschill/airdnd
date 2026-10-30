# The Lantern at Hollowmere — Dungeon Quick Reference
*D&D 5e (2014) • Level 2 featured PC (~12 HP) • Proposed homebrew dungeon mechanics*

## Route & Running Rules
**Cinder Row drain entrance → 1. Fog Drains → 2. Sallow Court Gate → 3. Cistern → 4. Ossuary Stair → 5. Dreamer's Sanctuary (beneath Marrow Mill).**

**Alternate:** Peacefully resolving Kathra opens the **Greywake Abbey ward-conduit → Room 4**, skipping Rooms 1–3 and granting the PC the blessing and ward knowledge described in **`hollowmere-combat-reference.md`**.

- **Checks:** DC 10 easy; DC 11–12 moderate; DC 14 challenging. **Never gate an essential clue or route behind one roll.** Failure costs time, causes a minor complication, or invites a different approach.
- **Low-HP safeguards:** Trap damage at most **1d4** per activation; no repeated unavoidable damage. Other party members deal with background threats abstractly until the PC selects one companion for Room 5.
- **Lantern principle:** Open flame or the warded lantern burns back concentrated fog. Reward recalling earlier investigation clues without a mandatory knowledge check.
- **Combat:** Enemy stats, turns, potions, companion abilities, and Kathra's blessing are in **`hollowmere-combat-reference.md`** (Combat QRef). Do not run the entire party on initiative.

---

## One-Glance Room Flow
`Cinder Row → [1 Fog: light lamps] → [2 Gate: negotiate / cutpurse] → [3 Cistern: Clear + Thermal to Basin, Foul to Drain] → [4 Stair: hold off Plaguebound] → [5 Dreamer: fight or reseal]`

`Greywake Abbey + Kathra at peace ─────────────────────────────────────────→ [4 Plaguebound Stair] → [5 Dreamer]`

**DM priorities:** Key information always gets through • Check failure changes approach, not access • Preserve PC spotlight • Consult Combat QRef for fights • Stop to let the PC select a companion at the stair.

---

## Room 1 — Fog Drains | Environmental Trap (5–8 min)
**Scene:** Sloping brick drains; three outlets vent sweet, dense fog; **two unlit vigil lamps**; a functioning entrance lamp; rusted grate and maintenance wheel at the far end.

**Goal:** Safely traverse the fog and open the grate.

| Player action / hazard | Mechanic / result |
|---|---|
| Recognize the role of lamps | **Automatic** from Wren's explanation; their flames repel fog |
| Study vent timing | **DC 10 Investigation:** notice alternating bursts; failure still reveals lamps as a safe option |
| Light unlit lamps / carry flame | **No check** with a viable flame source; clears a traversable path |
| Cross dense fog unprotected | **DC 11 WIS save:** failure = disoriented, stop near next outlet; **no damage**, can retry or light lamps |
| Open grate with maintenance wheel | **No check** |
| Force corroded grate instead | **DC 12 Athletics;** failure by 5+ = **1d4 bludgeoning** from snapped handle; wheel remains usable |

**Expected sequence:** Observe fog → light lamps or improvise fire → turn wheel → proceed. **Fail-forward:** Walking blindly causes delay, not a hard stop.

## Room 2 — Sallow Court Gate | Social or Combat (5–10 min)
**Scene:** A damp stone platform spans an underground watercourse; barricaded service gate; **three cutpurses**, with the party occupying the others if a fight starts.

**Goal:** Get through the gate (optionally win cooperation or information).

| Approach | Resolution |
|---|---|
| Pay toll | **5 gp** or comparable valuables |
| Persuade / intimidate / bluff | **DC 12 Persuasion / Intimidation / Deception** |
| Earned Phelaia's help earlier | **Automatic passage**; otherwise invoking her name can give **advantage** on a social check |
| Failed social roll | Larger demand, warning, or another tactic available; **not instant combat** |
| Fight | **One cutpurse actively fights the PC**; other thieves occupied by party; surrender/retreat possible |

**Combat QRef:** **“Sallow Court Cutpurse”** in `hollowmere-combat-reference.md` for stat block, tactics, 3-round beats, and morale.

**Exit:** Negotiation, surrender, or victory opens passage. A cooperative thief may warn of the cistern or aid allies later.

## Room 3 — Cistern of Three Waters | Water-Flow Puzzle (10–15 min)
**Scene:** Three elevated sources enter an old stone waterworks chamber: **Clear Spring** (cold, blue), **Thermal Flow** (boiling, orange), and **Foul Runoff** (stagnant, green). A central basin operates the exit-door float lock. Three two-position sluice levers redirect each source to either **Basin (B)** or **Drain (D)**.

**Goal:** Send **both the Clear Spring and Thermal Flow into the basin**, while diverting Foul Runoff to the drain. The fresh water dilutes the hot spring into a **clear, bubbling bath** that flushes away debris and lifts the exit float. Correct settings: **Clear = B; Thermal = B; Foul = D**. Pull the **main sluice** to test: the basin purges its old sludge, fills with clean, steaming water, the float rises, and the exit opens **without a roll**.

### Lever Feedback — All 8 Combinations (DM Only)
**Lever order: Clear / Thermal / Foul.** `B` = Basin, `D` = Drain. The PC can adjust any lever and test again indefinitely.

| Clear | Thermal | Foul | What happens when the main sluice opens | Exit? |
|:---:|:---:|:---:|---|:---:|
| D | D | D | All three flows bypass the basin; its level drops and the float stays down. | No |
| D | D | B | Green sludge fills the basin and clogs the float housing. | No |
| D | B | D | Only boiling water rushes in; thick steam rises, but the undiluted heat prevents the mechanism from settling. | No |
| D | B | B | Boiling flow churns with foul runoff, creating a scalding, murky mess that jams the float. | No |
| B | D | D | Cold, clear water washes away loose debris, but the flow is too weak to lift and hold the float. | No |
| B | D | B | Clear water turns cloudy green as runoff pours in; sediment catches in the float mechanism. | No |
| **B** | **B** | **D** | **Hot and cold streams mingle into a clear, bubbling pool. The surge flushes the basin, lifts the float, and unlocks the exit.** | **YES** |
| B | B | B | The bath begins to clear and bubble, but foul green runoff immediately muddies it and clogs the lock. | No |

**Note:** Three binary levers produce **8 unique settings**. There is **no limit on attempts**; even a ninth or later try can succeed.

### Checks, Hazards & Hints

| PC action | Mechanic / feedback |
|---|---|
| Look at the sources | **Automatic:** distinct cold/blue, boiling/orange, and foul/green streams; the basin is designed for flushing and refilling |
| Trace channels and levers | **DC 10 Investigation:** identify which lever controls each stream; on failure, testing still shows where they flow |
| Examine the basin lock | **DC 12 Investigation:** the float needs **enough clean combined flow** to rise; sludge clogs it and an undiluted thermal stream is too hot |
| Examine water properties | **DC 10 Nature:** hot water mixed with cool spring water creates a usable, cleansing bath; foul runoff must go elsewhere |
| Free a seized Foul lever (optional) | **DC 11 Athletics** or **DC 10 Investigation** to find its release pin; retries, leverage, or tools work; never permanently stuck |
| Test an **incorrect** arrangement with Thermal = B | **First hazardous activation only:** a poorly mixed scalding surge prompts **DC 11 DEX save**; failure = **1d4 fire**. The correct `B / B / D` setting is safe. Subsequent tests cause descriptive steam only |
| Test any other incorrect arrangement | No damage; narrate the precise water/float response above |

**DM hint ladder:** (1) Describe the cold spring, boiling stream, foul runoff, and sticky float. (2) Show exactly which streams enter the basin after each lever test. (3) A check or close inspection reveals that **spring water alone lacks force**, **thermal water alone is too hot**, and **runoff blocks the mechanism**. (4) If stuck: **“It needs a strong, clean flush: hot and cold together, with the dirty stream diverted.”** Working levers and the main sluice never require rolls.

**Expected sequence:** Inspect flows → redirect valves → open main sluice → observe reaction → adjust until `B / B / D` → **clean, bubbling basin; exit opens**. **Fail-forward:** Unlimited trials; at most **one steam-damage event**, and never on the winning configuration.

## Room 4 — Plaguebound Stair | Hostile Nonlethal Obstacle (5–10 min)
**Scene:** A narrow ossuary stair with makeshift cots, empty Draught vials, and a barricade. **Four Plaguebound survivors**, desperate for another dose and fiercely protective of the Dreamer's supply, actively block the party. Some are truly charmed; others are simply dependent and frightened. **Both entrance routes converge here.**

**Goal:** Break through without a lengthy fight; two allied party members remain to **hold the stair**, while the featured PC selects **one Cleric / Warrior / Mage** to accompany them into Room 5.

**Plaguebound (optional minimal stats):** **AC 10, HP 6, Speed 25 ft.** Desperate grapple: **Athletics +2**, contested under normal 2014 grapple rules; makeshift weapon **+2 to hit, 1d4 bludgeoning**, used chiefly if attacked. Their default tactics are to grapple, obstruct, and shout—not deal damage.

| Approach | Resolution |
|---|---|
| Talk them down | **DC 14 Persuasion** (their charm and desperation make them reluctant) |
| Slip through opening | **DC 11 Acrobatics** |
| Push through or shift barricade | **DC 12 Athletics** |
| Distract with Draught vial | **DC 10 Deception** |
| Use vigil lantern to clear mist | One hesitates; **advantage on next passage check** (does not automatically end their charm) |
| Fail a passage check | Brief grapple/blocked path; retry or change approach; **no automatic damage** |

**Suggested beats:** **R1:** Plaguebound order the party back and close ranks. **R2:** Two allies volunteer to hold the four at bay. **R3:** PC and chosen companion slip through, push past, or exploit the distraction.

**Background hold (optional):** Once per round, **d20 vs DC 10**: success = allies occupy the Plaguebound; failure = one slips toward the PC, requiring **DC 11 Athletics/Acrobatics** to get clear or companion interception. Failed follow-up causes **delay only**, not an extra automatic attack. Do not let this sidetrack the boss battle indefinitely.

**Exit / party split:** Two allies remain on the stairs to contain the Plaguebound. **PC + one chosen companion** enter Room 5. See **Combat QRef** for companion stats and boss-combat support.

## Room 5 — Dreamer's Sanctuary | Final Boss (15–25 min)
**Scene:** Beautiful, steaming turquoise underground spring; the Dreamer presents as an inviting water nymph. **Dr. Ashbury** works beside an alchemical bench with Draught bottles. **Three ward-stones** ring the pool (one dimly active, **two damaged**).

**Goal:** Defeat the **Bound Dreamer + Ashbury** with **PC + one chosen companion**, **or** reactivate **both damaged ward-stones** with Kathra's knowledge.

| Arena feature / action | Mechanic |
|---|---|
| Shallow pool | **Difficult terrain** |
| Examine alchemical workbench | **DC 10 Investigation:** see Draught-making equipment |
| Destroy usable Draught supplies | Bench **AC 10, 5 HP**; Ashbury loses access to bench supplies (adjudicate separately from her single carried dose) |
| Restore damaged ward-stone | With Kathra's knowledge: **action adjacent; DC 11 Arcana** per stone; retry on failure; **2 successes total** reseal Dreamer |
| Accessibility alternative | If PC knows the method but lacks Arcana, use **DC 11 INT** or **two uninterrupted actions per stone** for automatic activation |

**Combat QRef:** **“The Bound Dreamer + Dr. Ashbury”** in `hollowmere-combat-reference.md` for enemy/companion stat blocks, charm, healing, round-by-round beats, potion rules, and ending consequences. Dreamer is **bound/weakened**, not full-strength Succubus.

**Visual feedback:** Each repaired ward dims the nymph illusion, clouds the spring, and strengthens the runes. **Both restored = containment.** Without Kathra's method, the PC can win by defeating the Dreamer, but cannot properly reseal the wards.


