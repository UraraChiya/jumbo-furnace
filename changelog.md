## 1.19.2-3.0.0.0
* Updated Jumbo Furnace to Minecraft 1.19.2 (requires forge 43.1.0 or higher)
* This is a save-compatibility-breaking update. Jumbo Furnaces in old worlds may lose their data or disappear entirely.
* Removed orthodimensional hyperfurnaces. Jumbo furnaces can now be upgraded with jumbo furnaces instead. This is still specified via the `jumbofurnace:multiprocessing_upgrade` item tag.
* Mods using forge's burn time api for their fuel items can now specify a burn type for the "jumbofurnace:jumbo_smelting" recipe type, which will take precedence over normal furnace fuel values when used as fuel for a jumbo furnace.
* Vanilla-furnace smelting recipes with cooking times longer than jumbo furnace's cooking cycle time (specified in Jumbo Furnace's serverconfig) can no longer be cooked in jumbo furnaces.
 