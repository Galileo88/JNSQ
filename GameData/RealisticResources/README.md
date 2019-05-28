# Realistic Resources
Realistic Resources is inspired by [Realistic Atmospheres](https://github.com/OhioBob/Realistic-Atmospheres) made by [OhioBob](https://github.com/OhioBob/), and is designed to operate on the KSP Community Resource Pack and perform the following:
To strip out the entirely random resource distributions and to apply carefully crafted templates (groups of resource distributions) according to the logically expected class and composition of a body. While this mod is installed, un-configured bodies will have no resources at all.

This mod enables planet makers to easily assign custom and appropriate distributions to their planet packs and skip the headaches of figuring out and writing the individual nodes themselves, and assorting all of their writings into several per-resource config files.

## Templates
The following templates and resource types have been made available. Unique entries are templates exclusive to a stock planet, designed either to make that planet resemble an IRL celestial body or because it is an extreme oddity.
* Eve, a hybrid class methane + metal world, is not known (to me anyway) to be possible.
* Minmus, an entirely ice world cannot exist in the habitable zone of a star. It is made to possess Nitrogen and no metals.
* Mun, as the real Moon, is made to possess a large fraction of Oxygen and MetalOre.
* Duna, akin to Mars, is given a strong presence of Oxygen (in the ground only, there is no explicit metal oxide resource), and metals.


| Surface | Ocean | Atmosphere | Unique |
| --- | --- | --- | --- |
| Rock | Terra | Default (CO2-rich) | Eve |
| Rock-Metal | Nitrogen | Terra | Mun |
| Rock-Ice | Methane | Ice-Nitrogen | Minmus |
| Ice-Water | Ammonia | Ice-Methane | Duna |
| Ice-Methane | | Ice-Ammonia |
| Ice-Nitrogen | | Ice-Water (Thick, N2-rich) |
| | | Ice-Water (Thin, CO2-rich) |
| | | Gas (Jovian) |
| | | Gas (Uranian) |

## Resources
In the spirit of realism, this mod drastically reduces the presence of the stock "Ore" resource in order to starve the use of this omnipotent and exceedingly abstracted resource, and to encourage the use of the distinct and specialized resources. The exact ones used are named below as a heads-up to players:

**Surface and Atmosphere resources**
* Ammonia, CarbonDioxide, ExoticMinerals, Gypsum, LqdHe3, Hydrates, LqdHydrogen, MetalOre, Methane, Minerals, Nitrogen, Ore, Oxygen, RareMetals, Rock, Silicates, Substrate, Uraninite, Water.

**Ocean resources**
* LqdAmmonia, LqdCO2, LqdMethane, LqdNitrogen, LqdOxygen, Water.

## Compatibility
This mod purges resource distributions placed by most other mods. Untagged resource distributions are all deleted in the ModuleManager `:FINAL` pass. The whitelisting mentioned below largely only applies to global/universal placements, and nearly no specific/per-planet placements in order to prevent unwanted high concentrations like Karbonite on Eve.

**Whitelisted resources**
* Antimatter, ArgonGas, LqdHe3, LqdHydrogen, XenonGas. (used by at least the Near Future Tech and Far Future Tech mods).
* Karbonite, Karborundum.
* __Not__ Dirt (used only by USI MKS. Its absence should be but a minor hurdle to MKS players).