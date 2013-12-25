FTB-Monster-Server-MCPC-1.6.4-Help
==================================

This is the crash log, how do I fix it and make the server run?


---- Minecraft Crash Report ----
// This is a token for 1 free hug. Redeem at your nearest Mojangsta: [~~HUG~~]

Time: 24/12/13 10:50 PM
Description: Exception in server tick loop

cpw.mods.fml.common.MissingModsException
	at cpw.mods.fml.common.Loader.sortModList(Loader.java:244)
	at cpw.mods.fml.common.Loader.loadMods(Loader.java:491)
	at cpw.mods.fml.server.FMLServerHandler.beginServerLoading(FMLServerHandler.java:99)
	at cpw.mods.fml.common.FMLCommonHandler.onServerStart(FMLCommonHandler.java:350)
	at net.minecraft.server.dedicated.DedicatedServer.func_71197_b(DedicatedServer.java:92)
	at net.minecraft.server.MinecraftServer.run(MinecraftServer.java:634)
	at net.minecraft.server.ThreadMinecraftServer.run(ThreadMinecraftServer.java:16)


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- System Details --
Details:
	Minecraft Version: 1.6.4
	Operating System: Windows 8 (amd64) version 6.2
	Java Version: 1.7.0_40, Oracle Corporation
	Java VM Version: Java HotSpot(TM) 64-Bit Server VM (mixed mode), Oracle Corporation
	Memory: 2992228440 bytes (2853 MB) / 4116709376 bytes (3926 MB) up to 4116709376 bytes (3926 MB)
	JVM Flags: 3 total; -Xms4096m -Xmx4096m -XX:PermSize=256m
	AABB Pool Size: 0 (0 bytes; 0 MB) allocated, 0 (0 bytes; 0 MB) used
	Suspicious classes: FML and Forge are installed
	IntCache: cache: 0, tcache: 0, allocated: 0, tallocated: 0
	CraftBukkit Information: 
   Running: 
   Failed to handle CraftCrashReport:
java.lang.NullPointerException
	at org.bukkit.Bukkit.getName(Bukkit.java:72)
	at org.bukkit.craftbukkit.v1_6_R3.CraftCrashReport.call(CraftCrashReport.java:19)
	at net.minecraft.crash.CrashReportCategory.func_71500_a(CrashReportCategory.java:106)
	at net.minecraft.crash.CrashReport.func_71504_g(CrashReport.java:58)
	at net.minecraft.crash.CrashReport.<init>(CrashReport.java:40)
	at net.minecraft.server.MinecraftServer.run(MinecraftServer.java:693)
	at net.minecraft.server.ThreadMinecraftServer.run(ThreadMinecraftServer.java:16)

	FML: MCP v8.11 FML v6.4.49.965 Minecraft Forge 9.11.1.965 155 mods loaded, 155 mods active
	mcp{8.09} [Minecraft Coder Pack] (minecraft.jar) Unloaded
	FML{6.4.49.965} [Forge Mod Loader] (craftbukkit.jar) Unloaded
	Forge{9.11.1.965} [Minecraft Forge] (craftbukkit.jar) Unloaded
	AppliedEnergistics-Core{rv14.finale2} [AppliedEnergistics Core] (minecraft.jar) Unloaded
	CodeChickenCore{0.9.0.7} [CodeChicken Core] (minecraft.jar) Unloaded
	denLib{3.1.35} [denLib] (minecraft.jar) Unloaded
	Evoc{1.0.0} [Evoc] (minecraft.jar) Unloaded
	InfiniBows{1.2.0 build 14} [Infinity Bow Fix] (minecraft.jar) Unloaded
	MobiusCore{1.0.4} [MobiusCore] (minecraft.jar) Unloaded
	NotEnoughItems{1.6.1.8} [Not Enough Items] (NotEnoughItems 1.6.1.8.jar) Unloaded
	PowerCrystalsCore{1.1.8} [PowerCrystals Core] (PowerCrystalsCore-1.1.8-10.jar) Unloaded
	switches|pistontweak{1.3.0 build 25} [Switches|PistonTweak] (minecraft.jar) Unloaded
	TConstruct-Preloader{0.0.1} [Tinkers Corestruct] (minecraft.jar) Unloaded
	DamageIndicatorsMod{2.9.1.9} [Damage Indicators] (1.6.4 DamageIndicatorsv2.9.1.9.zip) Unloaded
	betterstorage{0.7.3.38} [BetterStorage] (1.6.4.BetterStorage_0.7.3.38.zip) Unloaded
	advancedgenetics{v1.1} [Advanced Genetics] (advancedGenetics_v1.1.jar) Unloaded
	Agriculture{1.0.0} [Agriculture] (Agriculture-1.6.2-1.2.2.jar) Unloaded
	AppliedEnergistics{rv14.finale2} [Applied Energistics] (appeng-rv14-finale2-mc16x.jar) Unloaded
	ATG{0.9.3} [Alternate Terrain Generation] (ATG-1.6.4-0.9.3.jar) Unloaded
	Autoutils{1.0.1} [Autoutils] (autoutils-1.6.4-1.0.1.jar) Unloaded
	Backpack{1.22.25} [Backpack] (backpack-1.22.25-1.6.x.zip) Unloaded
	BasicComponents{1.0.0} [Basic Components] (Basic_Components_v1.0.0.18.jar) Unloaded
	bdlib{0.9.2.7} [BD Lib] (bdlib-mc164-0.9.2.7.jar) Unloaded
	BiblioCraft{1.5.3} [BiblioCraft] (BiblioCraft[v1.5.3].zip) Unloaded
	BiblioWoodsBoP{1.3} [BiblioWoods Biomes O'Plenty Edition] (BiblioWoods[BiomesOPlenty][v1.3].zip) Unloaded
	BiblioWoodsForestry{1.3} [BiblioWoods Forestry Edition] (BiblioWoods[Forestry][v1.3].zip) Unloaded
	BiblioWoodsNatura{1.1} [BiblioWoods Natura Edition] (BiblioWoods[Natura][v1.1].zip) Unloaded
	BigReactors{0.2.8A} [Big Reactors] (BigReactors-0.2.8A.jar) Unloaded
	BuildCraft|Builders{4.2.1} [BC Builders] (buildcraft-A-1.6.4-4.2.1.jar) Unloaded
	BuildCraft|Core{4.2.1} [BuildCraft] (buildcraft-A-1.6.4-4.2.1.jar) Unloaded
	BuildCraft|Energy{4.2.1} [BC Energy] (buildcraft-A-1.6.4-4.2.1.jar) Unloaded
	BuildCraft|Factory{4.2.1} [BC Factory] (buildcraft-A-1.6.4-4.2.1.jar) Unloaded
	BuildCraft|Silicon{4.2.1} [BC Silicon] (buildcraft-A-1.6.4-4.2.1.jar) Unloaded
	BuildCraft|Transport{4.2.1} [BC Transport] (buildcraft-A-1.6.4-4.2.1.jar) Unloaded
	ChickenChunks{1.3.3.3} [ChickenChunks] (ChickenChunks 1.3.3.3.jar) Unloaded
	Chisel{1.5.0} [Chisel] (chisel-1.6.4-1.5.0fix.jar) Unloaded
	CoFHCore{2.0.0.b11b} [CoFH Core] (CoFHCore-2.0.0.b11b.jar) Unloaded
	CoFHLoot{2.0.0.b11b} [CoFH Loot] (CoFHCore-2.0.0.b11b.jar) Unloaded
	CoFHMasquerade{2.0.0.b11b} [CoFH Masquerade] (CoFHCore-2.0.0.b11b.jar) Unloaded
	CoFHSocial{2.0.0.b11b} [CoFH Social] (CoFHCore-2.0.0.b11b.jar) Unloaded
	CoFHWorld{2.0.0.b11b} [CoFH World] (CoFHCore-2.0.0.b11b.jar) Unloaded
	CompactSolars{4.4.19.224} [Compact Solar Arrays] (compactsolars-universal-1.6.4-4.4.19.224.zip) Unloaded
	CompactWindmills{1.0.2.2} [CompactWindmills] (CompactWindmills+MC.1.6.4+v.1.0.2.2.jar) Unloaded
	CCTurtle{1.58} [ComputerCraft Turtles] (ComputerCraft1.58.zip) Unloaded
	ComputerCraft{1.58} [ComputerCraft] (ComputerCraft1.58.zip) Unloaded
	CraftHeraldry{1.0.3} [CraftHeraldry] (CraftHeraldry 1.0.3.zip) Unloaded
	DenPipes{2.1.18} [DenPipes] (DenPipes-1.6.4-2.1.18.jar) Unloaded
	DenPipes-Emerald{1.1.6} [DenPipes-Emerald] (DenPipes-Emerald-1.6.4-1.1.6.jar) Unloaded
	DenPipes-Forestry{1.1.8} [DenPipes-Forestry] (DenPipes-Forestry-1.6.4-1.1.8.jar) Unloaded
	DragonAPI{release} [DragonAPI] (DragonAPI 1.6 v10h.zip) Unloaded
	DyeTrees{beta} [Dye Trees] (DyeTrees 1.6 v10b.zip) Unloaded
	emashercore{1.2.1.8} [Emasher Resource] (EmasherResource-1.2.1.8.zip) Unloaded
	EnderIO{0.5.5} [Ender IO] (EnderIO-1.6.4-0.5.5.136.jar) Unloaded
	endernet{0.1.2} [EnderNet] (EnderNet-beta3.jar) Unloaded
	EnderStorage{1.4.3.5} [EnderStorage] (EnderStorage 1.4.3.5.jar) Unloaded
	eng_toolbox{1.1.6.6} [Engineer's Toolbox] (EngineersToolbox-1.1.6.6.zip) Unloaded
	EnhancedPortals3{3.0.0_Beta-2d} [EnhancedPortals] (EnhancedPortals_3.0.0_Beta-2d.jar) Unloaded
	ExpandedRedstone{Gamma} [ExpandedRedstone] (ExpandedRedstone 1.6 v10b.zip) Unloaded
	ExtraUtilities{1.0.1} [Extra Utilities] (extrautils-1.0.2.zip) Unloaded
	factorization.misc{0.8.23} [Factorization Miscellaneous Nonsense] (Factorization-0.8.23.jar) Unloaded
	factorization.notify{0.8.23} [Factorization Notification System] (Factorization-0.8.23.jar) Unloaded
	factorization{0.8.23} [Factorization] (Factorization-0.8.23.jar) Unloaded
	factorization.dimensionalSlice{0.8.23} [Factorization Dimensional Slices] (Factorization-0.8.23.jar) Unloaded
	flatsigns{1.4.0} [Flat Signs] (flatsigns-1.6.2-universal-1.4.0.15.jar) Unloaded
	Forestry{2.3.1.0} [Forestry for Minecraft] (forestry-A-2.3.1.0.jar) Unloaded
	gascraft{2.0.3.2} [GasCraft] (GasCraft-2.0.3.2.zip) Unloaded
	GateCopy{3.1.4} [GateCopy] (GateCopy-1.6.4-3.1.4.jar) Unloaded
	gendustry{0.9.4.21} [GenDustry] (gendustry-mc164-0.9.4.21.jar) Unloaded
	GeoStrata{Gamma} [GeoStrata] (GeoStrata 1.6 v10b.zip) Unloaded
	HopperDuctMod{1.2.2} [Hopper Ducts] (HopperDuctsMod1.2.2.zip) Unloaded
	IC2NuclearControl{1.6.2c} [Nuclear Control] (IC2NuclearControl-1.6.2c-ic2-experimental.zip) Unloaded
	iChunUtil{2.4.0} [iChunUtil] (iChunUtil2.4.0.zip) Unloaded
	IC2{2.0.316-experimental} [IndustrialCraft 2] (industrialcraft-2_2.0.316-experimental.jar) Unloaded
	inventorytweaks{1.56} [Inventory Tweaks] (InventoryTweaks-MC1.6.2-1.56-b77.jar) Unloaded
	IronChest{5.4.1.649} [Iron Chest] (ironchest-universal-1.6.4-5.4.1.649.zip) Unloaded
	JABBA{1.0.3} [JABBA] (JABBA_1.0.3.zip) Unloaded
	LogisticsPipes|Main{0.7.4.dev.80} [Logistics Pipes] (LogisticsPipes-MC1.6.4-0.7.4.dev.80.jar) Unloaded
	magicalcrops{3.1.4} [Magical Crops] (magical_crops_1.6.4_3.1.4.zip) Unloaded
	MagicBees{2.1.9} [Magic Bees] (magicbees-2.1.9.jar) Unloaded
	Mariculture{1.1.4c} [Mariculture] (mariculture-1.6.X-v1.1.4c.zip) Unloaded
	Roguelike{1.2.7} [Roguelike Dungeons Mod] (mc-roguelike-1.6.4-forge-v1.2.7.zip) Unloaded
	MFFS{3.5.0} [Modular Force Field System] (MFFS_v3.5.0.255.jar) Unloaded
	Mimicry{1.2.1} [Mimicry] (Mimic_1.2.1_forge 953_mc 1.6.4.zip) Unloaded
	MFR Compat Forestry Trees{1.0} [MFR Compat Forestry Trees] (MineFactoryReloaded-2.7.4B1-228.jar) Unloaded
	MFR Compat Extra Trees{1.0} [MFR Compat Extra Trees] (MineFactoryReloaded-2.7.4B1-228.jar) Unloaded
	MineFactoryReloaded{1.6.2R2.7.4B1} [MineFactory Reloaded] (MineFactoryReloaded-2.7.4B1-228.jar) Unloaded
	MineFactoryReloaded|CompatAppliedEnergistics{1.6.2R2.7.4B1} [MFR Compat: Applied Energistics] (MineFactoryReloaded-2.7.4B1-228.jar) Unloaded
	MineFactoryReloaded|CompatAtum{1.6.2R2.7.4B1} [MFR Compat: Atum] (MineFactoryReloaded-2.7.4B1-228.jar) Unloaded
	MineFactoryReloaded|CompatBackTools{1.6.2R2.7.4B1} [MFR Compat: BackTools] (MineFactoryReloaded-2.7.4B1-228.jar) Unloaded
	MineFactoryReloaded|CompatBuildCraft{1.6.2R2.7.4B1} [MFR Compat: BuildCraft] (MineFactoryReloaded-2.7.4B1-228.jar) Unloaded
	MineFactoryReloaded|CompatChococraft{1.6.2R2.7.4B1} [MFR Compat: Chococraft] (MineFactoryReloaded-2.7.4B1-228.jar) Unloaded
	MineFactoryReloaded|CompatExtraBiomes{1.6.2R2.7.4B1} [MFR Compat: ExtraBiomes] (MineFactoryReloaded-2.7.4B1-228.jar) Unloaded
	MineFactoryReloaded|CompatForestry{1.6.2R2.7.4B1} [MFR Compat: Forestry] (MineFactoryReloaded-2.7.4B1-228.jar) Unloaded
	MineFactoryReloaded|CompatForestryPre{1.6.2R2.7.4B1} [MFR Compat: Forestry (part 2)] (MineFactoryReloaded-2.7.4B1-228.jar) Unloaded
	MineFactoryReloaded|CompatForgeMicroblock{1.6.2R2.7.4B1} [MFR Compat: ForgeMicroblock] (MineFactoryReloaded-2.7.4B1-228.jar) Unloaded
	MineFactoryReloaded|CompatIC2{1.6.2R2.7.4B1} [MFR Compat: IC2] (MineFactoryReloaded-2.7.4B1-228.jar) Unloaded
	MineFactoryReloaded|CompatMagicalCrops{1.6.2R2.7.4B1} [MFR Compat: Magical Crops] (MineFactoryReloaded-2.7.4B1-228.jar) Unloaded
	MineFactoryReloaded|CompatMystcraft{1.6.2R2.7.4B1} [MFR Compat: Mystcraft] (MineFactoryReloaded-2.7.4B1-228.jar) Unloaded
	MineFactoryReloaded|CompatPams{1.6.2R2.7.4B1} [MFR Compat: Pam's Mods] (MineFactoryReloaded-2.7.4B1-228.jar) Unloaded
	MineFactoryReloaded|CompatRailcraft{1.6.2R2.7.4B1} [MFR Compat: Railcraft] (MineFactoryReloaded-2.7.4B1-228.jar) Unloaded
	MineFactoryReloaded|CompatRP2{1.6.2R2.7.4B1} [MFR Compat: RP2] (MineFactoryReloaded-2.7.4B1-228.jar) Unloaded
	MineFactoryReloaded|CompatSufficientBiomes{1.6.2R2.7.4B1} [MFR Compat: Sufficient Biomes] (MineFactoryReloaded-2.7.4B1-228.jar) Unloaded
	MineFactoryReloaded|CompatThaumcraft{1.6.2R2.7.4B1} [MFR Compat: Thaumcraft] (MineFactoryReloaded-2.7.4B1-228.jar) Unloaded
	MineFactoryReloaded|CompatThermalExpansion{1.6.2R2.7.4B1} [MFR Compat: Thermal Expansion] (MineFactoryReloaded-2.7.4B1-228.jar) Unloaded
	MineFactoryReloaded|CompatTwilightForest{1.6.2R2.7.4B1} [MFR Compat: TwilightForest] (MineFactoryReloaded-2.7.4B1-228.jar) Unloaded
	MineFactoryReloaded|CompatVanilla{1.6.2R2.7.4B1} [MFR Compat: Vanilla] (MineFactoryReloaded-2.7.4B1-228.jar) Unloaded
	MineFactoryReloaded|CompatXyCraft{1.6.2R2.7.4B1} [MFR Compat: XyCraft] (MineFactoryReloaded-2.7.4B1-228.jar) Unloaded
	powersuits{0.9.0-79} [MachineMuse's Modular Powersuits] (ModularPowersuits-1.6.2-0.9.0-79.jar) Unloaded
	Morpheus{1.2} [Morpheus] (Morpheus-1.6.4-1.2.32.jar) Unloaded
	Mystcraft{0.10.11.00} [Mystcraft] (mystcraft-uni-1.6.4-0.10.11.00.zip) Unloaded
	Natura{2.1.12} [Natura] (Natura_1.6.4_2.1.13.jar) Unloaded
	NEIAddons{1.9.3.r47} [NEI Addons] (neiaddons-1.6.2-1.9.3.r47.jar) Unloaded
	NEIAddons|AE{1.9.3.r47} [NEI Addons: Applied Energistics] (neiaddons-1.6.2-1.9.3.r47.jar) Unloaded
	NEIAddons|CraftingTables{1.9.3.r47} [NEI Addons: Crafting Tables] (neiaddons-1.6.2-1.9.3.r47.jar) Unloaded
	NEIAddons|ExtraBees{1.9.3.r47} [NEI Addons: Extra Bees] (neiaddons-1.6.2-1.9.3.r47.jar) Unloaded
	NEIAddons|Forestry{1.9.3.r47} [NEI Addons: Forestry] (neiaddons-1.6.2-1.9.3.r47.jar) Unloaded
	NEIAddons|MiscPeripherals{1.9.3.r47} [NEI Addons: Misc Peripherals] (neiaddons-1.6.2-1.9.3.r47.jar) Unloaded
	NEIPlugins{1.1.0.6} [NEI Plugins] (NEIPlugins-1.1.0.6.jar) Unloaded
	NetherOres{1.6.2R2.2.2B1} [Nether Ores] (NetherOres-2.2.2B1-16.jar) Unloaded
	notenoughkeys{0.0.4} [Not Enough Keys] (NotEnoughKeys-1.6.4-0.0.4.jar) Unloaded
	numina{0.1.0-47} [Numina] (Numina-1.6.2-0.1.0-47.jar) Unloaded
	ObsidiPlates{2.0.0} [Obsidian Pressure Plates] (obsidiplates-1.6.2-universal-2.0.0.15.jar) Unloaded
	OpenBlocks{1.2.2} [OpenBlocks] (OpenBlocks-Stable-1.2.2-snapshot-502.jar) Unloaded
	OpenPeripheral{0.2.1} [OpenPeripheral] (OpenPeripheral-0.2.1-snapshot-109-forge9.11.1.953.jar) Unloaded
	MapWriter{2.0.1} [MapWriter] (Opis_1.1.2_alpha.zip) Unloaded
	Opis{1.1.2_alpha} [Opis] (Opis_1.1.2_alpha.zip) Unloaded
	PortalGun{2.0.1} [PortalGun] (PortalGun2.0.1.zip) Unloaded
	QuarryPlus{1.5.5.3} [QuarryPlus] (QuarryPlus-1.6.4-1.5.5.3.zip) Unloaded
	Railcraft{8.3.1.0} [Railcraft] (Railcraft_1.6.4-8.3.1.0.jar) Unloaded
	RandomThings{1.8.6} [Random Things] (Random Things v. 1.8.6 [MC 1.6.2].jar) Unloaded
	ReactorCraft{beta} [ReactorCraft] (ReactorCraft 1.6 v10.zip) Unloaded
	Redstone Arsenal{1.0.0.b2b} [Redstone Arsenal] (RedstoneArsenal-1.0.0.b2b.jar) Unloaded
	xreliquary{1.6.4-1.1.1} [Reliquary] (Reliquary-1.6.4-1.1.1.jar) Unloaded
	remoteIO{@MAJOR@.@MINOR@.@REVIS@.${env.BUILD_NUMBER}} [Remote IO] (RemoteIO-1.7.1.jar) Unloaded
	Revamp{1.2.2} [Rivvest's Enhancements to Villager and Mob Performance] (revamp-1.2.2.zip) Unloaded
	RotaryCraft{Gamma} [RotaryCraft] (RotaryCraft 1.6 v10h.zip) Unloaded
	StevesCarts{2.0.0.b1} [Steve's Carts 2] (StevesCarts2.0.0.b3.zip) Unloaded
	switches{1.3.0} [Switches] (switches-1.6.4-universal-coremod-1.3.0.25.jar) Unloaded
	Sync{2.0.0} [Sync] (Sync2.0.0.zip) Unloaded
	TConstruct{1.6.X_1.5.2.1} [Tinkers' Construct] (TConstruct_mc1.6.4_1.5.2.2.jar) Unloaded
	Thaumcraft{4.0.5b} [Thaumcraft] (Thaumcraft4.0.5b.zip) Unloaded
	ThaumcraftMobAspects{1.6.X-1d} [Thaumcraft Mob Aspects] (thaumcraftmobaspects-1.6.X-1e-build2.zip) Unloaded
	ThaumicTinkerer{2.0} [Thaumic Tinkerer] (ThaumicTinkerer 2.0-44.jar) Unloaded
	ThermalExpansion{3.0.0.b11b} [Thermal Expansion] (ThermalExpansion-3.0.0.b11b.jar) Unloaded
	TMechworks{DEV.21b1027} [Tinkers' Mechworks] (TMechworks_1.6.4_0.1.2.jar) Unloaded
	TorchLevers{1.3.2} [Torch Levers] (TorchLeversV1.3.2.jar) Unloaded
	TwilightForest{1.20.2} [The Twilight Forest] (twilightforest-1.20.2.jar) Unloaded
	Waila{1.4.4} [Waila] (Waila_1.4.4b.zip) Unloaded
	WR-CBE|Addons{1.4.0.6} [WR-CBE Addons] (WR-CBE 1.4.0.6.jar) Unloaded
	WR-CBE|Core{1.4.0.6} [WR-CBE Core] (WR-CBE 1.4.0.6.jar) Unloaded
	WR-CBE|Logic{1.4.0.6} [WR-CBE Logic] (WR-CBE 1.4.0.6.jar) Unloaded
	xact{0.4.2c} [XACT Mod] (XACT v0.4.2c.jar) Unloaded
	ForgeMicroblock{1.0.0.227} [Forge Microblocks] (ForgeMultipart-universal-1.6.4-1.0.0.227.jar) Unloaded
	ForgeMultipart{1.0.0.227} [Forge Multipart] (ForgeMultipart-universal-1.6.4-1.0.0.227.jar) Unloaded
	McMultipart{1.0.0.227} [Minecraft Multipart Plugin] (ForgeMultipart-universal-1.6.4-1.0.0.227.jar) Unloaded
	Profiler Position: N/A (disabled)
	Is Modded: Definitely; Server brand changed to 'mcpc,craftbukkit,fml,forge'
	Type: Dedicated Server (map_server.txt)
