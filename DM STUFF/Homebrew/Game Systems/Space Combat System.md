---
title: Astryx Dominion Space Combat System
category: dm-stuff
clearance: omega_prime
tags:
  - space-combat
  - starships
  - boarding
  - systems
  - UL
  - tactical
  - DND
summary: Comprehensive framework for space combat and boarding operations in Astryx Dominion. Covers three-layer ship model, ship roles, actions, weapon types, system effects, scaling between small craft and capital ships, boarding mechanics, and cinematic risk-reward rules.
---
## CORE PHILOSOPHY

Space combat is not dogfighting fantasy. It is:

- Positioning
    
- Systems pressure
    
- Information warfare
    
- Catastrophic failure cascades
    

Ships don’t “lose HP” until the end. They **lose capability**.

---

## THE THREE-LAYER SHIP MODEL

Every ship has **three interlinked tracks**:

### 1. **Hull Integrity (HI)**

Physical structure.

- When this hits 0, the ship is destroyed or disabled.
    
- Hull damage happens _after_ shields and systems are compromised.
    

### 2. **Shield Capacity (SC)**

Energy defenses.

- Regenerates slowly.
    
- Can be overcharged or rerouted.
    
- Drops fast under focused fire.
    

### 3. **System Stability (SS)**

This is the magic.

Represents engines, sensors, weapons, AI, life support.

- Many attacks target **systems directly**
    
- When SS thresholds are crossed, bad things happen
    

---

## TURN STRUCTURE (FAST & CLEAN)

Combat is divided into **Rounds**, each with **three phases**.

### 1. **Command Phase**

Each ship chooses **one Command Stance**:

- **Aggressive** – bonus to attacks, vulnerable to system damage
    
- **Defensive** – shield regen, reduced accuracy
    
- **Evasive** – harder to hit, worse firing solutions
    
- **Tactical** – bonuses to scanning, hacking, precision strikes
    

This choice matters more than raw stats.

---

### 2. **Crew Action Phase**

Each player chooses a **Ship Role Action**.

No one waits around.

#### Core Roles (5e-friendly)

- **Pilot** – Maneuver, evade, reposition
    
- **Gunner** – Fire weapons, called shots
    
- **Engineer** – Reroute power, repair, overcharge
    
- **Systems Officer** – Scan, hack, disrupt
    
- **Commander** – Coordinate, inspire, issue directives
    

Players can switch roles mid-combat (with penalties).

---

### 3. **Resolution Phase**

- Attacks resolve
    
- System damage triggers
    
- Fires, breaches, AI glitches occur
    
- Shields regen if applicable
    

Then repeat.

---

## DAMAGE & CALLED SHOTS

### Weapon Attacks

Attacks can target:

- **Shields** (default)
    
- **Hull**
    
- **Specific Systems** (engines, weapons, sensors, AI)
    

Targeting systems increases difficulty but causes cascading effects.

### System Damage Table (Example)

When SS crosses a threshold, roll or choose:

- Engines lose thrust → movement penalties
    
- Weapons misfire → disadvantage or shutdown
    
- Sensors scrambled → blind spots
    
- AI latency → delayed actions
    
- Life support unstable → time pressure
    

This keeps fights tense without just grinding HP.

---

## MOVEMENT WITHOUT A MAP HELL

Use **Range Bands**, not grids.

- Close
    
- Medium
    
- Long
    
- Extreme
    

Pilot actions move between bands.  
Some weapons only work at certain bands.

Orientation matters narratively, not geometrically.

---

## SCANNING & INFORMATION WARFARE

The Systems Officer can:

- Reveal enemy weaknesses
    
- Predict next Command Stance
    
- Feed targeting data to gunners
    
- Jam or spoof enemy sensors
    

This ties directly into your **Focus + AV-8 ecosystem** later.

---

## FAILURE STATES (VERY IMPORTANT)

Ships don’t explode immediately.

At 0 Hull:

- The ship is crippled
    
- Boarding becomes possible
    
- Escape pods trigger
    
- UL AI initiates Contingency Protocols
    

This keeps characters alive and stories going.

---

# SHIP ROLES & ACTIONS

Each round, **each character chooses one role** and takes **one Major Action** and any number of **Free Actions** allowed by that role.  
Switching roles mid-combat is allowed but risky.

---

## ROLE SWITCHING

- Switching roles costs your **reaction** that round.
    
- If the ship has no AI assistance, switching also imposes **disadvantage on the action**.
    
- A character cannot take the same role two rounds in a row without a relevant proficiency (DM discretion).
    

This reinforces specialization without locking anyone in.

---

# 1. PILOT

_Position, survival, momentum_

**Primary Ability:** Dexterity (Vehicles / Piloting)  
**Secondary:** Wisdom (Perception)

### Major Actions

|Action|Effect|
|---|---|
|**Evasive Burn**|Until next round, attacks against your ship have disadvantage; ship weapons have disadvantage|
|**Hard Maneuver**|Change range band by 1 (2 on a success by 5+)|
|**Pursuit Lock**|Choose one enemy ship; their attempts to disengage from you have disadvantage|
|**Collision Course**|Attempt to ram or force a close-range engagement|
|**Drift & Vector**|Ignore penalties from damaged engines for one round|

### Free Actions

- Adjust facing / narrative orientation
    
- Call out movement openings to the Gunner
    
- Trigger flares, chaff, or decoys
    

### Failure Consequences

- Engine stress (temporary SS damage)
    
- Loss of control → forced random movement
    
- Exposure to enemy firing arcs
    

---

# 2. GUNNER

_Firepower and precision_

**Primary Ability:** Dexterity or Intelligence  
**Secondary:** Wisdom

### Major Actions

|Action|Effect|
|---|---|
|**Standard Volley**|Attack enemy shields or hull|
|**Called Shot**|Attack a specific system (engines, weapons, sensors) at disadvantage|
|**Overcharge Shot**|Deal bonus damage, but weapon risks overheating|
|**Suppressive Fire**|Enemy gunners have disadvantage next round|
|**Point Defense**|Shoot down incoming missiles or drones|

### Free Actions

- Switch weapon groups
    
- Coordinate firing arcs
    
- Accept targeting data from Systems Officer
    

### Failure Consequences

- Weapon jam or cooldown
    
- Friendly system interference
    
- Ammunition depletion (if applicable)
    

---

# 3. ENGINEER

_Power, repairs, desperation_

**Primary Ability:** Intelligence  
**Secondary:** Constitution

### Major Actions

| Action                  | Effect                                                 |
| ----------------------- | ------------------------------------------------------ |
| **Reroute Power**       | Boost shields, engines, or weapons                     |
| **Patch Systems**       | Restore System Stability or repair a damaged subsystem |
| **Emergency Overclock** | Grant another role advantage on their action           |
| **Contain Breach**      | Prevent cascading damage or fires                      |
| **Jury-Rig**            | Temporarily restore a destroyed system                 |

### Free Actions

- Seal compartments
    
- Trigger backup power
    
- Argue with the ship AI
    

### Failure Consequences

- Power surge damages another system
    
- Fire, radiation, or pressure hazards
    
- AI safety lockouts
    

---

# 4. SYSTEMS OFFICER

_Information is the real weapon_

**Primary Ability:** Intelligence or Wisdom  
**Secondary:** Charisma

### Major Actions

|Action|Effect|
|---|---|
|**Deep Scan**|Reveal enemy ship stats or weaknesses|
|**Targeting Uplink**|Grant advantage to Gunner or Pilot|
|**Electronic Warfare**|Impose disadvantage on enemy actions|
|**System Hack**|Temporarily disable an enemy subsystem|
|**Signal Masking**|Reduce chance of being targeted or tracked|

### Free Actions

- Monitor battlefield telemetry
    
- Feed data to Focus/AV-8 interfaces
    
- Log combat data for UL
    

### Failure Consequences

- Feedback damage (SS loss)
    
- Enemy counter-hack
    
- False data injected
    

---

# 5. COMMANDER

_Coordination, morale, authority_

**Primary Ability:** Charisma  
**Secondary:** Wisdom

### Major Actions

|Action|Effect|
|---|---|
|**Command Directive**|Grant an ally an extra Free Action|
|**Tactical Reframe**|Change ship’s Command Stance mid-round|
|**Rally Crew**|Restore minor SS or negate a failure|
|**Intimidating Broadcast**|Force enemy morale check|
|**Override Protocol**|Ignore one system failure this round|

### Free Actions

- Issue flavor orders
    
- Argue with UL protocols
    
- Record after-action justification
    

### Failure Consequences

- Crew hesitation
    
- Conflicting orders
    
- AI questions your authority
    

---

## SHARED ACTION: BOARDING PREP

Any role can spend their Major Action to:

- Prepare boarding pods
    
- Lock enemy airlocks
    
- Repel boarders
    
- Ready internal defenses
    

This becomes critical later.

---

## ROLE SYNERGY (VERY IMPORTANT)

When **two or more roles coordinate**, grant:

- Advantage
    
- Reduced difficulty
    
- Or enhanced effect
    

Example:

- Systems Officer + Gunner = guaranteed system hit
    
- Pilot + Engineer = ignore engine damage
    
- Commander + Anyone = turn failure into partial success
    

You want players _talking constantly_.

---

# SHIP WEAPON TYPES

All ship weapons share a base profile:

- **Attack Roll** (Gunner action)
    
- **Damage** to Shields, Hull, or Systems
    
- **Special Effects** based on weapon type
    

Weapons are defined by **damage profile**, not raw numbers.

---

## 1. KINETIC WEAPONS

_Mass, momentum, inevitability_

Examples: Railguns, mass drivers, coil cannons, micro-missiles

### Core Identity

- High hull damage
    
- Lower shield efficiency
    
- Physically destructive
    

### Mechanical Traits

- Deal **reduced damage to Shields**
    
- Deal **bonus damage to Hull**
    
- Can cause **breaches** on critical hits
    

### Special Effects

- On a successful hull hit, roll for:
    
    - Hull breach
        
    - Structural collapse
        
    - Crew injury zones
        
- Harder to intercept once fired
    

### Tactical Use

- Finishing blows
    
- Anti-armor roles
    
- Boarding prep (breach creation)
    

### Weaknesses

- Less effective against high-end shields
    
- Ammunition constraints
    
- Slower firing cycles
    

### Astryx Flavor

UL considers kinetic weapons “honest.” They leave evidence.

---

## 2. ENERGY WEAPONS

_Control through precision_

Examples: Lasers, plasma lances, particle beams

### Core Identity

- Versatile
    
- Shield-efficient
    
- High accuracy
    

### Mechanical Traits

- Full damage to Shields
    
- Moderate damage to Hull
    
- Can **bleed through** shields at overcharge
    

### Special Effects

- Overcharge causes:
    
    - Heat buildup
        
    - System instability
        
- Precision beams enable:
    
    - Easier Called Shots
        

### Tactical Use

- Shield stripping
    
- Precision disabling
    
- Sustained engagements
    

### Weaknesses

- Heat management
    
- Vulnerable to reflective defenses
    
- Power-hungry
    

### Astryx Flavor

Energy weapons are corporate-approved. Clean, efficient, documented.

---

## 3. EMP / DISRUPTION WEAPONS

_Win without killing_

Examples: EMP torpedoes, ion cannons, signal scramblers

### Core Identity

- System killers
    
- Low physical damage
    
- High chaos potential
    

### Mechanical Traits

- Minimal Hull damage
    
- Deal direct **System Stability damage**
    
- Ignore shields partially or fully
    

### Special Effects

On hit, roll or choose:

- Engines offline
    
- Weapons disabled
    
- Sensors blinded
    
- AI latency
    

### Tactical Use

- Capture missions
    
- Disabling superior ships
    
- Non-lethal enforcement
    

### Weaknesses

- Ineffective against hardened systems
    
- Short-lived effects
    
- Less useful once shields are gone
    

### Astryx Flavor

UL prefers EMP when it wants something intact—and obedient.

---

## 4. BIO-DISRUPTIVE WEAPONS

_Ethically uncomfortable on purpose_

Examples: Spore warheads, gene-burn beams, adaptive nanoclouds

### Core Identity

- Attacks crew, not ships
    
- Persistent effects
    
- Morally loaded
    

### Mechanical Traits

- Bypasses Hull
    
- Targets **Crew Integrity** or life-support systems
    
- Effects worsen over time
    

### Special Effects

- Panic, hallucinations, mutations
    
- Life support contamination
    
- Crew actions penalized or replaced by AI
    

### Tactical Use

- Psychological warfare
    
- Forcing surrender
    
- Research acquisition
    

### Weaknesses

- Requires close or sustained exposure
    
- Can contaminate captured ships
    
- GC treaty violations
    

### Astryx Flavor

UL classifies these as “situational research tools.”

---

## WEAPON SYNERGIES

Weapon types become lethal when combined:

- **Energy → Kinetic**  
    Strip shields, then punch through hull.
    
- **EMP → Boarding**  
    Disable systems, then move in.
    
- **Bio-Disruptive → Energy**  
    Distract crew, then surgically disable systems.
    

Encourage players to think in **loadouts**, not single weapons.

---

## WEAPON MOUNTS & SLOTS (OPTIONAL BUT JUICY)

Weapons can be:

- Fixed
    
- Turreted
    
- Drone-mounted
    
- Internal (point defense)
    

Some upgrades change **how** a weapon behaves, not what it is.

---

## DAMAGE IS NOT THE POINT

Damage is the _symptom_.  
The real goal is:

- System collapse
    
- Control
    
- Forced decisions
    

A ship with 90% hull and no sensors is already dead.

---

## DESIGN NOTE FOR DMS

When in doubt:

- Kinetic ends fights
    
- Energy shapes fights
    
- EMP controls fights
    
- Bio-disruptive haunts fights

---

# BOARDING ACTIONS

Boarding is not a single action. It is a **state change** in combat.

Once boarding begins, the fight splits into:

- **External Ship Combat**
    
- **Internal Close-Quarters Operations**
    

Both continue simultaneously.

---

## WHEN BOARDING BECOMES POSSIBLE

A ship may be boarded when **one or more** conditions are met:

- Target ship is at **Close Range**
    
- Target ship has:
    
    - Shields down **or**
        
    - Disabled engines **or**
        
    - System Stability below a critical threshold
        
- Boarding party has a viable insertion method:
    
    - Boarding pods
        
    - Breach charges
        
    - Docking clamps
        
    - Forced airlock override
        

UL doctrine prefers boarding over destruction whenever assets are recoverable.

---

## BOARDING PHASE STRUCTURE

Once boarding begins, each round gains a **Boarding Phase** after the Resolution Phase.

Each boarding character takes **one Boarding Action per round**.

Ship roles still matter. The ship fight does not pause.

---

## BOARDING STATES (IMPORTANT)

Boarding progresses through **states**, not rooms.

1. **Insertion**
    
2. **Containment**
    
3. **Objective Control**
    
4. **Resolution**
    

You move between states through actions and success, not maps.

---

# 1. INSERTION PHASE

_Getting inside alive_

### Boarding Actions

|Action|Effect|
|---|---|
|**Forced Entry**|Breach hull or airlock; triggers internal alarms|
|**Silent Dock**|Insert without alerting defenders (harder)|
|**Hot Drop**|Fast insertion; gain momentum but take damage|
|**Remote Breach**|Use drones or charges to open a path|

### Failure Consequences

- Hull decompression
    
- Casualties
    
- Boarding party scattered across compartments
    
- Automated defenses activate
    

Insertion defines the _tone_ of the boarding op.

---

# 2. CONTAINMENT PHASE

_The ship fights back_

Once inside, the ship becomes an enemy.

### Environmental Hazards (roll or choose)

- Zero-G compartments
    
- Fire suppression foam
    
- Radiation leaks
    
- Automated turrets
    
- Hostile AI countermeasures
    

### Boarding Actions

|Action|Effect|
|---|---|
|**Secure Compartment**|Prevent reinforcements|
|**Advance**|Push deeper toward objectives|
|**Hack Bulkheads**|Control internal movement|
|**Deploy AV-8**|Gain surveillance or suppress defenders|

Failure here causes:

- Time pressure
    
- Flanking enemies
    
- Loss of stealth
    

---

# 3. OBJECTIVE CONTROL

_Why you boarded in the first place_

Common objectives:

- Bridge takeover
    
- Engine shutdown
    
- AI core capture
    
- Data vault extraction
    
- Crew pacification
    

### Objective Actions

|Action|Effect|
|---|---|
|**Override Systems**|Disable or seize control|
|**Capture Personnel**|Take targets alive|
|**Extract Data**|Secure UL-relevant assets|
|**Sabotage**|Render ship unusable|

Each objective completed:

- Weakens the enemy ship externally
    
- Grants bonuses to allied ship actions
    

Example:  
Capturing the engine room grants advantage to the Pilot and prevents enemy disengagement.

---

# 4. RESOLUTION PHASE

_Who owns the ship now_

Boarding ends when:

- One side surrenders
    
- Boarding party retreats
    
- Ship is destroyed
    
- AI initiates lockdown or purge
    

Possible outcomes:

- Ship captured intact
    
- Ship disabled but salvageable
    
- Pyrrhic victory with casualties
    
- Ethical incident logged by UL
    

---

## INTERNAL COMBAT RULES (FAST & DEADLY)

- Use **normal D&D combat**, but:
    
    - Shorter sightlines
        
    - Environmental penalties
        
    - Reinforcements instead of infinite enemies
        
- Treat ship compartments as **dynamic hazards**, not maps
    

The ship should feel alive—and hostile.

---

## AI INTERVENTION EVENTS

At any time, the ship AI may:

- Vent compartments
    
- Seal doors
    
- Flood areas with gas
    
- Lock out intruders
    
- Offer surrender terms
    

UL AIs prioritize asset preservation over life.

---

## ROLE CROSSOVER (VERY IMPORTANT)

Characters outside the boarding party still matter.

- Engineer stabilizes hull to prevent decompression
    
- Systems Officer blocks internal sensors
    
- Commander negotiates surrender
    
- Pilot holds position under fire
    

Boarding should feel like **two teams fighting the same war from different angles**.

---

## FAILURE IS STORY, NOT GAME OVER

Failed boarding attempts can lead to:

- Prisoner arcs
    
- Forced alliances
    
- Shipboard survival scenarios
    
- Moral consequences with UL oversight
    

UL does not punish failure.  
UL punishes _unexplained failure_.

---

# CAPITAL SHIP vs SMALL CRAFT RULES

_Astryx Dominion Space Combat System_

This system governs combat between:

- **Capital Ships** (cruisers, carriers, dreadnoughts, stations)
    
- **Small Craft** (fighters, corvettes, shuttles, gunships)
    

The core rule: **Scale changes what “damage” means.**

---

## SCALE CATEGORIES

|Scale|Examples|
|---|---|
|**Small Craft**|Fighters, bombers, shuttles|
|**Escort**|Corvettes, frigates|
|**Capital**|Cruisers, carriers|
|**Supercapital**|Dreadnoughts, stations|

Attacks across scale bands behave differently.

---

## FUNDAMENTAL RULE: EFFECT, NOT DAMAGE

When a **smaller ship attacks a larger ship**, raw damage is reduced or ignored unless it causes a **System Effect**.

Small craft do not “kill” capital ships.  
They **cripple** them.

---

## ATTACKING A CAPITAL SHIP (SMALL → LARGE)

When a small craft successfully hits a capital ship, choose or roll for an effect instead of applying hull damage.

### SYSTEM STRIKE TABLE

|d6|Effect|
|---|---|
|1|Surface damage only (no effect)|
|2|Weapon array impaired|
|3|Sensor or comms disruption|
|4|Point-defense disabled in a section|
|5|Engine or maneuvering thrusters damaged|
|6|Critical subsystem exposed (follow-up attacks gain advantage)|

Modifiers:

- Precision weapons add +1
    
- Repeated hits stack effects
    
- Boarding follow-ups become possible
    

---

## BOMBING RUNS (HIGH RISK, HIGH PAYOFF)

Bombers may perform **Bombing Runs** against capital ships.

Requirements:

- Close range
    
- Shields down or distracted
    
- Survive defensive fire
    

On success:

- Choose a subsystem to heavily damage
    
- Apply Stability loss instead of hull damage
    

Failure:

- Immediate return fire
    
- Potential instant destruction
    

Bombing runs are heroic or suicidal. Often both.

---

## CAPITAL SHIP DEFENSES AGAINST SMALL CRAFT

Capital ships do not duel fighters.  
They **erase airspace**.

### Point Defense Grid

- Automatically attacks small craft each round
    
- Damage scales brutally
    
- Can be suppressed by:
    
    - Electronic warfare
        
    - Precision strikes
        
    - Boarding actions
        

When point defense is active, small craft:

- Have disadvantage on attack rolls
    
- Take attrition damage each round
    

---

## CAPITAL WEAPONS vs SMALL CRAFT

Capital weapons are not accurate against fighters.

Rules:

- Capital weapons cannot target individual small craft unless specialized
    
- Area weapons create **Threat Zones**
    
- Fighters caught in Threat Zones must evade or take damage
    

This keeps fighters mobile and terrified.

---

## ESCORT SHIPS (THE MISSING MIDDLE)

Escorts exist to:

- Protect capital ships from small craft
    
- Chase down bombers
    
- Control space
    

Mechanically:

- Escorts ignore small craft effect reduction
    
- Escorts can be overwhelmed by numbers
    
- Escorts are the _actual_ enemy of fighters
    

Smart fleets protect their capitals with escorts.  
Desperate fleets do not.

---

## CAPITAL SHIP WEAKNESS: BLIND SPOTS

Capital ships have blind arcs.

If small craft:

- Coordinate attacks
    
- Exploit blind arcs
    
- Disable sensors
    

They gain:

- Advantage on System Strikes
    
- Reduced point-defense response
    

This rewards tactical flying over raw stats.

---

## SWARM RULE (VERY IMPORTANT)

When **multiple small craft** attack the same subsystem in one round:

- Each additional hit increases effect severity
    
- On 3+ successful hits, escalate to **Critical Failure**
    

Critical Failures include:

- Reactor instability
    
- Fire spreading through decks
    
- AI failsafes triggering
    
- Boarding windows opening
    

This is how fleets die without exploding.

---

## CAPITAL SHIP COUNTERPLAY

Capital ships can respond by:

- Reorienting armor
    
- Launching interceptors
    
- Venting damaged sections
    
- Activating internal lockdowns
    
- Initiating AI-controlled maneuvers
    

These actions trade survivability for control.

---

## CINEMATIC MOMENT RULE

Once per battle, a small craft may attempt a **Heroic Maneuver**:

- Thread a gun battery
    
- Dive into a superstructure
    
- Ride debris into a hangar
    
- Ram a vulnerable node
    

Requires:

- High risk roll
    
- Narrative justification
    

On success:

- Massive system impact
    
- Story-level consequences
    

On failure:

- Loss is absolute

---