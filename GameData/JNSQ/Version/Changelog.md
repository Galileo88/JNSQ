# JNSQ

## 0.9.0 Change log 
:bookmark: *KSP 1.8.1+*
* Added Localization for biomes, body descriptions and loading screen tips:
  * German - Danke Woeller
  * Italian - Grazie Sigma88
  * Spanish - Gracias Adstri (needs proof reading)
* Added (Moved in) Karborundum engine tweak from Rational Resources.
* Updated "No ghosts" sunflare feature to work in scatterer mode.
* Updated antenna patch to handle NF Exploration's antenna module (**not** the reflector module).
* Updated KK bases:
  * Added AirBase (airplane) Boneyard, 30km south west of KSC.
  * Added C. McAuliffe space center.
  * Added Welcome Island Harbor.
  * Adjusted hangar mass limits, raised hangar prices, buffed standalone util building's storage volume.
  * Adjusted C. Yeager space center to not have a box mountain range around it anymore.
  * Adjusted Darude base concerning static positions and a contract waypoint marker. Any landed craft here may be offset or destroyed.
  * Adjusted tile colors to match terrain texture updates.
  * All bases now aligned to the cardinal directions. North runway actually points north. This is due to a KK fix only available for KSP 1.8 and later.
  * Fixed CRP patch structure. It's now contained in a single file. It applies to all fuel depot statics. It will provide WBI Classic stock resources if the WBI `ClassicStock` pseudo-mod is detected.
  * Made observatory centers discoverable (as anomalies) via SCANsat.
* Updated asteroids: Now they are only 3.3x dense as stock where they were 33x which was far too much.
* Updated planet terrain textures to use KSP new terrain shaders.
* Updated Jool and Lindor:
  * Added some more wow factor.
  * Adjusted/Fixed HazardousBody. Jool-diving remains an exercise in extreme steam bathing.
  * Lindor's rings now have a detail texture to simulate granular debris fields.
* Updated Kerbin: expanded arid biomes region southward around and over Darude base.
* Updated Moho: new biome map + Rational Resources config.
* Updated Nara: new surface + new biome map.
* Updated Minmus: new surface + no pixelation.
* Update Huygen: Scatterer atmosphere adjustments.
* Updated Rational Resources bundle to 1.1.0. [Full changelog here](https://github.com/JadeOfMaar/RationalResources/blob/master/GameData/RationalResources/Version/Changelog.md#110).

## 0.8.6 Change log
:bookmark: *KSP 1.7.1 ~ 1.7.3*
* Updated Jool and Lindor:
  * Made Lindor's rings more opaque.
  * New textures and updated biome maps.
  * Added Huygen, a moon of Lindor, including all associated revisions.
  * Added local asteriod fields.
  * Revised orbit of Riga to accommodate Huygen.
  * Changed Bop's orbit to prograde. It remains retrograde for Principia only.
* Fixed KK center headings. This fix may not apply in KK for KSP 1.7 or older. Confirmed for KSP 1.8.
* Rotated palms trees around KSC.
* Updated HazardousBody heat parameters.
* Updated delta-V map: Darkened some gray texts and added Huygen.
* Added AntennaRange.png: a chart for measuring how much of what stock antennas (or the JX2 antenna) are required for many situations.
* Replaced loading screen images. Emphasis was too far on the part mods and away from the bodies; Bodies have heavily changed since previous images were produced.

## 0.8.5 Change log
* Added MachFX tweak: Changed plasma transition range from Mach 2.5 ~ 3.5 to Mach 4.5 ~ 6.5, thanks to players: **CalicoJackRackam, Rocketology**.
* Added 3x multiplier to SCANsat scanner altitudes.
* Adjusted Kerbal Konstructs facilities:
  * Buffed prices on everything. Funds ROI at business facilities break-even at 3 years with 1 kerbal or 1 year with max staff.
  * Unlocked DLC-replacing sites and KSCHarbor launch points.
  * Added features to Woomera2 and made it now override Woomerang.
  * Fixed tile grass colors at all sites.
  * Added and removed color presets.
* Added new, more defined celestial body textures. Nudging at Squad that we don't need a new shader to play the "stock visual terain" game.
* Adjusted ocean colors.
* Updated Rational Resources bundle to 1.0.2. [Full changelog here](https://github.com/JadeOfMaar/RationalResources/blob/master/GameData/RationalResources/Version/Changelog.md#102).
* Removed installer (.exe) option. Unfortunately it was proven more inconvenient than convenient.

## 0.8.1 Change log
* Fixed 0.8 lag fest.

## 0.8 Change log
* Fixed Breaking Ground compatibility.
* Updated Rational Resources bundle to 1.0.1. [Full changelog here](https://github.com/JadeOfMaar/RationalResources/blob/master/GameData/RationalResources/Version/Changelog.md#101).
* Added loading screen images thanks to KSP forum users: **Nertea, Norcalplanner, Rock3tman_, Saltshaker, StarStreak2109, Zorg**.
* Added more loading tips.
* Added several Kerbal Konstructs facilities. 
  * These require only OSSNTR (Omega's Stockalike Structures: No Textures Required). 
  * Most of these allow for KerbinSide airport alike experience. All of these have (not necessarily all at once) modules on them for trading fuel, expanding antenna coverage, staffing with kerbals and farming funds or science, spawning a VTOL or rover on something other than KSC's launchpad or runway, recovering for up to 50%(?) funds value in career mode. Two harbors included for water launching. Most of these need to be spotted with SCANsat's anomaly detector and everything needs to be purchased in career mode.
* Fixed Kerbin biome map: Arid Mountains was missing.
* Updated CelesitalBodies.pdf: fixed minor error.
* Updated Duna biome map: 
  * 14 biomes including 5 variants of craters.
* Updated Eve biome map: 
  * Added 11 seas named after modders or mods whose names relate to monsters.
  * Methane Lakes renamed to Petrol Lakes.
* Updated Tam biome map: 
  * Added 3 biomes. Thanks to CoriW, maker of Planet Arkas.
* Updated solar panel catch-all config.
* Updated Rational Resources settings:
  * Eve's Shores now always Ore rich to make LFO (Kerolox) production from (near to the) Petrol Lakes convenient.
  * Added/Fixed some options for atmo edge mining.
* Updated Visuals/Immersion:
  * Fixed Eve planetshine color. Should no longer be default purple.
  * New clouds for Kerbin and Laythe. 
  * Fog For Laythe.
  * Dust Storms for Duna.
  * Scatterer tweaks.
  * Palm trees around KSC to add some character.
  * Icebergs for Kerbin.
  * New scatter objects on other bodies. (More to come later.)
  * New boulder meshes on all bodies.
  * New coniferous tree mesh to replace the stock pine tree.
  * New anomalies on a few bodies. (More to come later.)
* CKAN Indexed.
  
## 0.7 Change log
 * Performace pass.
 * Adjust the distance in which scatter objects are rendered, including BG scatter to ensure better performance.
 * Fixed Duna Scatterer exposure and high altitude pop in.
 * Adjusted RationalResources to make sure the ore tanks only avctivate if CRP is present.
 * New ocean texture for Kerbin, Eve and Laythe. Does not show when Scatterer is installed.
## 0.65 Change log
 * Fix issues with chute not deploying.
## 0.6 Change log
 * Fix sun flare exposure with scatterer installed.
## 0.5
:bookmark: *KSP 1.7.1  or newer*
* Implemented changes necessary for Kopernicus 1.7.1.
* Ground scatter updates, landClasses revisions.
* Added **Breaking Ground** DLC terrain objects.
* Added RemoteTech support, donated by DanShuTV on Twitch.
* Added compatibility patch for **Probes Before Crew**.
* Added optional mods:
  * FinalFrontier ribbons.
* Revised surface textures and tiling, deleted CTTP.
* Disabled spherical mesh for some bodies.
* Adjusted Kerbin's brightness, saturation and contrast.
* Darkened surface of Dres.
* Retextured Minmus and Hamek; new biomes.
* Modified orbit of Minmus; added alternate stable orbit for Principia.
* Made Kronometer compatible with ReScale (not currently updated for JNSQ).
* Disabled Kopernicus solar panel module.
* Very slight update to dV map: swapped locations of "Total" and "Low Orb Ins"
* Updated Sigma-TweakChutes.
* Fixed MechJeb2 config.
* Replaced **Realistic Resources** bundle with **Rational Resources**. Please uninstall the former if it is present.
* Sunflare:
  * Updated Unity version to resemble scatterer version.
  * Added toggle in `JNSQ\JNSQ_Configs\SunflareMode.cfg`
  * Added condition for ghost-less Unity sunflare. Create folder "JNSQNoGhosts" in GameData to activate it.
* Updated biome maps:
  * Fixed Kerbin Northern Sea reaching south.
  * Removed unwanted Shores and Arctic Sea at the southern ice cap.
  * Added Minmus "brown" biomes.
  * Krenwich Delta renamed to Krenwich Sea (Kerbin, Laythe).
* Added CelestialBodies.pdf
  
## 0.4
:bookmark: *KSP 1.7.0 or older*
* Initial Release
