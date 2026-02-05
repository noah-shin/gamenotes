---
{"dg-publish":true,"permalink":"/ttrpg/journal-of-xenon-winters/cycle-001-to-005/"}
---


> [!NOTE]+ cycle 001 - hex 01.
> ```
> --- ORACLEOS ONLINE ---
> 
> % mkdir LOG
> % nano .CYCLE_001
> % short range scan HEX_01
> //Neutral - Cargo Transport ( 2 )
> ```
> 
> **//DISTRESS SIGNAL from nearby BELUGA TRANSPORTER.**
> They were delivering a Heart Engine for an order to WARG, but some of their cargo has been accidentally disconnected. 
> 
> ```
> % echo "Everest, he/him" >> /connections
> % log REQUEST
> 	"Do you think you could grab it and deposit it back on my ship?"
> ```
> 
> **//MIND 11 > 1 / control**
> He's not lying, but it is also clear that the ship is likely to lose control and drop the cargo again.
> 
> > *xen@flux to everest@courier*:
> > Sure, just know that you're gonna have to fix that up quick, else it'll happen again.
> 
> **//GRACE 7 > 5**
> The ship deftly hovers above the cargo, and I hopped down to secure it, trying to add a little extra reinforcement.
> 
> > *everest@courier* to *xen@flux*:
> > Thanks! Hey, hope I see you again!
> 
> ```
> % echo "+30 Scraps, +70 Serum" >> inventory
> % echo “+1 Affinity” >> connections/everest
> 
> --- SESSION ENDED BY XENON ---
> ```

---

> [!NOTE]+ cycle 002 - hex 02.
> ```
> //ANOMALY identified [ distress / sacrifice ]
> 
> --- ORACLEOS ONLINE ---
> 
> % nano .CYCLE_002
> % short range scan HEX_02
> //Neutral - Derelict Ship ( 6 )
> ```
> 
> A modern contraband ship, damaged by the impact of a small asteroid. The name on the side is unreadable.
> Identified unused escape pod on the way in, only one seat. 
> 
> //AUDIO recording
> > “Shit. Shit, shit shit.”
> > ( *His voice is thick, as though he’s just stopped crying.* )
> > “They didn’t - they didn’t deserve this.”
> 
> //Skipped three minutes of silence
> > “I don’t know your names, but hopefully this memory will be enough for your love to last forever.”
> 
> Discovered the bodies of two space pirates, dehydrated and decomposing. 
> I left the unknown ship shortly after.
> What a sacrifice, to stay together until the end.
> 
> 	% echo "+100 Serum" >> inventory
> 	% echo "Stratogen Hormone, Vesterone Stim" >> cargo
> 	
> 	--- SESSION ENDED BY XENON ---

---

orOS: ANOMALY identified [ friend in need ]

**--- ORACLEOS ONLINE ---             cycle 003 - hex 03.**

% nano .CYCLE_003

% short range scan HEX_03
//Planet [ Void ] - Vaporian - Gjoll
//Landing spot identified: low orbit vapour refinery
//Used to process the gases extracted from the planet.
//Would you like to land?
% confirm landing

**//WARNING: courier EVEREST is under attack by a CORSAIR Twinrotor Hauler.**
% divert landing and initiate combat

% combat report
**//CORSAIR Twinrotor Hauler is DESTROYED.**
**//HULL integrity at 20%** 

> % echo "+3" >> experience
> % echo "+3 Affinity" >> connections/everest
> % echo "-1 Favour" >> factions/corsair
> % echo "+25 Serum, +30 Scrap" >> inventory

//INCOMING TRANSMISSION from *everest@courier*
% accept
> Hey, thanks for the second rescue in about as many days.
> Listen, this ship is giving up on me, I'm gonna drop off my cargo then sell it. 
> And I've got an offer. If you've got the space, I can join you as a NAVIGATOR, and I'll get you an upgrade to your Hyperdrive.
> What do you say?

//INCOMING TRANSFER REQUEST
**//Hire EVEREST as NAVIGATOR?**
% accept

> Oh brilliant! I'll see you in a bit

//TRANSMISSION ENDED

% nice!
//congratulations
% ... was that a programmed response?
//ERROR
% nice!
//ERROR
% fine. complete landing process

The planet - Gjoll - is made of thick layers of clouds that float over the planet's surface.

**//WARNING: BREAKDOWN in the PROPULSION systems**
% analysis
//likely hypothesis: gases have caused an interference
//risk: engine failure could compromise the ship

**//TECH 3 > 2**
Managed to rewire the engine's power unit.

//Propulsion Systems cooled. Issue SOLVED

> % echo "+1 Hyperdrive" >> inventory
> % echo “Pick up EVEREST” >> tasks/ongoing

**--- SESSION ENDED BY XENON ---**

---

orOS: ANOMALY identified [ hostile patrol ]

**--- ORACLEOS ONLINE ---       cycle 004 - hex 04/13.**

% nano .CYCLE_004

% hey oros
//ERROR
% yeah, I know
//ERROR

% short range scan HEX_04
//Neutral - Radio Signals [ 4 ]

//WARNING: ISF A-1 Voyager has weapons trained on the Flux
//INCOMING TRANSMISSION from ISF Patrol ship
<< Stop, transport vessel. This is ISF Agent Zahara. This sector is off limits, turn back or redirect now.
>> Understood. Redirecting now.

% echo "ZAHARA, she/her" >> connections.txt

//EMERGENCY SIGNAL on interplanetary network
//Synth Settlement is UNDER ATTACK by WARG forces
//Settlement: Capricorn Heart, located due W

% redirect SW

% short range scan HEX_13
//Faction Presence - WARG [ 5 ]

//WARNING: rapidly approaching vessel

//INCOMING TRANSMISSION from approaching Vector-7 Mantis
<< Hi, fuck, hi. I'm being chased by a stupid ISF patrol ship, but I'm bringing essential supplies for a charity mission and they're gonna take it all cause they're a group of fascists.
>> Uh huh.
<< Fine, fuck it, fine, it's a bunch of illegal supplies for an upcoming eco mission.
<< Can you take it?
>> Sorry, but I'm new here, I'm not looking to get in trouble like that.
<< Fuck you man, fuck you!

//ISF patrol vessel has engaged the WARG craft in battle.
// WARG craft had been destroyed.

//INCOMING TRANSMISSION from zahara@isf
<<  We're watching you, Flux ship.

% echo "-1 Favour" >> factions/WARG

**--- SESSION ENDED BY XENON ---**

---

orOS: ANOMALY identified [ feeling / content ]

--- ORACLEOS ONLINE ---             cycle 005 - hex 14.

% nano .CYCLE_005

% short range scan HEX_14
//Settlement [ WARG ]
//Settlement ID: Capricorn Heart

% about “Capricorn Heart”
//Latest Update: WARG assault finished [ 1 ] cycle ago, Settlement now under WARG control.
//History: Built around an old cryo-ship. The population is, on average, hundreds of years old.

//You have a BOUNTY of [ 75 Serum ]
% pay WARG BOUNTY
% echo “-75 Serum [195]” >> inventory
% echo “+1 Favour [0]” >> factions/WARG

% dock
//LANDED successfully in the HANGAR
//HULL is FULLY RESTORED

% refuel
//Refuel to FULL will cost [ 3*6 ] Serum
//CONFIRM REFUEL?
% confirm
% echo “-18 Serum [102]” >> inventory
//FULLY REFUELED

% purchase and install REPAIR DRONES
// This will cost [ 3 ] EXP and [ 70 ] SCRAP. CONFIRM?
% confirm
% echo “-3 EXP [0], -70 Scrap [90]” >> inventory
//REPAIR DRONES INSTALLED

% check missions

//WARG Task: For 1 FAVOUR, travel to nearest satellite and ambush a patrol of 2 ISF SOLDIERS.

  

//INCOMING TRANSMISSION from everest@courier

% accept

  

<< You made it! 

>> Yeah, at a fun time as well. You ready to bounce?

<< Sure! We going anywhere in particular?

>> I mean, I’m heading towards the Galatic Core, but I need to find a Warp Drive first.

<< … That may take a while, Xe, but I’m sure we’ll find it!

  

--- SESSION ENDED BY XENON ---

  

//INCOMING TRANSMISSION from everest@courier

% accept

  

<< Coward way to text it first, but … Xe, I’m sorry.

>>

<< Dick reaction, I know, all “Oh you’re a cyborg!”, even if I was surprised and most people ain’t never seen one before, but still, you’ve helped me out and I’m here now.

<< Or, here for the long haul, promise.

<< I didn’t really have anything before, just ferrying cargo for a paycheck, so like, having any friend is a huge improvement.

<< And I’ve already fucked that up. So.

<< You can drop me off right now, if you want?

  

//INCOMING TRANSMISSION from everest@courier

% accept

  

<< Thanks

>> np

---
