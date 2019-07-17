# Rational Resources

## 0.9.0
* Added Ore tank types for SimpleConstruction.
* Added MetallicOre presence.
* Added MetalOre and Oxium to scanners for Classic Stock.
* Added several stock scanner modules to RR Scanners:
  * GPS to all.
  * KerbNet to all.
  * Biome scanner to ground and sea.
  * Asteroid analysis to ground.
  * (Per) Resource Analysis via CRP, Classic Stock (I might revert this one. Possible PAW spam.)
* Added Hexagen to Mun crust (Helium presence for CRP pending).
* Added atmo edge distributions for Default and Terra templates.
* Added ExoRock and ExoIce for airless worlds.
* Changed Ore tanks patch to only target stock Ore tanks.
  * Added Hydrates, Rock options.
* Fixed distributions settings for worlds changed by JNSQ.
* Fixed gas giant Hydrogen, Helium presence.
* Fixed mini drill abundance threshold, leave it unchanged.
* Finish balancing ISRU chains.
* Treat stock Oxidizer as LqdOxygen, remove LqdOxygen -> Oxidizer option. Due to balancing reasons, these two have a redundancy problem.
* Treat LiquidFuel as Dodecane.

## 0.8.6
* Added CarbonDioxide and Hydrates splitters to ISRU.
  * These and other ISRU chains pending balance pass.
* Added Star exo band templates (Population 1 ~ 3) with decreasing amounts of most things but Hydrogen and Helium.
* Added Water to Mun and Minmus polar biomes.
* Added MetalOre to stock Drill-O-Matics.
* Added small MetalOre presence to Minmus to help with base-building.
* Change SimpleConstruction ISRU to consume MetalOre.
* Fixed Ore tank patch to only active if CRP present.
* Fixed intake harvester patch to only active if CRP present.
* Enabled several non-MKS resources to appear in SCANsat resource overlay selection.

## 0.8.5
* Added parts:
  * ZZZ box Convert-O-Trons (will hold OmniConverters in Classic Stock mode). These are temporary parts and not to be used on permanent or long-term crafts. They are for testing the ISRU chains.
  * HECS-shaped resource scanners for: Surface; Sky (Atmo+Exo); Ocean.
  * Exo scoop. Supports Antimatter, karborundum, LqdHe3, Hydrogen, LqdDeuterium.
* Added features:
  * Atmosphere harvester and splashed-only intake modules to the stock XM-G50 radial intake.
  * Resource options to the stock Drill-O-Matics.
  * Mini Convert-O-Tron and Drill-O-Matic are no longer borderline unplayable. They are as terrible as they are on purpose and some of us don't like that.  
  * LqdCO2 secondary mode for stock NERV. Requires ReStock.
  * Atmo/exo harvester modules will not appear if KSPI is installed.
* No longer add resource scanners to stock parts (the ones that will still appear in the Surface Scanner are those added by CRP, not this mod).
* Added Easy Mode `RationalResourcesEasy` pseudo-mod. This prevents deletion of the stock fuel options in the Convert-O-Trons and causes Ore to not be nerfed as harshly. Ore remains available everywhere but will not pass 8% max (vs the default 15%).
* Added `RationalResourcesOverride` pseudo-mod. This provides for planet mods that change Kerbin and Sun and will want alternate resource templates for them.
* Buffed Minerite/Mineral abundance in Duna. Reduced RareMetal abundance in exchange.
* Changed all LqdHydrogen presence to Hydrogen and tuned abundances and ranges.
* Added yellow star atmo template (only provides exo resources).

"Pseudo-mods" in this context are mods whose purpose are only to activate extra patches. to activate a pseudo-mod, create a folder with its name in GameData or create a patch with a `:FOR[]` targeting the pseudo-mod.

## 0.8
* Pre-release
* CRP supported
* Classic Stock supported
* No ISRU configs
