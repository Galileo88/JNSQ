# Rational Resources

## 1.0.2
* Updated SSPXr extras config. Caught redundant/overlapping subtypes.
* Added WBI logistics module to all stock parts when TankSwitchForSquad patch is active and Rational Resources is in Classic Stock play mode.
* Tiny adjustments to nuclear engines.

## 1.0.1
* Moved B9 tank definitions to core folder to prevent breakage of established mods containing RR tank type patches.

## 1.0
* Split all added parts and active stock part modifications (except the experiment and the scanners) into their own mod, `RationalResourcesParts`. This allows RR itself to be a resource placement mod and absolutely nothing more, for those who want to bundle it or those who just don't want parts.
* Added nuclear engines:
  * "Panther" clone "Main Coon" nuclear turbojet with built-in nuclear reactor.
  * "NERVA" clones. The "O" edition is high thrust and can choose between Carbon Dioxide and Water. The "R" edition is high Isp and can choose between Hydrogen, Ammonia and Methane. Their mode switch feature requires **B9 Part Switch 2.10** or later.
* Added/Updated LqdHe3 presence via ExoRock, ExoIce, Mun templates.
* Added LqdHe3 to RR Ground Scanner.
* Added Water to Duna.
* Reduced MetalOre tank volume. A full tank weighed far, far too much.
* WBI Classic Stock:
  * Changed nuclear engines to use Classic Stock resources.
  * Added OmniConverters for cycling Atmosphere and CompressedAtmosphere.
  * Provided tank types. Most of Pathfinder's tank types available to all stock tanks through the Extras config.
* Fixed small error in OPM science config.
* Fixed XM-G50 intake patch to use harvester modules for ocean filtering. Intake modules showed very undesired behavior.
* Changes concerning Eve oceans and Kerosene/LiquidFuel:
  * Added large Ore presence to Eve Shallows biome to compensate for a lack of proper heavy hydrocarbon resource outside of RealFuels.
  * Added **Extras**: RR_EveLiquidFuelOcean.cfg -- what it says on the tin. Also adds a LiquidFuel harvester module to the XM-G50 air scoop. The idea of this is both very necessary on one hand and very silly on the other hand so it will not be active by default and will not be endorsed for use elsewhere.
  * Removed CRP LqdMethane from Eve oceans as this is cryogenic and should not exist at a hot inner planet. It will still appear at any decent world with hydrocarbon oceans-- cold outer worlds.
  * Classic Stock Hydrokerbon presence is unchanged as it meets the mark.


## 0.9.1
* Added support for the Outer Planets Mod.
* Added Extras folder with optional configs.
  * Moved stock Ore converters remover here.
  * Added `RationalResourcesSquad`. This extra applies B9PS and all fuel options to all stock tanks. This also adds non-redundant tank types to CryoTanks if that is installed. (Does not affect CryoTanks if installed alongside WBI Classic Stock.)
  * Added patch for Nertea's SSPXr.
  * Added LqdHe3 tank type which only appears for Galaxies Unbound (a planet pack).
  

## 0.9.0
* Added atmo edge distributions for Default and Terra templates.
* Added ExoRock and ExoIce templates for airless worlds.
* Added Hexagen to Mun crust (Helium presence for CRP pending).
* Added MetallicOre presence.
* Added MetalOre and Oxium to scanners for Classic Stock.
* Added Ore tank types for SimpleConstruction.
* Added Planet Classification experiment.
  * Added to stock M4435 Narrow-Band Scanner.
  * Supports JNSQ.
* Added several stock scanner modules to RR Scanners:
  * GPS to all.
  * KerbNet to all.
  * Biome scanner to ground and sea.
  * Asteroid analysis to ground.
  * (Per) Resource Analysis via CRP, Classic Stock (I might revert this one. Possible PAW spam.)
* Added temporary clones of the stock 'Bread' tanks with B9PS and Tweakscale patch. These can hold all RR tank types. Better tank models and sizes coming.
* Changed Ore tanks patch to only target stock Ore tanks.
  * Added Hydrates, Rock options.
* Fixed distributions settings for worlds changed by JNSQ.
* Fixed gas giant Hydrogen, Helium presence.
* Fixed mini drill abundance threshold, leave it unchanged.
* Finish balancing ISRU chains.
* Removed CO2 multimode patch for stock NERV engine. It was found to conflict with the Kerbal Atomics multimode patch. This patch may return as an example for making other CO2 NTR configs.
* Treated stock Oxidizer as LqdOxygen, remove LqdOxygen -> Oxidizer option. Due to balancing reasons, these two have a redundancy problem.
* Treated LiquidFuel as Dodecane.

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
