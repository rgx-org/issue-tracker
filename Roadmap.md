# Rune Breakers Roadmap
### Current version: v0.25 ~ dev00 closed test
Outline of **major** features for upcoming versions.  
A version is considered completed when all features are implemented. Lists are non-comprehensive and will fall out of date from time to time. Entries may be added, reorganized, or deleted over time. This roadmap started as an internal organization list for myself, I'm sharing it publicly to give people an idea of what is upcoming, but these are not feature promises or guarantees in any way.

The next version has a detailed "todo list", while later versions have simple loose outlines of features.

## v0.3 ~ Dark Lord
**Goal**: A mostly complete T2 (pre-transc) experience in the Lost Realm.
- [ ] Breaker Manual / Tipbox pages
- [ ] F16-17
  - [ ] Bacsojin (todo: MVP)
  - [ ] Jirant (todo: MVP & FoE)
- [ ] Finish "Mostly done" jobs
  - [ ] Crusader
  - [ ] Monk
  - [ ] Blacksmith
  - [ ] Sage
- [ ] F15 Boons for implemented jobs
- [ ] Finish WIP ropts
- [ ] Add status effect descriptions
- [x] Run state improvements
  - [x] Better handling of server restarts / lost runs
  - [x] Party state improvements
- [ ] Overhaul monster aggro/targeting system
- [ ] Implement Summons (new system)
- [ ] Alchemist job
  - [ ] Base kit
  - [ ] Ropts
  - [ ] Boons
- [ ] F18-19
  - [ ] Vesper
  - [ ] Evil Snake Lord
- [ ] Add remaining Tutorials
  - [ ] Intermediate
  - [ ] Advanced
- [ ] Crossbows (new weapon type)
- [ ] Hunter job
  - [ ] Ammo rework
    - [ ] Figure out Bow access?
  - [ ] Finish Archer
  - [ ] Base kit
  - [ ] Ropts
  - [ ] Boons
- [ ] Rogue job
  - [ ] Base kit
  - [ ] Ropts
  - [ ] Boons
- [ ] Bard/Dancer job
  - [ ] Base kit
  - [ ] Ropts
  - [ ] Boons
- [ ] F20 (Dark Lord)
- [ ] Berserk builds (Backwater)
- [ ] Ropt all remaining items
  - [ ] Phase 1: Assignments
  - [ ] Phase 2: Implementations
- [ ] Implement 'invaders' (new system)
  - [ ] Loot goblin and 1 or 2 more for now.
- [ ] Challenge floors
  - [ ] F3 (Angeling)
  - [ ] F7 (Menblatt)
  - [ ] F9 (Tao Gunka)
  - [ ] F12 (Turtle General)
  - [ ] F14 (CTM)
  - [ ] F17 (Celine Kimi(?))
  - [ ] F19 (White Knight)
- [ ] Implement 'Sequences' (new backend system)

## Interlude: Prototype test (Public)
**Goal**: Limited weekend-only public tests to raise some initial awareness about the project.
* Might happen before v0.3 is finished.
* Will be focused on fixing bugs and community management.
* Likely will do 2 or 3 tests, depending on how they go.

## v0.35 ~ Survival Mode
**Goal**: Create a more comprehensive community experience with some replayable end-game mode and more progression/customization systems.
* Survival Mode
  * Accessible by T2 characters who clear F20
  * No permadeath, running out of Lives resets the run
  * Endless waves of scaling monsters, each wave being on a timer
  * Gain points based on how long a party lives for
* Main town: Hiraeth
* Achievement System
* Quest System
* Costume System
* Storage System
  * Mostly for sharing costumes atm
* Stylist
  * New stylist room
  * New palettes
* Website
  * Better Control Panel experience
  * Profile pages w/ char & run statistics
  * Score leaderboards
  * Cash shop ([plz.](https://www.youtube.com/watch?v=7NgoTbNKPzs))
* Security hardening

## Interlude: Pre-alpha test (Public)
**Goal**: After v0.35 I will open up the server to public testing for some time.
* Add more community support features, both in and out of game (Guilds, etc)
* Learn best ways to grow & support the community
* Figure out moderation strategies (in and out of game)
* Advertising?
* Probably, lots of bug fixing and feedback listening
* I don't know how long I'll leave this up for.

## v0.4 ~ Lord of Death
**Goal**: Addition of the third content tier, from F21-F25
* F20 boons
* Implement T3 (transcendent) jobs
* Round 1 of T3 item/ropt design
* Add F21-F25

## v0.5 ~ Randgris
**Goal**: Finishes the core Lost Realm experience, wrapping up the initial pass on T3 jobs/systems and the main boss.
* F25 boons
* Add F26-30
* More T3 item/ropt design
* Survival Mode will likely need major updating/reworking by this point

## v0.55 ~ Ingrid
**Goal**: A complete Lost Realm experience, encompassing all floors from F1-30, with a new higher difficulty option.
* T3 Challenge Floors
* Add optional "True Boss"
* Valkyrie difficulty
  * Elite mutations?
  * Expand invader system? (PCNPC Invasions?)
* Spectating runs?

## v0.6 ~ Reginleif
* **Goal**: Implementation of the open world component, allowing players to truly "Break Free" of the Lost Realm.
* Reclaim Hugel
* Add ~3 towns and ~30ish fields (Hugel to Alde to Einbroch or Lhz?)
* Add 2~3 dungeons (Abyss Lake, Magma, Mines?)
* Add first Super Boss (Guild-scale fight)
* Figure out fun character optimization systems, add early versions of them
* Some type of field grinding mechanics & gimmicks (Fever style? MVP respawn timer reduction based on mobs killed?)

## v0.65 ~ Distributed regional map-servers
* **Goal**: Stand up map-servers in various regions to allow players to play in low ping
* Dynamic regional map-servers for Lost Realm and other instances?
* How to handle fields? I don't like channel systems.

## Interlude: Public Alpha
**Goal**: Refocus on community aspects
* Probably need heavy guild system refinements?
* Town mechanics...?

## v0.7 ~ Balance focus
**Goal**: Hoping to have enough data and feedback to get serious about the job ecoystem and item balance.
* Create internal tools for measuring balance better
* Maybe an external character calc/builder...?

## v0.8 ~ Nightmare Instances
**Goal**: Add new Nightmare instance system
* Add 2 or 3 Nightmare instances (Abyss Lake and ???)
* 4-8 player instances with Lives and some type of entrance requirement
  * heavy teamwork focus
  * some type of competition system with another group...?
* Entrances located at final floor of some dungeons

## v0.9 ~ PVP Modes
**Goal**: Design and implement modes to facilitate some type of PVP play
* Follow the fun based on where the game is at
* Small scale PVP? (1v1-5v5)
* Larger scale PVP? (16-24? Some type of WoE style?)
* Guild Wars (GBF style), but in field grind maps?
* PvPvE dungeons? Boss rush competitions?

## Interlude: Public Beta
**Goal**: Focus on stability and refinements to prepare for release
* Refine CI/CD pipelines
* Final exploit/bugfixes, overall refinements

## v1.0 ~ Release
**Goal**: The game is in a "fully playable, content complete" state for the current needs.
* Start preparing for the next world map expansion
* Create an event schedule? Maybe a guild war schedule?
* idk i hope it's fun though, will be happy to be here.
