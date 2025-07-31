# Known Issues

If your bug is not listed here, search the [open issues](https://github.com/rgx-org/issue-tracker/issues).  
If it's not there either, open a [new issue](https://github.com/rgx-org/issue-tracker/issues/new) or report it in the Discord's [bug-reports section](https://discord.com/channels/1371314292154044426/1400384221108895894).  

## Notable Missing Features
* Items without descriptions/ropts are placeholders.
* Ropts marked `(WIP)` do not function.
* Archer, Rogue, and Sage jobs are disabled.
* Bows are not yet usable.

## General
* Sometimes you warp to the wrong place (esp on F15?). Workaround with `@unstuck`
* There's no timer on logging out (intentional for testing).
* Reva’s bonfire shop may break, especially in parties.
* Breaker Zone portals sometimes spawn behind walls (workaround: `@endzone`) 
* Some skills fail silently despite message settings. Report these.
* Many status effects have incomplete or erroneous descriptions

## Mechanics
* The `Backwave` keyword doesn't do anything.
* Some jobs have erratic HP across floors in a certain tier.
* Reflect Shield can trigger auto-attack autospells under some conditions (might become a boon or ropt?)
* Cooldown resets aren't shown on the hotkey bar (e.g. Instant Reset).
* Damage block effects (e.g. Safety Wall, Kyrie Eleison) may have desync'd visuals and damage activation.
* Suction effects do not always properly vacuum monsters to you.

## Visuals
* Body color effects (e.g., Poison, Heat, Weapon Quicken, Energy Quicken) don't stack together well.
* Day/night states sometimes reset on client restart, affecting lighting.
* Party members may show the wrong weapon animation under certain conditions.
* Some effects (e.g. Chill) show on hidden units.
* Lightning Bolt's animation has weird delay on it when used by mobs.

## Exploits
* Skill Resetters are not tier locked.
* Some items have incorrect trade/drop restrictions.
* Mimics can be easily identified using a certain client-side exploit.

## Enemies / AI
* Goblin King sometimes takes omega damage around ~50% HP.
* Enemies running away ignore Provoke (not sure if this is a bug or feature yet).