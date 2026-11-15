# Clasificación de mods por lado

Total: 422 mods — ambos: 309, solo cliente: 64, solo servidor: 49

Leyenda: **both** = cliente y servidor, **client** = solo en la PC de cada jugador, **server** = solo en el servidor.

Fuentes: `mods.toml` del jar (side de dependencias, displayTest, clientSideOnly), API de Modrinth (client_side/server_side), conocimiento de cada mod. En la duda: both.

| Lado | Mod | Archivo | Propio | Motivo |
|---|---|---|---|---|
| server | AI-Improvements | `AI-Improvements-1.20-0.5.2.jar` |  | IA de mobs, servidor (Modrinth server-only) |
| server | Almanac | `almanac-forge-1.20.1-1.26.11.1.jar` |  | Librería solo de servidor (IGNORE_ALL_VERSION, Modrinth server-only) |
| server | Better village | `bettervillage-forge-1.20.1-3.3.1-all.jar` |  | Mejoras de aldeas, lógica de servidor (Modrinth server-only) |
| server | Cerulean | `cerulean-forge-1.0.0-1.20.1.jar` |  | Logros por datapack (Modrinth server-only) |
| server | Chunky | `Chunky-1.3.146.jar` |  | Pregeneración del mundo (comandos de admin), solo servidor |
| server | CrashExploitFixer | `crashexploitfixer-forge-2.0.0+1.20.4-all-srg.jar` |  | Anti-exploits de servidor (Modrinth server-only) |
| server | Despawn Tweaks | `despawntweaks-forge-1.0.0-1.20.1.jar` |  | Reglas de despawn (Modrinth server-only) |
| server | Double Doors | `doubledoors-1.20.1-7.5.jar` |  | Puertas dobles, lógica de servidor (Modrinth server-only) |
| server | FancyHolograms | `fancyholograms-forge-1.20.1-2.9.0.jar` | sí | Mod propio: hologramas; deps side=SERVER, IGNORE_ALL_VERSION, sin clases de cliente |
| server | Fast Noise Mod | `zfastnoise-1.0.13+1.20+forge.jar` |  | Optimización de generación de ruido (Modrinth server-only) |
| server | Improved Village Placement | `improved-village-placement-1.1.1.jar` |  | Colocación de aldeas (Modrinth server-only) |
| server | Integrated Patches | `integrated_patches v1.2.0-1.20.1.jar` |  | Parches de estructuras (Modrinth server-only) |
| server | Lithostitched | `lithostitched-forge-1.20.1-1.4.12.jar` |  | Librería de generación de mundo (Modrinth server-only) |
| server | Load My F***ing Tags | `lmft-1.0.4+1.20.1-forge.jar` |  | Load My F***ing Tags: arreglo de servidor (Modrinth server-only) |
| server | Moog's Structure Lib | `MoogsStructureLib-forge-1.20-3.4.2.jar` |  | Librería de estructuras de Moog (Modrinth server-only) |
| server | MoogsEndStructures | `MoogsEndStructures-universal-1.20-2.1.0.jar` |  | Moog's End Structures: estructuras (Modrinth server-only) |
| server | MoogsMissingVillages | `MoogsMissingVillages-universal-1.20-2.2.0.jar` |  | Moog's Missing Villages: estructuras (Modrinth server-only) |
| server | MoogsNetherStructures | `MoogsNetherStructures-universal-1.20-3.1.0.jar` |  | Moog's Nether Structures (Modrinth server-only) |
| server | MoogsOceanStructures | `MoogsOceanStructures-universal-1.20-1.1.0.jar` |  | Moog's Ocean Structures (Modrinth server-only) |
| server | MoogsSoaringStructures | `MoogsSoaringStructures-universal-1.20-2.2.0.jar` |  | Moog's Soaring Structures (Modrinth server-only) |
| server | MoogsVoyagerStructures | `MoogsVoyagerStructures-universal-1.20-5.1.3.jar` |  | Moog's Voyager Structures (Modrinth server-only) |
| server | Multiverse (Core + Portals + Inventories + SignPortals) | `multiverse-forge-1.20.1-5.8.2.jar` | sí | Mod propio: multimundo; deps side=SERVER, IGNORE_ALL_VERSION, sin clases de cliente |
| server | Neruina | `neruina-3.3.5+1.20.1-forge.jar` |  | Evita crasheos por entidades que fallan al hacer tick, solo servidor |
| server | NetherPortalFix | `netherportalfix-forge-1.20-13.0.1.jar` |  | Arreglo de portales (Modrinth server-only) |
| server | Pollaland Rangos | `pollarangos-1.20.1.jar` | sí | Mod propio: rangos; IGNORE_SERVER_VERSION, sin clases de cliente ni registros |
| server | Pollaland Tiempo | `pollatiempo-1.20.1.jar` | sí | Mod propio: límite de 4 h; IGNORE_SERVER_VERSION, sin clases de cliente ni registros |
| server | Radium | `radium-mc1.20.1-0.12.4+git.26c9d8e.jar` |  | Optimización de lógica de servidor (Modrinth server-only) |
| server | Repurposed Structures | `repurposed_structures-7.1.25+1.20.1-forge.jar` |  | Estructuras (Modrinth server-only) |
| server | ServerCore | `servercore-forge-1.5.2+1.20.1.jar` |  | Optimización de servidor; config conservadora (distancias dinámicas, mínimo 6) |
| server | Simple Backups | `SimpleBackups-1.20.1-3.1.24.jar` |  | Copias de seguridad automáticas del mundo (cada 4 h, guarda 6) |
| server | Simple Shops Fix | `simpleshopsfix-1.1.1.jar` |  | Arreglo de Simple Shops (Modrinth server-only) |
| server | SimpleJail (Forge) | `simplejail-forge-1.20.1.jar` | sí | Mod propio: cárcel; IGNORE_SERVER_VERSION, sin clases de cliente ni registros |
| server | TAB | `TAB v5.5.0 1.20 - 1.20.1.jar` |  | Plugin/mod de servidor (tabla de jugadores). Estaba por error en el cliente y lo crasheaba -> solo servidor |
| server | Underground Rivers | `underground-rivers-1.0.1-forge-1.20.1.jar` |  | Generación de ríos (Modrinth server-only) |
| server | Village Spawn Point | `villagespawnpoint-1.20.1-6.1.jar` |  | Spawn en aldea (Modrinth server-only) |
| server | Villages&Pillages | `villagesandpillages-forge-2.0.0+mc1.20.1.jar` |  | Estructuras de aldeas (Modrinth server-only) |
| server | When Dungeons Arise | `DungeonsArise-1.20.x-2.1.58-release.jar` |  | Estructuras; mods.toml depende de minecraft/forge solo en SERVER |
| server | When Dungeons Arise: Seven Seas | `DungeonsAriseSevenSeas-1.19.2-1.0.2-forge.jar` |  | Estructuras; deps side=SERVER |
| server | WorldGuard (Forge) | `worldguard-forge-1.20.1.jar` | sí | Mod propio: protección de zonas; IGNORE_SERVER_VERSION, sin clases de cliente ni registros |
| server | YUNG's Better Caves | `YungsBetterCaves-1.20.1-Forge-2.0.7.jar` |  | YUNG's: generación de mundo (Modrinth server-only) |
| server | YUNG's Better Desert Temples | `YungsBetterDesertTemples-1.20-Forge-3.0.3.jar` |  | YUNG's: estructura (Modrinth server-only) |
| server | YUNG's Better Dungeons | `YungsBetterDungeons-1.20-Forge-4.0.4.jar` |  | YUNG's: estructura (Modrinth server-only) |
| server | YUNG's Better End Island | `YungsBetterEndIsland-1.20-Forge-2.0.6.jar` |  | YUNG's: estructura (Modrinth server-only) |
| server | YUNG's Better Jungle Temples | `YungsBetterJungleTemples-1.20-Forge-2.0.5.jar` |  | YUNG's: estructura (Modrinth server-only) |
| server | YUNG's Better Mineshafts | `YungsBetterMineshafts-1.20-Forge-4.0.4.jar` |  | YUNG's: estructura (Modrinth server-only) |
| server | YUNG's Better Ocean Monuments | `YungsBetterOceanMonuments-1.20-Forge-3.0.4.jar` |  | YUNG's: estructura (Modrinth server-only) |
| server | YUNG's Better Strongholds | `YungsBetterStrongholds-1.20-Forge-4.0.3.jar` |  | YUNG's: estructura (Modrinth server-only) |
| server | YUNG's Better Witch Huts | `YungsBetterWitchHuts-1.20-Forge-3.0.3.jar` |  | YUNG's: estructura (Modrinth server-only) |
| server | YUNG's Bridges | `YungsBridges-1.20-Forge-4.0.3.jar` |  | YUNG's: estructura (Modrinth server-only) |
| client | 3d-Skin-Layers | `skinlayers3d-forge-1.11.4-mc1.20.1.jar` |  | clientSideOnly=true |
| client | Advancement Plaques | `AdvancementPlaques-1.20.1-forge-1.6.9.jar` |  | Solo UI de logros (Modrinth: cliente requerido, servidor no soportado) |
| client | Athena | `athena-forge-1.20.1-3.1.2.jar` |  | Librería de texturas conectadas (CTM), solo render (Modrinth client-only) |
| client | BadOptimizations | `BadOptimizations-2.4.1-1.20.1.jar` |  | Optimización de render; mods.toml depende de minecraft solo en CLIENT |
| client | Better Advancements | `BetterAdvancements-Forge-1.20.1-0.6.0.73.jar` |  | Pantalla de logros; dependencias side=CLIENT |
| client | Better Biome Reblend | `betterbiomereblend-1.5.3.jar` |  | Mezcla de colores de bioma (render); dependencias side=CLIENT |
| client | BetterF3 | `BetterF3-7.0.2-Forge-1.20.1.jar` |  | Pantalla F3; dependencias side=CLIENT |
| client | betterfpsdist mod | `betterfpsdist-1.20.1-6.0.jar` |  | Distancia de render para FPS, solo cliente |
| client | Chat Heads | `chat_heads-0.15.7-forge-1.20.jar` |  | Cabezas en el chat; displayTest IGNORE_ALL_VERSION + deps CLIENT |
| client | ChatAnimation | `chatanimation-forge-1.3.5+mc1.20.1.jar` |  | Animación del chat; deps CLIENT |
| client | Continuity | `continuity-3.0.0+1.20.1.forge.jar` |  | Texturas conectadas; IGNORE_ALL_VERSION, Modrinth client-only |
| client | Controlling | `Controlling-forge-1.20.1-12.0.2.jar` |  | Buscador de controles; deps CLIENT |
| client | Crash Assistant | `CrashAssistant-forge-1.19-1.20.1-1.11.12.jar` |  | Ayudante de crasheos del lanzador (Modrinth client-only) |
| client | Cubes Without Borders | `cwb-5.0.0+1.20.0.forge.jar` |  | Cubes Without Borders: modo ventana sin bordes |
| client | Cull Less Leaves Reforged | `CullLessLeaves-Reforged-1.20.1-1.0.5.jar` |  | Render de hojas (Modrinth client-only) |
| client | Do a Barrel Roll | `do_a_barrel_roll-forge-3.5.6+1.20.1.jar` |  | Control de élitro; servidor opcional |
| client | Don't Punch My TACZ | `dont-punch-my-tacz-v0.5.2-1.20.1-forge.jar` |  | clientSideOnly=true en mods.toml |
| client | Drippy Loading Screen | `drippyloadingscreen_forge_3.1.5_MC_1.20.1.jar` |  | Pantalla de carga; deps CLIENT |
| client | Dynamic FPS | `dynamic-fps-3.11.4+minecraft-1.20.0-forge.jar` |  | Reduce FPS en segundo plano; IGNORE_ALL_VERSION + deps CLIENT |
| client | Eating Animation | `eatinganimation-1.20.1-5.1.0.jar` |  | Animación de comer; IGNORE_ALL_VERSION |
| client | Embeddium | `embeddium-0.3.31+mc1.20.1.jar` |  | Motor de render (Sodium); Modrinth client-only |
| client | Embeddium Extra | `rubidium-extra-0.5.4.4+mc1.20.1-build.131.jar` |  | Opciones extra de Embeddium |
| client | EnchantmentDescriptions | `EnchantmentDescriptions-Forge-1.20.1-17.1.21.jar` |  | Descripción de encantamientos en tooltip; deps CLIENT |
| client | Entity Model Features | `entity_model_features-3.3.12-1.20.1-forge.jar` |  | EMF: modelos de entidades; deps CLIENT |
| client | Entity Texture Features | `entity_texture_features-7.2.7-1.20.1-forge.jar` |  | ETF: texturas de entidades; deps CLIENT |
| client | EntityCulling | `entityculling-forge-1.12.1-mc1.20.1.jar` |  | clientSideOnly=true |
| client | Euphoria Patcher | `EuphoriaPatcher-1.10.5-r5.9.3-forge.jar` |  | Parcha el shader Complementary; deps CLIENT |
| client | Fallingleaves | `fallingleaves-1.20.1-2.1.2.jar` |  | Partículas de hojas; deps CLIENT |
| client | FancyMenu | `fancymenu_forge_3.10.0_MC_1.20.1.jar` |  | Menú de título personalizado (solo interfaz) |
| client | Flerovium | `flerovium-forge-1.20.1-1.2.19-all.jar` |  | Optimización de render; deps CLIENT |
| client | Freecam | `freecam-forge-1.2.1+1.20.jar` |  | Cámara libre (Modrinth client-only) |
| client | Fusion | `fusion-1.3.16-forge-mc1.20.1.jar` |  | Texturas conectadas Fusion (Modrinth client-only) |
| client | GeckoBetterFPS | `gbf-1.0.2.jar` |  | GeckoLib Better FPS: optimización de render |
| client | GPUTape | `GPUTape-1.18x-1.21x-1.0.5.1.jar` |  | Optimización de GPU (Modrinth client-only) |
| client | ImmediatelyFast | `ImmediatelyFast-Forge-1.5.5+1.20.4.jar` |  | Optimización de render; IGNORE_ALL_VERSION + deps CLIENT |
| client | Ixeris | `Ixeris-4.6.11+1.20.1-forge.jar` |  | clientSideOnly=true |
| client | Jump Over Fences | `jumpoverfences-forge-1.20.1-1.3.1.jar` |  | Modrinth: cliente requerido, servidor no soportado |
| client | Legendary Tooltips | `LegendaryTooltips-1.20.1-forge-1.4.5.jar` |  | Tooltips (Modrinth client-only) |
| client | Melody | `melody_forge_1.0.3_MC_1.20.1-1.20.4.jar` |  | Librería de audio de FancyMenu/Drippy, solo cliente |
| client | Mod Name Tooltip | `modnametooltip-1.20.1-1.20.0.jar` |  | Nombre del mod en tooltip; deps minecraft CLIENT |
| client | Model Gap Fix | `modelfix-1.15.jar` |  | Arreglo de modelos; IGNORE_ALL_VERSION + deps CLIENT |
| client | Mouse Tweaks | `MouseTweaks-forge-mc1.20.1-2.25.1.jar` |  | Atajos de ratón en inventario (Modrinth client-only) |
| client | NotEnoughAnimations | `notenoughanimations-forge-1.12.7-mc1.20.1.jar` |  | clientSideOnly=true |
| client | Oculus | `oculus-mc1.20.1-1.8.0.jar` |  | Shaders (Iris para Forge) |
| client | Particle Core | `particle_core-0.3.3+1.20.1+forge.jar` |  | Optimización de partículas; deps CLIENT |
| client | Presence Footsteps [FORGE] | `Presence Footsteps [FORGE] 1.0.0.jar` |  | Sonidos de pasos (Modrinth client-only) |
| client | Prism | `Prism-1.20.1-forge-1.0.5.jar` |  | Librería de tooltips para Legendary Tooltips (Modrinth client-only) |
| client | Punchy | `punchy-3.2b-forge-1.20.1.jar` |  | Animaciones en primera persona; deps CLIENT |
| client | Reflex AntiLag | `reflex-forge-1.0.4+mc1.20.1.jar` |  | Reflex anti-lag de entrada (Modrinth client-only) |
| client | Searchables | `Searchables-forge-1.20.1-1.0.3.jar` |  | Librería de búsqueda para Controlling (Modrinth client-only) |
| client | Simply Tooltips | `SimplyTooltips-forge-0.1.5-1.20.1.jar` |  | Tooltips (Modrinth client-only) |
| client | Smart Particles | `smart_particles-20.1.10-Forge.jar` |  | Partículas (Modrinth client-only) |
| client | Sodium Dynamic Lights | `sodiumdynamiclights-forge-1.0.10-1.20.1.jar` |  | Luz dinámica de antorcha en mano (Modrinth client-only) |
| client | Sodium Extras | `sodiumextras-forge-1.0.7-1.20.1.jar` |  | Extras de Sodium (Modrinth client-only) |
| client | Sodium Options API | `sodiumoptionsapi-forge-1.0.10-1.20.1.jar` |  | API de opciones de Sodium (Modrinth client-only) |
| client | Sound Physics Remastered | `sound-physics-remastered-forge-1.20.1-1.5.1.jar` |  | Física de sonido; IGNORE_ALL_VERSION, servidor opcional |
| client | Subtle Effects | `SubtleEffects-forge-1.20.1-1.15.1-hotfix.1.jar` |  | Efectos visuales; IGNORE_ALL_VERSION, servidor opcional |
| client | Tips | `Tips-Forge-1.20.1-12.1.9.jar` |  | Consejos en pantalla de carga; IGNORE_ALL_VERSION + deps CLIENT |
| client | WaterMedia | `watermedia-3.0.1-fix-youtube.jar` | sí | Reproductor de video; WaterFrames/LittleFrames lo piden solo en CLIENT |
| client | WaterMedia: Binaries | `watermedia_binaries-3.0.1.jar` |  | Binarios VLC de WaterMedia (152 MB); WaterMedia lo pide solo en CLIENT |
| client | Weather Glass | `weatherglass-0.6.2-1.20.1-forge.jar` |  | Efectos de lluvia en pantalla; IGNORE_ALL_VERSION + deps CLIENT |
| client | WI Zoom | `WI-Zoom-1.5-MC1.20.1-Forge.jar` |  | Zoom; IGNORE_ALL_VERSION |
| client | Xaero's Minimap | `xaerominimap-forge-1.20.1-26.6.0.jar` |  | Minimapa de Xaero (servidor opcional) |
| client | Xaero's World Map | `xaeroworldmap-forge-1.20.1-1.47.0.jar` |  | Mapa del mundo de Xaero (servidor opcional) |
| both | [Let's Do] Bakery | `letsdo-bakery-forge-2.0.6.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | [Let's Do] Beachparty | `letsdo-beachparty-forge-2.0.3.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | [Let's Do] Brewery | `letsdo-brewery-forge-2.0.6.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | [Let's Do] Candlelight | `letsdo-candlelight-forge-2.0.5.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | [Let's Do] Farm & Charm | `letsdo-farm_and_charm-forge-1.0.14.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | [Let's Do] Furniture | `letsdo-furniture-forge-1.0.4.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | [Let's Do] HerbalBrews | `letsdo-herbalbrews-forge-1.0.12.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | [Let's Do] NetherVinery | `letsdo-nethervinery-forge-1.2.19.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | [Let's Do] Vinery | `letsdo-vinery-forge-1.4.41.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Additional Lanterns | `additionallanterns-1.1.2-forge-mc1.20.2.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Additional Lights | `additional_lights-1.20.1-2.1.7.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | AddonsLib | `addonslib-forge-1.20.1-1.11.jar` |  | Modrinth: cliente required, servidor required |
| both | Adorable Hamster Pets | `adorablehamsterpets-3.7.0-1.20.1+forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Adorn | `Adorn-5.0.1+1.20.1-forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Advanced Netherite | `advancednetherite-forge-2.1.3-1.20.1.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | AlcoCraft+ | `alcocraftplus-1.20-2.2.0-forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | aleki's Nifty Ships | `alekiNiftyShips-FORGE-1.20.1-1.0.14.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Alex's Caves | `alexscaves-2.0.2.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Alex's Delight | `alexsdelight-1.5.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Alex's Mobs | `alexsmobs-1.22.9.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Alex's Mobs - Neapolitan Compat | `Compat_AlexsMobs-Neapolitan.jar` |  | Modrinth: cliente required, servidor required |
| both | All The Leaks | `alltheleaks-1.1.5-1.20.1-forge.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Amendments | `amendments-1.20-2.2.6.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Ancient Villages | `ancientvillages-forge-1.20.1-0.0.4.jar` |  | Modrinth: cliente required, servidor required |
| both | Another Furniture | `another_furniture-forge-1.20.1-3.0.4.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | AppleSkin | `appleskin-forge-mc1.20.1-2.5.1.jar` |  | Servidor opcional (sincroniza saturación) -> ambos |
| both | Aquaculture 2 | `Aquaculture-1.20.1-2.5.7.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Aquaculture Delight | `aquaculturedelight-1.1.0-forge-1.20.1.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Aquamirae | `aquamirae-forge-1.20.1-7.1.14.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Architectury | `architectury-9.2.14-forge.jar` |  | Modrinth: cliente required, servidor required |
| both | Armor of the Ages | `Armor of the Ages-forge-1.20.1-1.3.16.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Artifacts | `artifacts-forge-9.5.19.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | AS Edo Japan | `asedojapan-forge-1.20.1-0.1.3.1.jar` |  | Modrinth: cliente required, servidor required |
| both | AstikorCarts Redux | `astikorcartsredux-1.2.5.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | AttributeFix | `AttributeFix-Forge-1.20.1-21.0.5.jar` |  | Modrinth: cliente required, servidor required |
| both | Automobility | `automobility-0.4.2+1.20.1-forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | AzureLib | `azurelib-neo-1.20.1-3.2.9.jar` |  | Modrinth: cliente required, servidor required |
| both | Bagus Lib | `bagus_lib-1.20.1-5.6.1.jar` |  | Modrinth: cliente required, servidor required |
| both | Balm | `balm-forge-1.20.1-7.3.44.jar` |  | Modrinth: cliente optional, servidor optional |
| both | Better Archeology | `betterarcheology-1.2.1-1.20.1.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | BetterDays | `betterdays-1.20.1-3.3.4.5-FORGE.jar` |  | Modrinth: cliente required, servidor required |
| both | Blocks + | `Blocks+1.20.1-1.7.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Blueprint | `blueprint-1.20.1-7.1.5.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Bookshelf | `Bookshelf-Forge-1.20.1-20.2.15.jar` |  | Modrinth: cliente required, servidor required |
| both | BOZOID | `EpheroLib-1.20.1-FORGE-1.2.0.jar` |  | Sin datos claros -> ambos (más seguro) |
| both | Brewin' And Chewin' | `BrewinAndChewin-1.20.1-3.2.1.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Butchery | `butchery-5.3.1-forge-1.20.1.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Caelus API | `caelus-forge-3.2.0+1.20.1.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Camera Mod | `camera-forge-1.20.1-1.0.20.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Candy World | `candymod-1.20.1-1.1.5.jar` | sí | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Cannibalism | `cannibalism-1.20.1-5.6.10.jar` | sí | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Carry On | `carryon-forge-1.20.1-2.1.2.7.jar` |  | Modrinth: cliente required, servidor required |
| both | Casual Swing | `casualswing-1.0.2-fix-1.20.1-Forge.jar` |  | Registra ítems -> ambos |
| both | cataclysm | `L_Enders_Cataclysm-3.31.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Cataclysm x YUNG's Better Nether Fortresses Compat | `cataclysmfortresses-1.20.1-Forge.jar` |  | Sin datos claros -> ambos (más seguro) |
| both | CHA&S - Craftable Horse Armour and Saddle | `CHA-S-1.20-forge.jar` |  | Modrinth: cliente optional, servidor optional |
| both | Charm of Undying | `charmofundying-forge-6.5.0+1.20.1.jar` |  | Modrinth: cliente required, servidor required |
| both | Chefs Delight | `chefs-delight-1.0.5-forge-1.20.1.jar` |  | Modrinth: cliente required, servidor required |
| both | Chimes | `Chimes-v2.1.1-1.20.1-Forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Chipped | `chipped-forge-1.20.1-3.0.7.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Chococraft 4 | `chococraft-1.20.1-forge-0.9.12.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | chunksending mod | `chunksending-1.20.1-4.1.jar` |  | Limitador de envío de chunks; inofensivo en ambos (dudoso -> ambos) |
| both | Citadel | `citadel-2.6.3-1.20.1.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Cloth Config v10 API | `cloth-config-11.1.136-forge.jar` |  | Modrinth: cliente optional, servidor optional |
| both | Clumps | `Clumps-forge-1.20.1-12.0.0.4.jar` |  | Modrinth: cliente optional, servidor optional |
| both | Collective | `collective-1.20.1-8.86.jar` |  | Modrinth: cliente optional, servidor optional |
| both | Comforts | `comforts-forge-6.4.0+1.20.1.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Compat Delight | `compatdelight-1.0.1.1.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Configured | `configured-forge-1.20.1-2.2.3.jar` |  | Sin datos claros -> ambos (más seguro) |
| both | connector | `Connector-1.0.0-beta.49+1.20.1.jar` |  | Sinytra Connector (carga mods Fabric) -> ambos |
| both | CookingForBlockheads | `cookingforblockheads-forge-1.20.1-16.0.15.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Corail Tombstone | `tombstone-1.20.1-9.1.5.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | CorgiLib | `Corgilib-Forge-1.20.1-4.0.3.6.jar` |  | Modrinth: cliente required, servidor required |
| both | CoroUtil | `coroutil-forge-1.20.1-1.3.7.jar` |  | Modrinth: cliente required, servidor required |
| both | CosmeticArmorReworked | `cosmeticarmorreworked-1.20.1-v1a.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Crabber's Delight | `crabbersdelight-1.20.1-1.2.3.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Create | `create-1.20.1-6.0.8.jar` |  | Añade bloques: requerido en ambos |
| both | Create Deco | `createdeco-2.0.3-1.20.1-forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | CreativeCore | `CreativeCore_FORGE_v2.12.42_mc1.20.1.jar` |  | Librería de LittleFrames/WaterFrames/PlayerRevive -> ambos |
| both | Creeper Overhaul | `creeperoverhaul-3.0.2-forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Cristel Lib | `cristellib-1.1.6-forge.jar` |  | Modrinth: cliente optional, servidor required |
| both | Croptopia | `Croptopia-1.20.1-FORGE-4.0.1.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Croptopia Delight | `croptopiadelight-1.3.2.jar` |  | Modrinth: cliente required, servidor required |
| both | Cupboard utilities | `cupboard-1.20.1-4.2.jar` |  | Sin datos claros -> ambos (más seguro) |
| both | Curios API | `curios-forge-5.14.1+1.20.1.jar` |  | Modrinth: cliente required, servidor required |
| both | Custom NPCs | `CustomNPCs-1.20.1-GBPort-Unofficial-1.20.1.20260711.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | DarkPaintings | `DarkPaintings-Forge-1.20.1-17.0.6.jar` |  | Modrinth: cliente required, servidor required |
| both | Dawn Of Time | `dawnoftimebuilder-forge-1.20.1-1.5.54.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Dawn Of Time: Beyond Vanilla | `dotbv-forge-1.20.1-0.1.1.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Decorative Blocks | `decorative_blocks-forge-1.20.1-4.1.3.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Deeper and Darker | `deeperdarker-forge-1.20.1-1.3.3.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Delight Lib | `delightlib-26.05.18-1.20-forge.jar` |  | Modrinth: cliente required, servidor required |
| both | Deltabox Lib | `deltaboxlib-forge-2.2.0+1.20.1.jar` |  | Modrinth: cliente required, servidor required |
| both | Disenchanting | `Disenchanting-forge-1.20.1-2.2.4.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Domum Ornamentum | `domum_ornamentum-1.20.1-1.0.304-snapshot-universal.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Drug Mod: Reloaded | `drugmod-reloaded-1.20.1.jar` | sí | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Dungeons and Taverns | `dungeons-and-taverns-3.0.3.f.jar` |  | Modrinth: cliente optional, servidor required |
| both | EarthMobsMod | `earthmobsmod-1.20.1-10.5.0.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Easy Anvils | `EasyAnvils-v8.0.2-1.20.1-Forge.jar` |  | Modrinth: cliente required, servidor required |
| both | Easy Magic | `EasyMagic-v8.0.1-1.20.1-Forge.jar` |  | Modrinth: cliente required, servidor required |
| both | Ecologics | `ecologics-forge-1.20.1-2.2.7.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Elevator Mod | `elevatorid-1.20.1-1.9.1-forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Elytra Slot | `elytraslot-forge-6.4.4+1.20.1.jar` |  | Modrinth: cliente required, servidor required |
| both | Elytra Trims | `elytratrims-forge-3.10.0+1.20.1.jar` |  | Modrinth: cliente optional, servidor optional (añade contenido) |
| both | Emojiful | `Emojiful-Forge-1.20.1-4.2.0.jar` |  | Modrinth: requerido en ambos |
| both | End's Delight | `ends_delight-2.6.1+forge.1.20.1.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Enhanced Mob Spawners | `spawnermod-1.20.1-1.9.3+Forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Epic Sustance | `epicsustance-2.0.0.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Epic-Knights: Shields, Armor and Weapons | `epic-knights-1.20.1-forge-10.15.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Etched | `etched-3.0.4.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Fairy Lights | `fairylights-7.0.0-1.20.1.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Farmer's Delight | `FarmersDelight-1.20.1-1.3.4.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Farmer's Delight Compat | `Compat_FarmersDelight.jar` |  | Modrinth: cliente required, servidor required |
| both | Fast Item Frames | `FastItemFrames-v20.1.5-1.20.1-Forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Fast Paintings | `fastpaintings-1.20-1.2.7.jar` |  | Modrinth: cliente required, servidor required |
| both | Fast Suite | `FastSuite-1.20.1-5.1.2.jar` |  | Modrinth: cliente required, servidor required |
| both | Fast Workbench | `FastWorkbench-1.20.1-8.0.4.jar` |  | Modrinth: cliente required, servidor required |
| both | fastasyncworldsave mod | `fastasyncworldsave-1.20.1-2.6.jar` |  | Sin datos claros -> ambos (más seguro) |
| both | FastBoot | `fastboot-1.20.x-1.2.jar` |  | Sin datos claros -> ambos (más seguro) |
| both | Faz Roleplay Plus | `FazRoleplayClothes-1.20.1-2.4.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Feature Recycler | `Feature-Recycler-forge-1.0.1.jar` |  | Sin datos claros -> ambos (más seguro) |
| both | Ferrite Core | `ferritecore-6.0.1-forge.jar` |  | Modrinth: cliente optional, servidor optional |
| both | Flash's NPCs | `flashnpcs-1.20.1-1.2.0.jar` | sí | Añade bloques/ítems/entidades -> requerido en ambos |
| both | ForgeEndertech | `ForgeEndertech-1.20.1-11.1.11.2-build.2374.jar` |  | Librería de AdLods; tiene canal de red y clases de cliente -> ambos para no fallar el handshake |
| both | Forgified Fabric API | `fabric-api-0.92.6+1.11.15+1.20.1.jar` |  | Forgified Fabric API -> ambos |
| both | Fragmentum | `fragmentum-5.4.0+1.20.1-forge.jar` |  | Modrinth: cliente required, servidor required |
| both | FramedBlocks | `FramedBlocks-9.4.3.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Framework | `framework-forge-1.20.1-0.8.0.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Friends&Foes | `friendsandfoes-forge-5.0.4+mc1.20.1.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | From The Fog | `From-The-Fog-1.20-v1.9.2-Forge-Fabric.jar` |  | Modrinth: cliente optional, servidor required (añade contenido) |
| both | FTB Library | `ftb-library-forge-2001.2.13.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Fzzy Config | `fzzy_config-0.7.7+1.20.1+forge.jar` |  | Modrinth: cliente required, servidor required |
| both | Garden Trails | `gardentrails-forge-1.20.1-0.1.14.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | GeckoLib 4 | `geckolib-forge-1.20.1-4.8.4.jar` |  | Librería de animación de entidades -> ambos |
| both | GlitchCore | `GlitchCore-forge-1.20.1-0.0.1.1.jar` |  | Modrinth: cliente required, servidor required |
| both | gml | `gml-4.0.10-all.jar` |  | Modrinth: cliente optional, servidor optional |
| both | Goblin Traders | `goblintraders-forge-1.20.1-1.11.5.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | GottschCore | `gottschcore-1.20.1-2.10.0.jar` |  | Sin datos claros -> ambos (más seguro) |
| both | Gpu memory leak fix | `gpumemleakfix-1.20.1-1.8.jar` |  | Arreglo de memoria GPU; dudoso -> ambos |
| both | Handcrafted | `handcrafted-forge-1.20.1-3.0.6.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Hang Glider | `HangGlider-v8.0.1-1.20.1-Forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Harmful smoke | `harmfulsmoke-1.0.7-alpha-forge-1.20.1.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Horseman | `horseman-1.20.1-1.3.17-forge.jar` |  | Modrinth: cliente required, servidor required |
| both | Ice and Fire | `iceandfire-2.1.13-1.20.1-beta-5.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Iceberg | `Iceberg-1.20.1-forge-1.1.25.jar` |  | Librería de UI pero Modrinth la marca requerida en ambos -> ambos |
| both | Immersive Aircraft | `immersive_aircraft-1.5.0+1.20.1-forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Immersive Armors | `immersive_armors-1.7.2+1.20.1-forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Immersive Furniture | `immersive_furniture-forge-0.4.1+1.20.1.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Immersive Lanterns | `immersivelanterns-forge-1.0.6-1.20.1.jar` |  | Modrinth: cliente required, servidor required |
| both | Immersive Paintings | `immersive_paintings-0.6.13+1.20.1-forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Immersive Thunder | `immersivethunder-forge-1.20.1-1.3.0.jar` |  | Sin datos claros -> ambos |
| both | Immersive Vehicles (formerly MTS) | `Immersive Vehicles-1.20.1-24.0.0.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Immersive Vehicles (MTS/IV) - Official Content Pack | `MTS Official Pack-1.20.1-V29.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Infernal Mobs | `infernalmobs-1.20.1.11.jar` |  | Sin datos claros -> ambos (más seguro) |
| both | Integrated API | `integrated_api-forge-1.20.1-1.9.2.jar` |  | Modrinth: cliente required, servidor required |
| both | Iron Chests | `ironchest-1.20.1-14.4.4.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Iron Furnaces | `ironfurnaces-1.20.1-4.1.8.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Iron's Lib | `irons_lib-1.20.1-2.3.0.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Iron's Spells 'n Spellbooks | `irons_spellbooks-1.20.1-3.16.3.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Jade | `Jade-1.20.1-Forge-11.13.3.jar` |  | Jade muestra más info si está en el servidor |
| both | Jade Addons | `JadeAddons-1.20.1-Forge-5.5.1.jar` |  | Modrinth: cliente optional, servidor optional |
| both | Just Enough Items | `jei-1.20.1-forge-15.74.0.234.jar` |  | JEI funciona mejor con el servidor (transferencia de recetas) |
| both | Just Outdoor Stuffs | `JustOutdoorStuffs-1.20.1-forge-v1.0.2.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Kaleidoscope Tavern | `kaleidoscopetavern-1.2.0-forge+mc1.20.1.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Kaleidoscope World Liquor | `kaleidoscope_world_liquor-1.1.13-forge+mc1.20.1-all.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Kaleth Roleplay | `kaleth_roleplay-1.20.1.jar` | sí | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Kiwi Library | `Kiwi-1.20.1-Forge-11.10.3.jar` |  | Modrinth: cliente optional, servidor optional |
| both | Konkrete | `konkrete_forge_1.8.0_MC_1.20-1.20.1.jar` |  | Librería de FancyMenu/Drippy; servidor opcional -> ambos por seguridad |
| both | kotlinforforge | `kotlinforforge-4.12.0-all.jar` |  | Modrinth: cliente optional, servidor optional |
| both | Krypton Reno | `Krypton Reno-forge-1.20.1-26.1.1-1.20.1.jar` |  | Modrinth: cliente optional, servidor optional |
| both | L_Ender 's Delight | `lendersdelight-1.20.1-1.0.10b.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Large Ore Deposits | `AdLods-1.20.1-8.1.12.0-build.2294.jar` |  | Grandes vetas: Modrinth dice solo servidor, pero depende de ForgeEndertech (que tiene red y código de cliente) -> ambos por seguridad |
| both | Library ferret | `libraryferret-forge-1.20.1-4.0.0.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | LionfishAPI | `lionfishapi-3.0.jar` |  | Modrinth: cliente required, servidor required |
| both | LittleFrames | `LittleFrames_FORGE_v1.4.3-wm3_mc1.20.1.jar` | sí | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Lootr | `lootr-forge-1.20-0.7.35.94.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Macaw's Bridges | `mcw-bridges-3.1.2-mc1.20.1forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Macaw's Doors | `mcw-doors-1.1.5-mc1.20.1forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Macaw's Fences and Walls | `mcw-mcwfences-1.2.1-mc1.20.1forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Macaw's Furniture | `mcw-furniture-3.4.1-mc1.20.1forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Macaw's Holidays | `mcw-holidays-1.1.2-mc1.20.1forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Macaw's Lights and Lamps | `mcw-lights-1.1.5-mc1.20.1forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Macaw's Paintings | `mcw-paintings-1.1.0-mc1.20.1forge.jar` |  | Modrinth: cliente required, servidor required |
| both | Macaw's Paths and Pavings | `mcw-mcwpaths-1.1.1-mc1.20.1forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Macaw's Roofs | `mcw-roofs-2.3.2-mc1.20.1forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Macaw's Stairs and Balconies | `mcw-mcwstairs-1.0.2-mc1.20.1forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Macaw's Trapdoors | `mcw-trapdoors-1.1.5-mc1.20.1forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Macaw's Windows | `mcw-mcwwindows-2.4.2-mc1.20.1forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | MezzConfig | `mezz_config-1.20.1-forge-0.7.1.jar` |  | Librería de configuración (JEI) -> ambos |
| both | MidnightLib | `midnightlib-forge-1.9.2+1.20.1.jar` |  | Modrinth: cliente optional, servidor optional |
| both | Mighty Mail | `mighty_mail-forge-1.20.1-1.1.4.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Minecraft Comes Alive | `minecraft-comes-alive-7.7.1-beta.5-skins-1.20.1.jar` | sí | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Miner's Delight | `miners_delight-1.20.1-1.4.5-backport.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | MineTraps | `MineTraps-1.20.2-(v.2.3.0a).jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | MmmMmmMmmMmm | `dummmmmmy-1.20-2.0.12-forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | MOA DECOR: ART | `MOAdecor ART 1.20.1.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | MOA DECOR: BATH | `MOAdecor BATH 1.20.1.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | MOA DECOR: COOKERY | `MOAdecor COOKERY 1.20.2.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | MOA DECOR: GARDEN | `MOAdecor GARDEN 1.20.1.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | MOA DECOR: HOLIDAYS | `MOAdecor HOLIDAYS 1.20.1.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | MOA DECOR: LIGHTS | `MOAdecor LIGHTS 1.20.1.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | MOA DECOR: SCIENCE | `MOAdecor SCIENCE 1.20.1.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | MOA DECOR: TOYS | `MOAdecor TOYS 1.20.1.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | MOA: ELECTRONICS | `MOAdecor ELECTRONICS 1.20.1.A.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Mobtimizations | `mobtimizations-forge-1.20.1-1.0.0.jar` |  | Modrinth: cliente required, servidor required |
| both | Modern Life | `modernlife-1.20.1-1.75.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | ModernFix | `modernfix-forge-5.27.93+mc1.20.1.jar` |  | Modrinth: cliente optional, servidor optional |
| both | Moonlight Library | `moonlight-1.20-2.16.39-forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | More Bows Restrung | `MoreBows-1.0.13+1.20.x.forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | More Delight | `moredelight-26.05.20-1.20-forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | MoreVanillaArmor | `MoreVanillaArmor-1.20.1-5.1.2.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Mowzie's Cataclysm | `mowzies_cataclysm-1.2.1.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Mowzie's Mobs | `mowziesmobs-1.8.2.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | MrCrayfish's Furniture Mod: Refurbished | `refurbished_furniture-forge-1.20.1-1.0.20.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | My Nether's Delight | `MyNethersDelight-1.20.1-1.10.4-backport.1.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Naturalist | `naturalist-2.0.9-forge-1.20.1.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Nature's Compass | `NaturesCompass-1.20.1-1.12.0-forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Neapolitan | `neapolitan-1.20.1-5.1.0.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Necronomicon | `Necronomicon-Forge-1.6.0+1.20.1.jar` |  | Modrinth: cliente required, servidor required |
| both | Nenu's POP Plushies | `nenus_pop_plushies-2.11.2-forge-1.20.1.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | No Chat Reports | `NoChatReports-FORGE-1.20.1-v2.2.3.jar` |  | Modrinth: cliente optional, servidor optional |
| both | Ocean's Delight | `oceansdelight-1.0.2-1.20.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Otyacraft Engine | `otyacraftengine-forge-mc1.20-3.7.0-alpha.2.jar` |  | Modrinth: cliente required, servidor required |
| both | PacketFixer | `packetfixer-3.3.2-1.18-1.20.4-merged.jar` |  | Modrinth: cliente optional, servidor optional |
| both | Panda's Falling Tree's | `fallingtrees-forge-mc1.20-0.13.2-SNAPSHOT.jar` |  | Modrinth: cliente required, servidor required |
| both | PandaLib | `pandalib-forge-mc1.20-0.5.2-SNAPSHOT.jar` |  | Modrinth: cliente optional, servidor optional |
| both | Patchouli | `Patchouli-1.20.1-85-FORGE.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Paxi | `Paxi-1.20-Forge-4.0.jar` |  | Modrinth: cliente optional, servidor optional |
| both | Penned In | `pennedin-1.20.1-forge-1.3.2.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Placebo | `Placebo-1.20.1-8.6.3.jar` |  | Modrinth: cliente optional, servidor optional |
| both | Platform | `Platform-forge-1.20.1-1.4.2.jar` |  | Modrinth: cliente optional, servidor optional |
| both | Player Animator | `player-animation-lib-forge-1.0.2-rc1+1.20.jar` |  | Modrinth: cliente required, servidor required |
| both | PlayerRevive | `PlayerRevive_FORGE_v2.0.31_mc1.20.1.jar` |  | Modrinth: cliente required, servidor required |
| both | Plushie Buddies | `plushie_buddies-1.0.2-1.20.1.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Pollacoins | `pollacoins-2.0.0.jar` | sí | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Pollaland Calendario | `pollacalendario-1.20.1.jar` | sí | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Pollaland Ciudad | `pollaciudad-1.20.1.jar` | sí | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Polymorph | `polymorph-forge-0.49.11+1.20.1.jar` |  | Modrinth: cliente required, servidor required |
| both | Pool Table | `pooltable-forge-1.20.1-1.7.0.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | PrettyPipes | `PrettyPipes-1.15.0-all.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Puzzles Lib | `PuzzlesLib-v8.1.36-1.20.1-Forge.jar` |  | Modrinth: cliente optional, servidor optional |
| both | Real Bicycles | `real-bicycles-1.0.0.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Redden's Stone Lanterns | `reddens_stone_lanterns_1.0.3-forge1.20.1.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Redirected | `redirected-forge-1.0.0-1.20.1.jar` |  | Modrinth: cliente required, servidor required |
| both | Remove Stardust Labs Intro Message | `zRemove_SDL_Intro_v1.2.2.jar` |  | Modrinth: cliente optional, servidor required |
| both | Resourceful Lib | `resourcefullib-forge-1.20.1-2.1.29.jar` |  | Modrinth: cliente required, servidor required |
| both | Resourcefulconfig | `resourcefulconfig-forge-1.20.1-2.1.3.jar` |  | Modrinth: cliente optional, servidor optional |
| both | Ribbits | `Ribbits-1.20.1-Forge-3.0.5.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Sabor Colombiano | `saborcolombiano-1.20.1.jar` | sí | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Saturn | `saturn-mc1.20.1-0.1.3.jar` |  | Modrinth: cliente optional, servidor optional |
| both | Scaling Health | `ScalingHealth-1.20.1-8.0.2+9.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | SecurityCraft | `[1.20.1] SecurityCraft v1.10.2.1.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Serene Seasons | `SereneSeasons-forge-1.20.1-9.1.0.3.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | ShulkerBoxTooltip | `shulkerboxtooltip-forge-4.0.4+1.20.1.jar` |  | Servidor opcional -> ambos |
| both | Silent Lib | `silent-lib-1.20.1-8.0.0.jar` |  | Modrinth: cliente required, servidor required |
| both | Simple Shops | `simpleshops-1.2.2.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Simple Voice Chat | `voicechat-forge-1.20.1-2.6.27.jar` |  | Chat de voz: necesita servidor y cliente |
| both | Simply Light | `simplylight-1.20.1-1.4.6-build.50.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Simply Swords | `simplyswords-forge-neoforge-1.70.2-1.20.1.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Sky Villages | `SkyVillages-1.0.4-1.19.2-1.20.1-forge-release.jar` |  | Sin datos claros -> ambos (más seguro) |
| both | Snow Under Trees | `snowundertrees-1.20.1-1.4.12.jar` |  | Modrinth dice solo servidor, pero registra contenido -> ambos por seguridad |
| both | Snow! Real Magic! | `SnowRealMagic-1.20.1-Forge-10.7.0.jar` |  | Modrinth: cliente required, servidor required |
| both | Snowy Spirit | `snowyspirit-1.20-3.0.10.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Some Assembly Required | `some-assembly-required-1.20.1-4.2.3.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Sophisticated Backpacks | `sophisticatedbackpacks-1.20.1-3.26.20.2248.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Sophisticated Core | `sophisticatedcore-1.20.1-1.5.33.2475.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Sophisticated Storage | `sophisticatedstorage-1.20.1-1.5.17.2230.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | spark | `spark-1.10.53-forge.jar` |  | Profiler; útil en ambos lados |
| both | Spartan Shields | `SpartanShields-1.20.1-forge-3.1.1.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Spartan Weaponry | `SpartanWeaponry-1.20.1-forge-3.2.1-all.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Storage Drawers | `StorageDrawers-forge-1.20.1-12.15.1.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Structure Essentials mod | `structureessentials-1.20.1-5.1.jar` |  | Sin datos claros -> ambos (más seguro) |
| both | SuperMartijn642's Config Library | `supermartijn642configlib-1.1.8-forge-mc1.20.jar` |  | Modrinth: cliente optional, servidor optional |
| both | SuperMartijn642's Core Lib | `supermartijn642corelib-1.1.26a-forge-mc1.20.1.jar` |  | Modrinth: cliente required, servidor required |
| both | Supplementaries | `supplementaries-1.20-3.1.44-forge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | TerraBlender | `TerraBlender-forge-1.20.1-3.0.1.11.jar` |  | Modrinth: cliente required, servidor required |
| both | Terralith | `Terralith_1.20.x_v2.5.4.jar` |  | Biomas; se deja en ambos por seguridad |
| both | The Aether | `aether-1.20.1-1.5.2-neoforge.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | The Twilight Forest | `twilightforest-1.20.1-4.3.2508-universal.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Thut Core | `thutcore-1.20.1-8.9.5-arreglado.jar` | sí | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Thut Elevators | `thuttech-1.20.1-9.3.3.jar` | sí | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Timeless & Classics Guns: Zero | `tacz-forge-1.20.1-1.2.0.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Tool Belt | `ToolBelt-1.20.1-1.20.03.jar` |  | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Torchmaster | `torchmaster-20.1.9.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Towns and Towers | `Towns-and-Towers-1.12-Fabric+Forge.jar` |  | Modrinth: cliente optional, servidor required |
| both | Trade Cycling | `trade-cycling-forge-1.20.1-1.0.18.jar` |  | Modrinth: cliente required, servidor required |
| both | Trash Cans | `trashcans-1.1.2-forge-mc1.20.4.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | TrashSlot | `trashslot-forge-1.20.1-15.1.5.jar` |  | Modrinth: cliente required, servidor required |
| both | Twilight Forest: The Lost Blocks | `TF_Lost_Blocks-1.20.1-1.5.0.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | TxniLib | `txnilib-forge-1.0.24-1.20.1.jar` |  | Modrinth: cliente required, servidor required |
| both | Universal Bone Meal | `UniversalBoneMeal-v8.0.1-1.20.1-Forge.jar` |  | Modrinth: cliente required, servidor required |
| both | Universal Enchants | `UniversalEnchants-v8.0.0-1.20.1-Forge.jar` |  | Modrinth: cliente optional, servidor required |
| both | Universal Sawmill | `sawmill-1.20-1.4.11.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Untitled Duck Mod | `untitledduckmod-1.7.0-fix-forge-1.20.1.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Unusual Furniture | `unusual_furniture-1.1.1-forge-1.20.1.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | VanillaBackport | `VanillaBackport-forge-1.20.1-1.2.2.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Variants&Ventures | `variantsandventures-forge-1.0.29-mc1.20.1.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | Vein Mining | `veinmining-forge-1.5.0+1.20.1.jar` |  | Modrinth: cliente required, servidor required |
| both | Visual Workbench | `VisualWorkbench-v8.0.1-1.20.1-Forge.jar` |  | Modrinth: cliente required, servidor required |
| both | VMinus | `vminus-3.3.2.jar` |  | Modrinth: cliente required, servidor required |
| both | WaterFrames | `waterframes-FORGE-mc1.20.1-v2.2.0-beta.6-wm301.jar` | sí | Añade bloques/ítems/entidades -> requerido en ambos |
| both | Waystones | `waystones-forge-1.20.1-14.1.21.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | What Are They Up To | `watut-forge-1.20.1-1.2.3.jar` |  | Modrinth: cliente required, servidor required |
| both | Whimsy Deco | `whimsy_deco-1.2.jar` |  | Modrinth: cliente required, servidor required (añade contenido) |
| both | WorldEdit | `worldedit-mod-7.2.15.jar` |  | WorldEdit: lo usa WorldGuard en el servidor; en cliente sirve para un jugador |
| both | YetAnotherConfigLib | `yet_another_config_lib_v3-3.6.6+1.20.1-forge.jar` |  | Modrinth: cliente optional, servidor optional |
| both | YUNG's API | `YungsApi-1.20-Forge-4.0.6.jar` |  | Modrinth: cliente required, servidor required |
| both | YUNG's Better Nether Fortresses | `YungsBetterNetherFortresses-1.20-Forge-2.0.6.jar` |  | YUNG's Better Nether Fortresses: Modrinth dice solo servidor, pero Cataclysm x YUNG's (ambos) lo requiere -> ambos |
| both | Zeta | `Zeta-1.0-31.jar` |  | Modrinth: cliente required, servidor required |

## Mods quitados

- **Unofficial Varied Commodities** (`unofficial-varied-commodities-restored-1.20.1.20261017.jar`): crashea el servidor dedicado (carga una pantalla de cliente al registrar un ítem). Kaleth lo quitó de su instancia y del pack, en cliente y servidor. **Los ítems de ese mod que ya existan en un mundo desaparecerán.** CustomNPCs solo lo usaba de forma opcional.
