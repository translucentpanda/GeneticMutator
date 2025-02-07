# Genetic Mutator

Are you a mostly solo player and wish you could play around with the Gene Trait mechanics without having to catch an absurd amount of dinos? 

Are you the designated tribe breeder and find yourself spending a lot of time watching eggs hatch with little payoff? 

This might be the mod for you!

### Description
This mod adds a variant of the Tek Trough that boosts the mutation rates of adult dinos and adds Gene Traits to baby dinos that are hatched or born within its effect radius.  There are no separate engrams or resource / fuel requirements; simply pick up your existing Tek Trough (or craft the original) and place it down as a Tek Mutagenic Trough. By changing the mutagens dispersed by the trough, you can change the frequency of mutations and the traits you'll find on your dinos. You won't be able to target specific stat mutations, but that's what some of the Gene Traits you'll find are for!

### Trough Settings
In addition to the default Tek Trough configurations, you'll find the following new options under a section titled "Mutagens:"

##### Mutation Mode
- *Blocked*: Prevents all mutations and enables you to quickly build up some clean base dinos for mass breeding. If you just want clean dinos while you're looking for something else, this is the mode for you.
- *Frequent*: Boosts the mutation rate to 50% and retains the default 3 chances to obtain a mutation from one of the parents. Will you get a lucky 2 rolls in your preferred stat? 3!? Maybe!
- *Steady*: Increases the mutation rate to a guaranteed 100%, but only gives you a single mutation. If Frequent is too much of a gamble, you can use this mode to gradually build your way up to your perfect dino. 

##### Gene Mode
- *Inherit*: Babies will inherit one random Gene Trait from each parent, if possible. Combine this with the Genetic Cloning mod to end up with too many copies of Gene Traits.
- *Wild*: The more balanced option, this mode immitates the Gene Traits of wild dinos. The Traits you find will depend on the type of dino you breed.
- *Boosted*: Babies will get 2 traits for their species, with a chance for a 3rd, and another chance that one of the traits to be upgraded straight to 3! I don't need balance, I need Gene Traits!

##### Debug Mode
- Enabling debug mode will add some extra text to the HUD for dinos affected by the trough. This can be useful for verifying the mode settings at a glance and will help you see how overlapping troughs might be affecting your dinos. If babies aren't coming out like you expect, see what's actually being applied to the parents with Debug Mode!

### GameUserSettings.ini
The only config options you'll find are for the boosted chances (inspired by Shiny!). Everything else you'll find on the trough itself!
- BoostedBonusTraitChance=0.33
- BoostedTraitUpgradeChance=0.33

### Disclaimers
- This mod is primarily intended for solo players and smallish tribes. *You may experience performance drops with massive, server-wide breeding farms!*
- This mod is meant to incentivize hatching/birthing and active participation. *It may not work with offline breeding mods!*
- This mod changes mutation rates the same way many other mods do, so whatever means you last used to change the mutation chance will be what ultimately affects the parents that you're breeding, whether that's treats or the trough. If you prefer treats, that's okay! Just feed them *after* they are affected by the trough or remove them from the trough area first just to be safe!

### Source Code
If you want to incorporate similar changes into your own mods, the source code for this mod (and my other mods) can be found here: https://github.com/translucentpanda?tab=repositories

### Changelog

##### 02/06/2025 (Version 1)
- Initial release.
