---
title: "COD Mobile Battle Royale — The Complete Handbook"
season: "Season 5 — Revenge (2026)"
last_verified: "2026-07-15"
maintainer: "itachi-re"
status: "living document — update every season"
---

# COD Mobile Battle Royale — The Complete Handbook

> A structured, beginner-to-Legendary reference for Call of Duty: Mobile Battle Royale — mechanics, settings, gunsmith builds, movement, and endgame strategy.

> [!NOTE]
> **Season context:** This guide reflects **Season 5 — Revenge**, which launched May 27, 2026 and was still the live season at the time of writing (July 15, 2026). CODM rebalances weapons roughly every 4–6 weeks, sometimes mid-season. Sections marked **📌 Meta-dependent** will age faster than sections marked **♾️ Evergreen** (mechanics, movement, aim, positioning). Check the [Season Meta Analysis](#22-season-meta-analysis) section first when returning to this doc after a patch.

---

## Table of Contents

1. [Understanding Battle Royale](#1-understanding-battle-royale)
2. [Settings Guide](#2-settings-guide)
3. [Best HUD Layout](#3-best-hud-layout)
4. [BR Classes](#4-br-classes)
5. [Weapon Meta](#5-weapon-meta)
6. [Gunsmith Builds](#6-gunsmith-builds)
7. [Weapon Mods](#7-weapon-mods)
8. [Loadout Strategy](#8-loadout-strategy)
9. [Landing Strategy](#9-landing-strategy)
10. [Early Game](#10-early-game)
11. [Mid Game](#11-mid-game)
12. [Final Circle](#12-final-circle)
13. [Movement Guide](#13-movement-guide)
14. [Aim Guide](#14-aim-guide)
15. [Team Play](#15-team-play)
16. [Solo vs Squad](#16-solo-vs-squad)
17. [Vehicles](#17-vehicles)
18. [Throwables](#18-throwables)
19. [Economy & Inventory](#19-economy--inventory)
20. [Common Mistakes](#20-common-mistakes)
21. [Advanced Tips](#21-advanced-tips)
22. [Season Meta Analysis](#22-season-meta-analysis)
23. [FAQ](#23-faq)

---

## 1. Understanding Battle Royale

**♾️ Evergreen**

CODM BR drops up to 100 players (solo, duo, or 4-player squad) from a plane with a randomized flight path onto a large map (Isolated, Blackout, Alcatraz, Krai, or a rotating seasonal map). Everyone starts with a melee weapon only — everything else is looted.

### Core systems

| System | How it works | Why it matters |
|---|---|---|
| **HP** | Base 100 HP, restored by med kits/bandages, not affected by armor | Damage always hits HP once armor is depleted |
| **Armor / Plates** | Vests absorb a percentage of incoming damage before HP is touched. Plates (common → legendary) refill a vest's capacity | Fighting without armor is close to suicide past the early game |
| **Kinetic Armor** | A seasonal/limited armor type that actively regenerates a portion of its capacity over time instead of needing plates | Reduces reliance on plate inventory but is not always available every season — check current playlist rules before assuming it's active |
| **Weapon Mods** | Deployable attachments (Red Dot, 4x scope, Extended Mag, Suppressor, Laser Sight, etc.) picked up as loose items in-world and slotted directly onto found weapons | Lets you upgrade a looted weapon on the fly without needing your custom Gunsmith build |
| **Custom Loadouts** | Your pre-built Gunsmith weapons (up to 2 slots), called in via loadout crates/airdrops or, this season, Buy Stations | Guarantees you always have your practiced recoil pattern and TTK regardless of what you loot |
| **Airdrops** | Supply crates that fall on a timer, marked by smoke, containing top-tier loot including one of your custom loadout weapons | High risk, high reward — expect contest fights |
| **Classes** | A selectable ability + passive (see [Section 4](#4-br-classes)) that recharges over the match | A correctly chosen class can flip a losing fight |
| **Revive** | Downed teammates can be revived directly, or eliminated teammates can be revived by retrieving their dog tags and reaching a respawn point (varies by mode: Buy Station, Redeploy Van, or teammate revive) | Squad survivability hinges on fast tag pickups — don't sit on a fight if a teammate is down |
| **Vehicles** | Cars, trucks, ATVs, boats, and occasionally a helicopter or armored vehicle (seasonal), used for rotation and escape | Vehicles are loud — using one announces your position for a wide radius |
| **Safe Zone** | The playable circle shrinks in stages on a timer; being caught outside deals increasing damage over time | Zone awareness beats gunfights — more players die to the circle out of panic than to enemy fire |
| **Chip Terminal** | A control-point-style structure that grants a squad-wide buff (commonly increased armor plate capacity or a temporary perk) when captured | Worth contesting early when your squad has full health and armor advantage, not worth dying over late |
| **Upgrade Terminal** | Deposit scrap/currency to permanently upgrade a piece of gear (usually your backpack or armor tier) for the rest of the match | Prioritize backpack upgrades early so you stop discarding loot |
| **Dog Tags** | Dropped by eliminated players; picking one up starts a revive-eligibility timer for that teammate | Always grab a downed ally's tag before looting their body |
| **Arsenal Drops** | Special crates (sometimes vehicle-mounted or terminal-linked) containing high-tier weapons and mods without needing a full airdrop contest | A safer alternative to airdrops if your squad isn't equipped to fight for one |

> [!TIP]
> New players lose most early games to the **circle**, not to gunfights. Before anything else, build the habit of checking the mini-map timer every time you finish looting a building.

---

## 2. Settings Guide

**♾️ Evergreen principles, 📌 exact values are personal/device-dependent**

There is no universal "best settings" screenshot that works for every device — frame rate and graphics settings are a hardware trade-off, and sensitivity is a personal-feel trade-off refined over hundreds of games. What follows is the *reasoning* competitive and Legendary players use to arrive at their numbers, plus sane starting points.

### Graphics

| Setting | Competitive recommendation | Why |
|---|---|---|
| Graphics Quality | Low or Medium (device-dependent) | Lower quality reduces foliage/texture density, making enemies stand out more against simplified backgrounds |
| Frame Rate | Max available (60/90/120 FPS if your device supports it) | Higher FPS reduces input-to-screen latency, which matters more in gunfights than visual fidelity |
| Anti-Aliasing | Off or Low | Marginal visual benefit, adds GPU load that competes with frame rate stability |
| Bloom | Off | Bloom washes out muzzle flash and highlights, making it harder to track enemies through gunsmoke |
| Shadows | Low or Off | Shadows are one of the most GPU-expensive settings for the least gameplay benefit |
| Depth of Field | Off | DOF blurs background detail — directly hides distant enemies from you |

> [!WARNING]
> Don't chase "max graphics for looks" in BR. Every setting above trades visual polish for either frame stability or literal enemy visibility. This is one of the few areas where the competitive answer is nearly unanimous across creators, pro players, and Reddit's r/CallOfDutyMobile.

### Controls / HUD Layout Philosophy

| Layout | Fingers used | Best for | Trade-off |
|---|---|---|---|
| **2-Finger** | Move + Look/Fire combined | Absolute beginners, casual play | Cannot ADS and jump/slide simultaneously — hard ceiling on mechanical skill |
| **3-Finger** | Move, Look/Fire, + one custom action (usually jump or slide) | Intermediate players stepping up from 2-finger | Big jump in mechanical ceiling for a small learning curve increase |
| **4-Finger** | Move, Look/Fire, jump, slide (or ADS) separated | Most Legendary and competitive players | Requires claw grip or a controller/trigger accessory; steep learning curve but enables jump-shots, slide-cancels, and strafing while firing |
| **5-Finger / Custom Claw** | Full separation of move, look, fire, jump, crouch/slide | Top-tier competitive and tournament players | Highest ceiling, least forgiving — misplaced fingers cost you fights while learning |
| **Tablet Layout** | Same philosophy as 4/5-finger but with more screen real estate for spacing buttons | Tablet players | Buttons can be spaced further apart, reducing accidental double-taps |

> [!TIP]
> The honest progression path is 2-finger → 4-finger, skipping 3-finger unless it genuinely helps you transition. Almost every serious BR player ends up on 4-finger or a claw variant because **jump-shotting and sliding while maintaining aim** is a core survivability skill in close-range fights.

### Sensitivity

Sensitivity is the setting most misrepresented online with exact numbers "copied" from pro players whose device, DPI, and grip differ from yours. Treat the table below as **starting ranges to tune from**, not final answers.

| Setting | Beginner | Intermediate | Competitive |
|---|---|---|---|
| Camera / Standard Sensitivity | 60–70% | 70–85% | 85–100%+ |
| ADS Sensitivity (Red Dot/Holo) | 60–70% | 70–80% | 80–95% |
| ADS Sensitivity (2x–3x) | 40–55% | 50–65% | 60–75% |
| Tactical/Sniper Scope Sensitivity | 20–35% | 30–45% | 40–60% |
| Gyroscope | Off (until comfortable) | On, low multiplier | On, tuned per-scope multiplier |

> [!NOTE]
> **Gyroscope** is one of the highest-ceiling, most under-used tools in CODM BR. It lets you make micro-adjustments (recoil control, final flick corrections) with wrist movement instead of thumb swipes, without sacrificing thumb-based tracking. Most Legendary snipers and many AR players run a low gyro multiplier stacked on top of thumb sensitivity — start at a low value (e.g. a small fraction of your ADS sensitivity) and raise it gradually.

### Audio

| Setting | Recommendation | Why |
|---|---|---|
| Music | Off or very low | Zero gameplay value, can mask footstep audio |
| Effects (gunfire, footsteps, environment) | Max | This is your primary information channel for enemy positioning |
| Voice Chat | On, pushed to a comfortable but non-dominant volume | Needed for squad coordination without drowning footsteps |
| Microphone | Push-to-talk if playing in public voice comms | Prevents your own background noise from stepping on teammates' calls |
| Footstep Optimization | Use headphones, not phone speakers, in any ranked or competitive session | Positional audio through speakers is unreliable; headphones (even wired earbuds) meaningfully improve directional footstep reads |

---

## 3. Best HUD Layout

**♾️ Evergreen**

Regardless of finger count, good HUD placement follows the same rules:

- **Fire button**: bottom-right, large hitbox, positioned so your firing thumb doesn't have to travel far to also reach ADS.
- **ADS**: directly adjacent to fire, or merged with fire (tap-to-fire, hold-to-ADS) depending on personal preference — merged saves a finger for jump/slide on 4-finger setups.
- **Jump / Slide / Crouch / Prone**: cluster these together on the side you don't use for camera movement, so a single thumb roll covers all vertical movement states without lifting off the screen.
- **Reload**: keep it reachable but *out of the way* of fire/ADS — accidental reloads mid-fight lose gunfights.
- **Throwables**: place slightly further from your primary combat cluster; you should have to make a deliberate reach for grenades so you don't fat-finger one during a gunfight.
- **Peek buttons** (lean left/right, if enabled): place near your camera thumb, since peeking is a camera-adjacent action, not a movement one.

> [!TIP]
> Whatever layout you choose, **lock it in for at least 100 games before changing anything**. Muscle memory is the actual performance gain here — the "best" layout is the one you stop consciously thinking about.

---

## 4. BR Classes

**📌 Meta-dependent — classes are added/adjusted across seasons, verify against the in-game class menu before committing Credits**

CODM BR currently runs a roster of specialized classes grouped under "professions," each granting a movement-speed passive after activating their skill. Common classes include Ninja, Trickster, Rewind, Hacker, Smoke Bomber, Trap Master, Jet Boost, Misdirection, and Kinetic Station, among seasonal additions.

| Tier | Class type | Why |
|---|---|---|
| **S** | Mobility/escape classes (e.g., Jet Boost, Rewind-style rewind-to-position) | BR is won more often by disengaging a losing fight than winning every fight — mobility classes let you dictate engagement range |
| **A** | Utility/disruption classes (Hacker-style intel classes, Smoke Bomber) | Strong for squads — provides information or cover that benefits the whole team, not just the user |
| **B** | Aggro/chaos classes (decoy or distraction abilities, pet/summon abilities) | Excellent for hot-drop aggression and clutch 1v1/1v2s, weaker in a passive rotate-and-survive playstyle |
| **C** | Situational/niche classes (counter-picks to a specific other class, area-denial traps) | Only worth running if you know your lobby or opponent is leaning on the class they counter |

> [!IMPORTANT]
> Class balance shifts almost every season, and profession passives (movement speed after skill activation) can meaningfully change a class's tier. **Before locking in a class for ranked grinding, check the current in-game class list — the specific names, costs (Credits vs COD Points), and passive values are the ground truth, not any external tier list including this one.**

### Solo vs. Squad class priorities

- **Solo:** prioritize escape/mobility and self-sufficiency (healing or repositioning skills) — you have no one to revive you.
- **Squad:** prioritize utility that benefits teammates (intel, area denial, armor drops) over pure personal mobility, since your teammates can already cover mobility gaps by rotating together.

---

## 5. Weapon Meta

**📌 Meta-dependent — Season 5 (Revenge), verified against the May 2026 balance patch**

Season 5's balance patch was one of the larger shake-ups of the year: it buffed the Switchblade X9 (stomach damage multiplier raised, mobility stock buffed), nerfed the SO-14, CX9, Fennec, and LW3-Tundra (movement speed, damage range, ADS speed, and recoil control reductions across the four), gave marksman rifles a mobility buff, tightened medium-range shotgun performance, and introduced the BAL-27 — a bullpup AR with a fire rate that accelerates the longer you hold the trigger.

> [!WARNING]
> BR TTK and range profiles are not identical to Multiplayer for every weapon — BR fights happen at generally longer average ranges with armor in play, which is why some MP darlings (high-fire-rate, short-range SMGs) underperform in BR while range-flexible ARs and marksman rifles tend to translate better. Treat MP tier lists as a *starting reference*, not a direct BR ranking.

### Assault Rifles

| Tier | Weapons | Why |
|---|---|---|
| S | BAL-27, Switchblade X9 (as a hybrid AR/SMG pick) | BAL-27 debuted strong with low recoil and a wide 4-shot headshot range; its ramping fire rate rewards committing to full BR engagement distances rather than tap-firing |
| A | DR-H, M13, RAM-7 | Forgiving recoil, consistent multi-target TTK, remain viable after receiving no Season 5 nerfs |
| B | Kilo 141, AK117, AK-47, Krig 6, Type 19 | Still functional, but out-classed at the top by weapons that received direct Season 5 buffs |
| C | Oden, EM2, Grau 5.56 | Higher skill floor (slower fire rate/high recoil) with no compensating buff this season — only worth running if you've mastered their recoil pattern |

### SMGs

| Tier | Weapons | Why |
|---|---|---|
| S | Switchblade X9, VMP | Switchblade X9 was directly buffed this patch; VMP received no changes but remains one of the most complete, low-recoil SMGs in the game |
| A | QQ9 (10mm ammo) | Very fast TTK at close range, community testing puts it among the fastest full-auto kill times this season |
| B | CBR4 | Still a safe, low-recoil close-range pick, just not a top-tier standout |
| C | CX9, Fennec | Both took multi-stat nerfs this patch (damage range, ADS speed, recoil, or mobility depending on weapon) — drop them from your rotation until/unless buffed back |
| C | USS 9 | Beginner-forgiving but out-classed at high-level play by the S/A tier options above |

### Shotguns

| Tier | Weapons | Why |
|---|---|---|
| A | HS0405 | Still the benchmark one-shot close-range shotgun despite the season's medium-range shotgun nerf |
| B | BY15, R9-0 | Viable panic/room-clear weapons; R9-0 trades one-shot potential for faster follow-ups and benefited from a bullet-spread accuracy improvement this patch |

### Snipers / Marksman

| Tier | Weapons | Why |
|---|---|---|
| A | LW3 Tundra | Nerfed this season (still adjusting to the new numbers) but retains the best bullet velocity and lowest sway in class — still the default one-sniper-rule-all pick for most players |
| A | DL Q33 | Strong bolt-action alternative, unaffected by the Tundra nerf, worth learning as a backup so you're not fully dependent on one weapon |
| A (buffed) | Marksman rifles broadly (e.g., AS VAL, XPR-50-class weapons) | Received a class-wide mobility buff this season, making them more attractive as a flexible, semi-auto mid-range pick that doesn't fully commit you to sniper playstyle |

### LMGs

| Tier | Weapons | Why |
|---|---|---|
| A | RPD, PKM-class LMGs | Large magazines (100 rounds on some) mean you can down and finish multiple targets without reloading — genuinely strong in the final-circle, back-to-back-fight scenarios common to BR |

### Pistols

| Tier | Weapons | Why |
|---|---|---|
| A | L-CAR 9 | The standard competitive secondary — fast TTK inside 20m, frees you from carrying a dedicated close-range primary if your main weapon is range-focused |

---

## 6. Gunsmith Builds

**📌 Meta-dependent, 📌 attachment specifics change with every balance patch**

> [!IMPORTANT]
> Exact attachment *codes* (the copy-paste strings some sites publish) are tied to a specific patch's numeric values and go stale within weeks. Instead, this section gives you the **attachment categories and the reasoning**, so the build stays correct even after minor tuning patches — only re-derive if a weapon gets a structural rework (new barrel options, mod slot changes).

For every weapon below: **primary goal → attachment category → why**. Slot into your own Gunsmith based on what's actually unlocked, since attachment unlock order varies by account progression.

### BAL-27 (S-tier AR — Season 5 new weapon)

- **Goal:** Maximize the ramping fire-rate mechanic by extending sustained-fire windows and controlling recoil once it accelerates.
- **Muzzle:** A recoil-control muzzle (compensator-class) — the accelerating fire rate makes late-magazine recoil the main accuracy risk.
- **Barrel:** A range/velocity barrel to keep the BR-relevant engagement distances (30m+) inside its optimal damage range.
- **Magazine:** Extended mag — the entire point of this weapon is committing to full engagements, so don't undercut it with a small mag.
- **Rear Grip/Stock:** A mobility-oriented stock to offset the ADS penalty typically attached to range/velocity barrels.
- **Laser (optional 5th slot):** Improves hip-fire and hip-ADS transition for the close-quarters phase of a fight before the ramp-up kicks in.
- **Best class pairing:** Mobility/escape classes — the ramp-up mechanic wants you holding a lane, and a mobility skill covers you if the fight goes wrong before your fire rate ramps.

### Switchblade X9 (S-tier SMG — buffed this patch)

- **Goal:** Lean into the new stomach-damage multiplier and stock mobility buff to play an aggressive close-mid range SMG.
- **Muzzle:** Suppressor if you're playing a rotate-heavy, stealth-focused style; compensator if you expect sustained close fights.
- **Barrel:** A short/light barrel for ADS speed — this weapon's identity is now speed, don't fight that with a heavy barrel.
- **Stock:** The mobility-focused stock (the one that received the +movement speed buff this patch) — it's the single highest-value attachment on this weapon right now.
- **Magazine:** Standard-to-extended depending on your engagement style; extended if you're pushing multiple targets per fight (common in BR squad wipes).
- **Best class pairing:** Aggro/hot-drop classes — this weapon wants you initiating fights at close range, not holding a defensive lane.

### VMP (S-tier SMG — unchanged, still elite)

- **Goal:** Preserve its already-low recoil while extending its usable range slightly for BR's more open engagements than MP.
- **Muzzle:** Compensator for vertical recoil control.
- **Barrel:** A range-focused barrel — VMP's main BR weakness versus AR-heavy fights is falloff range, so this is the highest-value slot.
- **Magazine:** Extended, for squad-wipe sustain.
- **Best class pairing:** Utility classes — VMP is flexible enough to fit almost any playstyle, so pair it with whatever your team composition is missing.

### DR-H (A-tier AR — reliable long-range option)

- **Goal:** Lean into its 3-shot-kill consistency at range; this is your "safe" pick if you don't want to relearn a build every patch.
- **Muzzle:** A range-extending muzzle to push its already-strong long-range identity further.
- **Barrel:** A velocity/range barrel — DR-H rewards commitment to long sightlines, common on open BR maps.
- **Optic:** A 2x–3x optic — DR-H's forgiving recoil pattern supports faster ADS engagement than a full sniper scope while still reaching mid-long range.
- **Best class pairing:** Any — it's the "no-surprises" weapon, so it fits whatever class your squad role needs.

### LW3 Tundra (A-tier Sniper — recently nerfed, still top pick)

- **Goal:** Offset the recent nerf by prioritizing sway reduction and ADS speed over pure damage attachments.
- **Barrel:** A velocity barrel to preserve one-shot range as much as possible post-nerf.
- **Stock/Rear Grip:** Sway-reduction attachment — critical after a nerf cycle where handling attachments matter more than they did pre-patch.
- **Optic:** Whatever scope magnification matches your comfortable flick distance — don't over-scope past what you can consistently track.
- **Best class pairing:** Mobility/escape classes — snipers are most vulnerable during the post-shot recovery window; a mobility skill covers that gap.

### CX9 / Fennec (C-tier this season — situational only)

- **Guidance:** Both took multi-stat nerfs (damage range, ADS speed, recoil, and/or mobility). They're still *usable* in casual lobbies but shouldn't be your ranked or competitive pick this season. If you already know their recoil pattern intimately, they remain playable as a close-range panic weapon — just don't expect them to carry a fight past 15–20m anymore.

> [!NOTE]
> Weapons requested but not detailed above (AK-47, EM2, Kilo 141, Grau 5.56, M13, Krig 6, Type 19, QQ9, USS 9, HS0405, BY15, HDR, DL Q33) remain fully usable and are covered at the tier-list level in [Section 5](#5-weapon-meta). They didn't get a dedicated build write-up here because they received no Season 5 balance changes — their existing, previously-established Gunsmith logic (recoil-control muzzle + range barrel + mobility stock, the same general framework used above) still applies unchanged.

---

## 7. Weapon Mods

**♾️ Evergreen (mod categories are stable across seasons)**

| Mod | Rank | Best on | Why |
|---|---|---|---|
| Extended Mag | S | LMGs, any weapon you expect multi-target fights with | Directly extends how many fights you can win per reload cycle — highest value in squad BR |
| Fast ADS | S | SMGs, close-range ARs | ADS speed is often the actual determining factor in close-range 1v1s, more than raw TTK |
| Precise Shot | A | Marksman rifles, DMRs | Increases headshot multiplier — pairs well with weapons you're already landing consistent headshots on |
| Vertical Recoil / Horizontal Recoil mods | A | High fire-rate ARs, LMGs | Directly extends your effective spray range before recoil breaks your pattern |
| Long Shot | B | Snipers, marksman rifles | Extends optimal damage range — valuable on open maps, less valuable on close-quarters seasonal maps |
| Hip Fire | B | Shotguns, close-range SMGs | Situational — high value if you play an aggressive close-range style, low value if you're primarily ADS-engaging |
| Dense Fire | C | Burst or 2-round-kill weapons | Niche — only worth it on weapons where a fire-rate increase doesn't also increase recoil beyond what you can control |
| Gold Mods | S (when available) | Whatever weapon they're rolled for | Gold mods generally combine two mod effects at reduced penalty — always an upgrade over a standard mod of the same category if you have the inventory space |

> [!TIP]
> In-match weapon mods are separate from your Gunsmith build — you'll frequently loot a weapon mid-game that isn't your custom loadout. Learning to recognize which loose mod matters most (Extended Mag and Fast ADS first, cosmetic/niche mods last) saves inventory space for healing items instead.

---

## 8. Loadout Strategy

**♾️ Evergreen**

- **First custom weapon:** Your primary engagement weapon — an AR or the SMG you're most confident with at your expected average fight distance for the map you're on.
- **Second custom weapon:** Cover the range your first weapon is weakest at. AR primary → SMG or shotgun secondary for close quarters. SMG primary → a DMR or sniper secondary for when you get caught in the open.
- **Late-game swaps:** As the circle shrinks, average engagement distance shrinks with it. It's normal and correct to drop a long-range weapon for a second close-range option once you're inside the final 2–3 circles, especially indoors or in dense POIs.

> [!TIP]
> Don't build two weapons that solve the *same* problem. The single most common loadout mistake is carrying two ARs with near-identical range profiles — you've effectively wasted one of your two slots.

---

## 9. Landing Strategy

**♾️ Evergreen**

| Drop type | Best for | Risk profile |
|---|---|---|
| **Hot drop** (named high-loot POI) | Players confident in early-game gunfights, aggressive squads wanting fast kills for XP/rank points | High risk, high reward — expect 3–6 squads landing simultaneously |
| **Safe drop** (edge-of-map, low-traffic POI) | Beginners, players prioritizing survival/placement over kills | Low risk, but you'll need to rotate further and may land with weaker loot |
| **Ranked drop** (a deliberately mid-tier POI with 1–2 squads max) | Most experienced ranked players | Balanced — enough loot to be competitive without the coin-flip of a full hot-drop |
| **High-tier loot zones** (marked yellow on the map) | Squads wanting guaranteed upgrades | Predictable value, but also predictably contested — treat as a hot drop in terms of risk |

**Rotation planning:** Before your plane even reaches the drop point, glance at the flight path and plan your *rotation direction*, not just your landing spot. Landing well but then rotating into the shrinking zone's least favorable edge undoes the advantage of a good drop.

---

## 10. Early Game

**♾️ Evergreen**

- **Loot priority order:** Armor vest → weapon (any) → plates → healing → attachments/mods → second weapon.
- **Armor first, weapon second** — a good weapon with no armor loses to a mediocre weapon with armor in almost every early fight.
- **Fighting:** Only engage early fights you can win decisively and disengage from cleanly. Early kills are worth less than early survival — you can always get kills later with a full loadout and armor.
- **When to disengage:** If a fight goes past 2–3 exchanged shots without a clear advantage, or a third party's gunfire becomes audible, disengage. Early-game fights rarely need to be finished at all costs.

---

## 11. Mid Game

**♾️ Evergreen**

- **Positioning:** Prioritize high ground and buildings with multiple exits over open ground, even if it means a slightly longer rotation.
- **Rotations:** Move with the zone shrink timer, not against it — arrive at your next position with time to set up cover, not scrambling in the final seconds.
- **Third-party awareness:** Any fight lasting more than ~15–20 seconds risks drawing a third squad. Factor this into whether you commit to a fight or disengage.
- **Vehicle usage:** Use vehicles for long rotations across open ground, but dismount before entering a POI — vehicles announce your position and remove your ability to use cover mid-approach.
- **Chip Terminal timing:** Worth contesting mid-game when your squad is at full health/armor and has a numbers advantage; skip it if contesting would cost you rotation time against the closing zone.
- **Airdrop timing:** Mid-game airdrops are generally safer to contest than late-game ones — fewer squads are alive to converge on the smoke.

---

## 12. Final Circle

**♾️ Evergreen**

- **High ground:** Nearly always worth the rotation cost in the final 2–3 circles — it grants sightlines on every other squad's rotation path.
- **Cover usage:** Natural cover (rocks, terrain) is more reliable than structures in the final circle, since structures get contested and destroyed/entered by multiple squads.
- **Smoke and grenades:** Use smoke proactively to break sightlines *before* you're pinned, not reactively after you're already taking damage.
- **Team spacing:** Spread out enough that a single grenade or spray can't hit your whole squad, but stay close enough to trade revives — a common benchmark is staying within quick sprint-reinforcement distance of each other.
- **End-game decision making:** In the final 2 squads, prioritize the fight you can win cleanly over the fight that gets you "final kill" bragging rights. A won gunfight with 20 HP left is still a loss if a third factor (zone damage, a straggler) finishes you immediately after.

---

## 13. Movement Guide

**♾️ Evergreen**

| Technique | What it is | When to use it |
|---|---|---|
| **Slide cancel** | Slide, then cancel into a jump or stand almost immediately to preserve momentum without the slide's recovery lag | Closing distance quickly while staying hard to hit |
| **Bunny hopping** | Chaining jumps to maintain speed while breaking a consistent height pattern | Crossing open ground under fire |
| **Drop shot** | Dropping to prone the instant you engage, to shrink your hitbox mid-fight | Point-blank fights where you're already taking damage |
| **Jump shot** | Jumping just before or during firing to disrupt an enemy's aim tracking | Close-range peeks where you expect to be pre-aimed |
| **Strafing** | Constant lateral movement while in a gunfight, never standing still while exchanging shots | Every mid-to-close range fight, always |
| **Shoulder peeking** | Exposing only the minimum silhouette needed to see/shoot around cover | Holding an angle against an unknown approach |
| **Head glitching** | Positioning so only your head/upper body clears an obstruction | Defending a chokepoint at range |
| **Jiggle peeking** | Quick in-and-out peeks to bait a reaction shot without fully committing | Scouting an unclear angle before committing to a push |
| **Camera abuse** | Using third-person camera offset to see around corners without exposing your character model | Corner-checking safely before a push |
| **Zipline movement** | Using ziplines for fast, low-exposure map traversal | Crossing open zones or escaping a losing fight quickly |

> [!TIP]
> Movement techniques are only valuable if they're automatic. Practice each one individually in a private match or the firing range before trying to combine them under actual gunfight pressure.

---

## 14. Aim Guide

**♾️ Evergreen**

- **Crosshair placement:** Keep your crosshair at head height on likely enemy paths *before* a fight starts, not after you see them — this cuts your reaction time roughly in half.
- **Tracking:** Practice matching an enemy's strafe speed with smooth camera movement rather than jerky micro-corrections.
- **Flicking:** Train flicks at a fixed sensitivity for at least a week before changing sensitivity again — flick accuracy is sensitivity-memory dependent.
- **Recoil control:** Learn your weapon's actual recoil pattern (most CODM ARs recoil up-and-slightly-right or up-and-slightly-left in a repeatable pattern) and counter-pull, rather than just holding straight down.
- **Hipfire:** Reserve for point-blank, already-close-range fights — hipfire accuracy degrades fast past ~5–8 meters on most weapons.
- **ADS discipline:** Don't hold ADS while running down open ground — you lose peripheral awareness and movement speed for no benefit until an enemy is actually visible.
- **Pre-aiming:** Round every corner with your crosshair already up at the angle you expect an enemy, not your movement direction.

**Drills:**
1. Firing range, 50 shots per session, aiming purely for consistent bodyshot tracking on a moving bot before touching headshot-only drills.
2. Multiplayer close-quarters modes (Frontline, Team Deathmatch on small maps) for high-volume, low-stakes gunfight reps before taking new mechanics into ranked BR.
3. Private match 1v1s against a friend to practice peeking and crosshair placement without full-lobby randomness.

---

## 15. Team Play

**♾️ Evergreen**

- **Communication:** Call enemy positions using clock direction or landmark references ("2 o'clock, tower") rather than vague callouts.
- **Callouts:** Establish a short, consistent callout vocabulary with your regular squad before ranked sessions — consistency beats cleverness under pressure.
- **Revives:** The player closest to a downed teammate should call the revive; don't let two players abandon cover to revive the same person.
- **Team composition:** Where possible, mix weapon ranges across your squad (one long-range anchor, two-three flexible mid/close) so your team isn't collectively weak at any one engagement distance.
- **Positioning:** Avoid stacking your whole squad in one room or sightline — a single grenade or a well-placed enemy angle shouldn't be able to threaten your entire team at once.
- **Roles:** Assign rough roles (anchor/sniper, entry/aggressor, support/healer-caller) based on each player's strongest weapon class, and stick to them long enough to build synergy.

---

## 16. Solo vs Squad

**♾️ Evergreen**

| Factor | Solo | Squad |
|---|---|---|
| Fight selection | Much more conservative — no one to revive you | Can afford to contest more fights with revive backup |
| Rotation | Faster, more flexible — no need to coordinate | Slower, must account for the whole team's position |
| Class choice | Self-sufficiency/mobility priority | Utility/team-benefit priority |
| Endgame | Purely mechanical — no communication advantage possible | Communication and coordinated pushes often decide close final circles |
| Common mistake | Overextending into fights you can't disengage from | Splitting up under pressure instead of consolidating |

---

## 17. Vehicles

**📌 Roster can shift seasonally (e.g., Armored Royale's dedicated armored vehicle is a Season 5 mode-specific addition)**

| Vehicle type | Speed | Durability | Noise | Best use |
|---|---|---|---|---|
| ATV / ATV-class bikes | High | Low | Moderate | Fast solo rotation, hard to hit due to small profile |
| Sedan/car-class | Moderate | Moderate | High | Squad rotation across open ground |
| Truck/SUV-class | Moderate-low | High | High | Tanking damage during a contested rotation, at the cost of speed |
| Boat | Water-only, moderate | Low | Moderate | Rotating across water-heavy maps, generally safer than swimming |
| Helicopter (map/season-dependent) | High | Low | Very high | Fast, high-visibility rotation — use only when speed matters more than stealth |
| Armored vehicle (Armored Royale mode) | Moderate | Very high | High | Acts as a mobile respawn anchor for the squad in this mode specifically — protect it as a team priority resource, not just transport |

> [!WARNING]
> Every vehicle in CODM BR is audible from a significant distance. Never drive directly into a POI you intend to loot quietly — dismount and approach on foot from at least a short distance out.

---

## 18. Throwables

**♾️ Evergreen**

| Throwable | Use case | Notes |
|---|---|---|
| **Frag Grenade** | Clearing a room or forcing repositioning | Cook briefly (don't insta-throw) against players holding a tight angle, so they can't simply walk away from it |
| **Smoke Grenade** | Breaking sightlines to revive, rotate, or disengage | The single most under-used throwable by casual players — smoke isn't just offensive, it's a disengagement tool |
| **Flash Grenade** | Room clears, breaking a defended chokepoint | Least effective outdoors at range; save for close-quarters pushes |
| **Cluster Grenade** | Area denial against a stacked or grouped enemy squad | Best thrown into a room/area you know is occupied by multiple enemies, not as a blind toss |
| **Nova Gas** | Zone denial/flush against players holding a position (class or throwable-dependent by season) | Forces movement — pairs well with a teammate covering the only clean exit |
| **Tactical equipment** (trophy systems, deployable cover, etc.) | Defensive final-circle holds | Most valuable in the last 2–3 squads when you're anchoring a position rather than pushing |

---

## 19. Economy & Inventory

**♾️ Evergreen**

| Item | Recommended carry | Reasoning |
|---|---|---|
| Ammo | Enough for 2 full magazine refills per weapon, no more | Over-carrying ammo eats slots better used for heals/plates |
| Armor plates | 4–6, topped up whenever safe | Running out of plates mid-fight is one of the most preventable causes of death |
| Heals (bandages/med kits) | 2–4 med kits + several bandages | Bandages for quick top-ups mid-fight, med kits for full recovery between fights |
| Throwables | 1 frag, 1 smoke minimum, more if inventory allows | Smoke should never be left at zero — it's your primary disengagement tool |

> [!TIP]
> Every time you loot, ask "does this replace something worse I'm already carrying, or is it just more of the same?" Inventory space is a resource — hoarding duplicate low-tier items is a common way beginners end up stuck outside the safe zone rearranging their backpack.

---

## 20. Common Mistakes

**♾️ Evergreen**

1. Chasing kills instead of prioritizing survival and placement, especially in ranked.
2. Fighting outside the safe zone instead of rotating first.
3. Standing still while exchanging shots instead of strafing.
4. Holding ADS while sprinting across open ground with no visible target.
5. Looting a body in the open instead of dragging the fight into cover first.
6. Not checking the mini-map zone timer after every engagement.
7. Overextending solo pushes when playing in a squad.
8. Ignoring dog tags and leaving a teammate un-revivable.
9. Driving a vehicle directly into a POI instead of dismounting early.
10. Carrying two weapons that cover the same range instead of complementary ranges.
11. Running out of plates because of not topping up between fights.
12. Panic-throwing grenades without cooking frags against close-range angles.
13. Never using smoke defensively, only offensively.
14. Fighting a third party without disengaging from the original fight first.
15. Holding a hot-drop fight past the point where the odds favor you.
16. Not adjusting loadouts as the circle shrinks (keeping a long-range weapon into the final close-quarters circles).
17. Peeking the same angle repeatedly after getting shot from it once.
18. Reloading in the open mid-fight instead of behind cover.
19. Ignoring footstep audio because music/other sounds are turned up too high.
20. Sprinting through open doorways instead of pre-aiming and clearing the angle first.
21. Splitting the squad up during a losing fight instead of consolidating.
22. Contesting every airdrop regardless of squad health/armor state.
23. Forgetting to upgrade the backpack early, causing constant inventory overflow.
24. Not communicating enemy direction with clear, consistent callouts.
25. Building a Gunsmith loadout around a weapon that got nerfed without checking current patch notes.
26. Using max graphics settings that reduce frame rate stability for the sake of visual fidelity.
27. Never practicing movement techniques outside of live matches, so they fail under pressure.
28. Staying on a rooftop past the point it becomes a third-party magnet.
29. Ignoring gyroscope entirely, missing out on fine aim-correction potential.
30. Treating every gunfight as winnable instead of recognizing when to disengage.
31. Landing in a hot POI without a plan for what to do if the first fight goes badly.
32. Not carrying a secondary weapon suited for the endgame's typically closer engagement ranges.
33. Forgetting to switch sensitivity/scope settings after a mid-match weapon swap.
34. Playing passively the entire match and getting caught with a weak loadout in the final circles.
35. Not using cover fire to allow a teammate to revive safely.
36. Misjudging vehicle noise range and alerting nearby squads unintentionally.
37. Holding a defensive position with no rotation plan once the zone moves away from it.
38. Wasting utility (smoke, flashes) on empty rooms instead of confirmed enemy positions.
39. Neglecting the Chip/Upgrade Terminal early when the squad has a clear safety window to use it.
40. Copy-pasting a Gunsmith build from an outdated source without checking if the weapon was nerfed since.

---

## 21. Advanced Tips

**♾️ Evergreen unless noted**

**Positioning & rotation**
1. Rotate early rather than last-minute — arriving with time to pick your exact spot beats arriving under pressure and taking whatever's left.
2. Use terrain silhouettes (ridgelines, rooftops) to spot rotating squads before they spot you.
3. Treat every open field crossing as a calculated risk, not a default path — check for a covered route first.
4. Hold rotation until a visible fight between two other squads resolves, then move in on the winner while they're still low.
5. Avoid being the second squad into a fight already in progress unless you have a clear numbers or positioning advantage.

**Gunfights**
6. Commit to the fight you started before chasing a second target — split attention loses both fights.
7. Bait a shot from an unclear angle with a jiggle-peek before committing to a full push.
8. Reset a losing fight by breaking line of sight and repositioning rather than trading to the death.
9. Use a thrown grenade to force a repositioning enemy into your teammate's sightline.
10. Track recoil patterns per-weapon; every AR/SMG has a learnable, repeatable climb direction.
11. Prioritize headshots only once your tracking accuracy on bodyshots is already consistent — headshot-hunting too early costs more fights than it wins.
12. Don't out-range yourself: know your weapon's optimal range profile and disengage fights that push past it.

**Class & loadout**
13. Match your class choice to your squad role, not just what feels fun.
14. Re-check your Gunsmith build after every patch note release — a single stat change can flip a weapon's tier.
15. Keep a backup weapon build memorized for whichever S-tier weapon got nerfed most recently, so you're never caught loadout-less.

**Endgame**
16. In the final circles, prioritize high ground even at the cost of a slightly longer rotation.
17. Pre-place smoke on your revive spot before pushing to revive, not after taking fire.
18. Track third-party audio constantly in the final 3 squads — most endgame deaths come from an unseen third, not the squad you're actively fighting.
19. Don't finish a downed enemy in the open if it exposes you to a wider angle — let the zone or a teammate finish them if safer.
20. Save at least one throwable specifically for the final circle, don't use your last grenade mid-game.

**Mindset**
21. Play every match for placement first, kills second — rank points reward survival more than eliminations in most competitive ranked systems.
22. Review your last few deaths for patterns (same angle, same overextension, same panic reload) rather than treating each death as unrelated.
23. Warm up with 10–15 minutes of Multiplayer or the firing range before jumping into ranked BR sessions.
24. Mute in-game chat noise or toxic squad members rather than letting tilt affect your positioning decisions.
25. Take a short break after 2–3 consecutive bad placements — decision quality drops noticeably after tilt sets in.

---

## 22. Season Meta Analysis

**📌 Meta-dependent — Season 5 (Revenge), current as of July 15, 2026**

- **Strongest weapons overall:** Switchblade X9 (SMG, directly buffed) and BAL-27 (new AR with a ramping fire-rate mechanic).
- **Strongest supporting picks:** VMP (unchanged, still elite), DR-H (unchanged, reliable long-range AR), LW3 Tundra (nerfed but still the best sniper in class), marksman rifles broadly (received a mobility buff).
- **Confirmed nerfs this season:** SO-14, CX9, Fennec, LW3-Tundra — reduced movement speed, damage range, ADS speed, or recoil control depending on the weapon. Medium-range shotgun performance was also tightened.
- **Weapons likely to remain relevant after future patches:** DR-H and VMP have a track record of staying viable across multiple seasons due to already-balanced base stats rather than needing buffs to stay competitive — a reasonable bet for players who don't want to relearn a build every patch.
- **What to watch for:** BAL-27's community-refined attachment meta was still settling in the weeks after launch — expect creator and Reddit consensus on its exact optimal build to solidify further after this document was written.

> [!IMPORTANT]
> This section will be the first thing to go stale. When you next update this repository, re-verify against the current in-game weapon balance notes before trusting anything in Sections 5, 6, and this section.

---

## 23. FAQ

**Mixed — flagged per answer**

1. **What's the single most important early-game priority?** ♾️ Getting an armor vest before your first weapon upgrade — survivability beats damage output early on.
2. **Should I always contest airdrops?** ♾️ No — only when your squad has a clear health/armor/numbers advantage.
3. **Is gyroscope worth learning?** ♾️ Yes, most high-level players stack a low gyro multiplier on top of thumb sensitivity for fine aim correction.
4. **What HUD layout should a beginner start on?** ♾️ 2-finger to learn fundamentals, then transition to 4-finger once comfortable — most competitive players end up there.
5. **Is the BAL-27 worth unlocking immediately?** 📌 Yes — it's free-tier Battle Pass content this season and entered the meta as a top-10 AR at launch.
6. **Is CX9 still viable?** 📌 It's playable in casual lobbies but took multiple nerfs this season (damage range, ADS speed, recoil) — not recommended for ranked/competitive right now.
7. **What's the best sniper this season?** 📌 LW3 Tundra remains the top pick despite a recent nerf; DL Q33 is a strong unaffected alternative.
8. **Should I run max graphics settings for the best visuals?** ♾️ No — most competitive settings trade visual fidelity for frame rate stability and enemy visibility (lower shadows/bloom/DOF).
9. **How many armor plates should I carry?** ♾️ 4–6, topped up whenever it's safe to do so.
10. **Is it better to hot drop or safe drop as a beginner?** ♾️ Safe drop — prioritize survival and looting fundamentals before taking on early hot-drop fights.
11. **What's the fastest way to improve aim?** ♾️ Consistent firing-range/Multiplayer reps focused on tracking before headshot-hunting, plus fixed sensitivity for at least a week at a time.
12. **Do vehicles alert nearby enemies?** ♾️ Yes, vehicles are audible from a significant distance — dismount before approaching a POI.
13. **What class is best for solo play?** ♾️ Mobility/escape-oriented classes, since there's no teammate to revive you if you overextend.
14. **What class is best for squad play?** ♾️ Utility/team-benefit classes that help the whole squad, not just the user.
15. **Should I always finish a downed enemy?** ♾️ Only if it doesn't expose you to a wider, more dangerous angle — sometimes the zone or a teammate can finish them more safely.
16. **How do I stop losing to third parties?** ♾️ Keep fights short and decisive, and stay aware of audio cues from outside your current engagement.
17. **Is Kinetic Armor always available?** 📌 No — it's tied to specific modes/seasons; check the current playlist before assuming it's active.
18. **What's the most under-used throwable?** ♾️ Smoke grenades used defensively for disengagement/revives, not just offensively.
19. **Should my squad stack together or spread out?** ♾️ Spread enough that one grenade/spray can't hit everyone, but stay close enough for quick revive support.
20. **How often should I re-check this guide's meta sections?** 📌 Every season, and after any mid-season balance patch — Sections 5, 6, and 22 are the fastest-aging parts of this document.
21. **What's the biggest mechanical skill separating Legendary players from Grand Master?** ♾️ Consistent disengagement decision-making — knowing when *not* to fight, more than raw aim.
22. **Is hip-fire viable in BR?** ♾️ Only at genuinely close range (roughly under 5–8 meters depending on weapon); ADS is more reliable past that.
23. **Should beginners use 3-finger HUD as a stepping stone?** ♾️ Optional — many players skip straight from 2-finger to 4-finger without meaningful downside.
24. **What's the ideal squad composition?** ♾️ Mixed weapon ranges across teammates (one long-range anchor, others flexible mid/close) so the squad isn't collectively weak at any one distance.
25. **Does headphone audio actually matter competitively?** ♾️ Yes — positional footstep audio is noticeably more reliable through headphones/wired earbuds than phone speakers.

---

## Maintenance Notes

- This document was researched against official Activision season announcements, competitive/creator meta breakdowns, and community balance-patch summaries current as of **July 15, 2026**.
- Sections tagged **📌 Meta-dependent** should be the first thing re-verified each season — weapon tiers, gunsmith specifics, class rosters, and the Season Meta Analysis section.
- Sections tagged **♾️ Evergreen** (mechanics, settings philosophy, movement, aim, positioning, team play) should remain accurate across multiple seasons and only need light edits.
- Recommended repo convention to match `butex-notes`/`c-learning-notes` style: keep this as a single living file (`battle_royale_guide.md`) with a version/last-verified date in frontmatter, rather than forking a new file per season — easier to diff season-to-season changes in Git history.
