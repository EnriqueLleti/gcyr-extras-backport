GCYR Extras (Backport for GregTech CEu 7.4.1)

This repository contains a backport of GCYR Extras, originally developed by the GCYR Extras contributors.

Original project: https://github.com/jmoiron/gcyr-extras?tab=readme-ov-file
Original project on curseforge: https://www.curseforge.com/minecraft/mc-mods/gcyr-extras

This project is released in accordance with the original license (GPL), and all credit for the original implementation belongs to its original authors. This repository only contains the modifications required to make the mod compatible with older versions of its dependencies.

What changed?

Compared to the original project, this version has been adapted to work with:

Minecraft 1.20.1
Forge
GregTech CEu 7.4.1
Gregicality Rocketry 0.2.7

The original project targets newer versions of GregTech CEu and Gregicality Rocketry.

![](icon.png)

# gcyr extras

gcyre is an addon mod for [gregicality rocketry](https://github.com/Argent-Matter/gcyr). At present it does two things:

* adds 4 additional tiers of rocket & tank
* two new multiblocks + casings
* if [GT--](https://github.com/Arborsm/GT--) is present, it registers its rocket fuels as usable in rockets

The additional tiers provide modpack authors with extra flexibility in gating custom planets.

No recipes are provided for the additional rocket engines/tanks.

## orbital mining

Two new multiblocks allow "mining" from planets/moons from orbit. These are essentially void miners.

### orbital laser miner

Similar to the fusion ring, with its own custom renderer. LuV tier machine that produces ores in exchange for power+coolant. Ships with recipes for GCYR's
luna/mercury/venus/mars.

![](img/laser_miner.png)

### orbital gas miner

A large multiblock gas collector that collects gas from orbit. Meant for gas giants, which may be added by pack authors. Only ships with an overworld recipe
that is mostly there for testing, where it functions as a slightly better version of the regular gas collector.

![](img/gas_miner.png)
