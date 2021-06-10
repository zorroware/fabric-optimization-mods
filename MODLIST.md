### Note: The incompatibilities listed are for the mods featured in this list only, and does not take into consideration any mods not featured here.

## Fabric API
Despite being a toolkit for modding functionality, Fabric API actually contains some optimizations and bugfixes. Even if you aren't planning to run any content mods, I recommend that you still use it. [Download it from GitHub](https://github.com/FabricMC/fabric).

## Rendering
| Name | <div style="width:290px">Description</div> | Developer | Stable | Dangerous | Incompatibilities | GitHub Link |
| --- | --- | --- | --- | --- | --- | --- |
| Sodium | A rendering engine replacement designed to boost your framerate and reduce random stuttering. | CaffeineMC | Mostly | No | Canvas | https://github.com/jellysquid3/sodium-fabric/ |
| Canvas | A shader-oriented rendering engine replacement. Focuses on functionality over raw performance. | Grondag | Yes | No | Sodium | https://github.com/grondag/canvas/ |
| Cull Leaves | A renderer tweak that implements leaf culling similar to OptiFine's. NOTE: This will negatively impact visuals! | TeamMidnightDust | Yes | No | None | https://github.com/TeamMidnightDust/CullLeaves/ |
| Entity Culling | A rendering tweak that implements asynchronous culling to entities. | tr7zw | No | No | None | https://github.com/tr7zw/EntityCulling-Fabric/ |
| Better Beds | Makes Minecraft use the built-in renderer for beds rather than the custom one, to improve rendering performance when around beds. | TeamMidnightDust | No | No | None | https://github.com/TeamMidnightDust/BetterBeds/ |

## Server
| Name | <div style="width:290px">Description</div> | Developer | Stable | Dangerous | Incompatibilities | GitHub Link |
| --- | --- | --- | --- | --- | --- | --- |
| Lithium | A mod that optimizes some aspects of Minecraft's server, while maintaining behavior identical to vanilla. Works in singleplayer. | CaffeineMC | Yes | No | None | https://github.com/jellysquid3/lithium-fabric/ |

## Lighting
| Name | <div style="width:290px">Description</div> | Developer | Stable | Dangerous | Incompatibilities | GitHub Link |
| --- | --- | --- | --- | --- | --- | --- |
| Phosphor | A smaller mod that makes Minecraft's bulky and slow lighting engine much faster. | Jellysquid | Yes | No | Starlight | https://github.com/jellysquid3/phosphor-fabric |
| Starlight | An experimental mod that can speed up lighting calculations by 26x compared to Phosphor (according to the developer). | Spottedleaf | Mostly | No | Phosphor | https://github.com/Spottedleaf/Starlight/ |

## Memory
| Name | <div style="width:290px">Description</div> | Developer | Stable | Dangerous | Incompatibilities | GitHub Link |
| --- | --- | --- | --- | --- | --- | --- |
| Hydrogen | Reduces RAM usage of Minecraft by compacting models and other misc. data. More effective with more content mods. | CaffeineMC | Yes | No | None | https://github.com/jellysquid3/hydrogen-fabric/ |

## Network
| Name | <div style="width:290px">Description</div> | Developer | Stable | Dangerous | Incompatibilities | GitHub Link |
| --- | --- | --- | --- | --- | --- | --- |
| Krypton | Optimizations for Minecraft's general networking. If you're at a bandwidth bottleneck then this can help. | astei | Somewhat | No | None | https://github.com/astei/krypton |

## Start-up
| Name | <div style="width:290px">Description</div> | Developer | Stable | Dangerous | Incompatibilities | GitHub Link |
| --- | --- | --- | --- | --- | --- | --- |
| Cadmium | Loader for Jellysquid's optimized fork of Mojang's DataFixerUpper. Speeds up game loading. LucilleTea's port is required for 1.16.x. | Jellysquid, LucilleTea (port) | No | Yes | None | https://github.com/jellysquid3/cadmium-fabric/, https://github.com/LucilleTea/cadmium-fabric/ |
| LazyDFU | Prevents DFU from being built until it is needed. Compatible with Cadmium and I highly recommend using these two together. | astei | Yes | No | None | https://github.com/astei/lazydfu/ |

## Extra Utility
### Note: These mods are extras that do not improve game performance.
| Name | <div style="width:290px">Description</div> | Developer | Stable | Dangerous | Incompatibilities | GitHub Link |
| --- | --- | --- | --- | --- | --- | --- |
| Sodium Extra Fabric (Requires Sodium) | Adds more graphical settings to Sodium, similar to OptiFine's. | FlashyReese | No | No | Canvas | https://github.com/FlashyReese/sodium-extra-fabric/ |
| Dynamic FPS | Slows down Minecraft's rendering when Minecraft is minimized or in the background to improve performance in other applications. | juliand665 | Yes | No | None | https://github.com/juliand665/Dynamic-FPS/ |
