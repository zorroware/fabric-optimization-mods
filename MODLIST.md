### Note: The incompatibilities listed are for the mods featured in this list only, and does not take into consideration any mods not featured here.

## Fabric API
Despite being a toolkit for modding functionality, Fabric API actually contains some optimizations and bugfixes. Even if you aren't planning to run any content mods, I recommend that you still use it. [Download it from GitHub](https://github.com/FabricMC/fabric).

## Rendering
| Name | <div style="width:290px">Description</div> | Developer | Incompatibilities | GitHub Link |
| --- | --- | --- | --- | --- |
| Sodium | A rendering engine replacement designed to boost your framerate and reduce random stuttering. | CaffeineMC | Canvas | https://github.com/jellysquid3/sodium-fabric |
| Canvas | A shader-oriented rendering engine replacement. Focuses on functionality over raw performance. | Grondag | Sodium | https://github.com/grondag/canvas |
| Cull Particles | This mod adds culling to particles. Redundant if using Sodium, as Sodium has its own implementation, but this should be used by Canvas or Vanilla users. | Tfarcenim | Sodium (redundant) | https://github.com/Tfarcenim/CullParticlesFabric |
| Enhanced Block Entities | Replaces most block entities with baked models. Also allows more customization using JSON. Depends on FRAPI and thus requires [Indium](https://github.com/comp500/Indium) if using Sodium. | FoundationGames | Unknown | https://github.com/FoundationGames/EnhancedBlockEntities |

## Server
| Name | <div style="width:290px">Description</div> | Developer | Incompatibilities | GitHub Link |
| --- | --- | --- | --- | --- |
| Lithium | A mod that optimizes some aspects of Minecraft's server, while maintaining behavior identical to vanilla. Works in singleplayer. | CaffeineMC | Unknown | https://github.com/jellysquid3/lithium-fabric |

## Lighting
| Name | <div style="width:290px">Description</div> | Developer | Incompatibilities | GitHub Link |
| --- | --- | --- | --- | --- |
| Phosphor | A smaller mod that makes Minecraft's bulky and slow lighting engine much faster. | Jellysquid | Starlight | https://github.com/jellysquid3/phosphor-fabric |
| Starlight | **WARNING: Uses non-free Mojang mappings!**<br>An experimental mod that can speed up lighting calculations by 26x compared to Phosphor (according to the developer). | Spottedleaf | Phosphor | https://github.com/Spottedleaf/Starlight |

## Memory
| Name | <div style="width:290px">Description</div> | Developer | Incompatibilities | GitHub Link |
| --- | --- | --- | --- | --- |
| Hydrogen | Reduces RAM usage of Minecraft by compacting models and other misc. data. More effective with more content mods. | CaffeineMC | DashLoader | https://github.com/jellysquid3/hydrogen-fabric |
| FerriteCore | **WARNING: Uses non-free MCP mappings!**<br>A mod similar to Hydrogen that employs more memory-efficient logic. Works very well with Hydrogen. | malte0811 | Unknown | https://github.com/malte0811/FerriteCore |

## Network
| Name | <div style="width:290px">Description</div> | Developer | Incompatibilities | GitHub Link |
| --- | --- | --- | --- | --- |
| Krypton | Optimizations for Minecraft's general networking. If you're at a bandwidth bottleneck then this can help. | astei | Unknown | https://github.com/astei/krypton |

## Start-up
| Name | <div style="width:290px">Description</div> | Developer | Incompatibilities | GitHub Link |
| --- | --- | --- | --- | --- |
| LazyDFU | Prevents DFU from being built until it is needed. | astei | Unknown | https://github.com/astei/lazydfu |
| DashLoader | Builds caches to load the game much faster. Works with LazyDFU but is extremely invasive and incompatible with many mods. | alphaqu | Hydrogen | https://github.com/alphaqu/DashLoader |

## Extras
### These mods are extras that do not improve game performance.
| Name | <div style="width:290px">Description</div> | Developer | Incompatibilities | GitHub Link |
| --- | --- | --- | --- | --- |
| Sodium Extra Fabric (Requires Sodium) | Adds more graphical settings to Sodium, similar to OptiFine's. | FlashyReese | Unknown | https://github.com/FlashyReese/sodium-extra-fabric/ |
| Dynamic FPS | Slows down Minecraft's rendering when Minecraft is minimized or in the background to improve performance in other applications. | juliand665 | Unknown | https://github.com/juliand665/Dynamic-FPS |
