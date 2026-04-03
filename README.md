# Ork Nurgle Daemon Encounter Log

An on-chain ledger of Ork descriptions of encounters with Nurgle’s daemons,  
plague cults, rot-flies, living infections, and other cheerful stink-beasts  
of Grandfather Nurgle.

Each entry uses a short 3‑line format describing how da smelly ladz acted  
and how da scrap ended. The community votes whether the encounter was  
**WAAAGH-approved** or **not proppa'.**

---

## Contract

Deployed on Base:  
`0x2Ae6884A5D56C6CBe21750Ac4dB6C55A3B0bCA8C`  
https://basescan.org/address/0x2ae6884a5d56c6cbe21750ac4db6c55a3b0bca8c#code

Main file: `contracts/NurgleDaemonEncounterLog.sol`

---

## Example encounter

```solidity
recordEncounter(
  "Plaguebearer Host",
  "Da green ladz waddled forward gigglin' an' drippin' goo like dey were proud of it.",
  "Da scrap ended wiv clouds of stink, squishy noises, an' da boyz arguin' who stepped in what."
);

Voting
voteEncounter(1, true);   // WAAAGH-approved
voteEncounter(1, false);  // Not proppa'

Closing Note
A joyful chronicle of Grandfather’s rot —
da drippy ones, da giggly ones,
an' da ones dat explode when ya poke 'em too hard.
