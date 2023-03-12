# ClearLagg
Delete entities, diagnose, or use one of clearlagg's many utilities to reduce lag.

### Description
*Designed with reducing lag as the primary goal, clearlag has grown over the years to target multiple sources of lag/exploits that plague minecraft servers and drastically decrease overall performance. Whether it be by culling entities, limiting mob-spawners, limiting mob-eggs, limiting mob-breeding, setting per-item entity live-time, the list goes on. Clearlag's main purpose is to give the server owner complete control over what they feel is suitable for their specific server type rather then enforcing strict rules or limiting vanilla features at a poor attempt to help decrease the server's full-tick. Prevention is the key to a high performance server. You may also use clearlag's profilers/samplers to diagnose why your server is spiking when timings are simply not enough. Even giving you the ability to view the JVM's garbage collection impact on your full-tick. Contrary to popular belief, Clearlag has virtually no impact on TPS, to the point you likely wont even see it register on a timings report.*

### Features:

-   MANY useful entity limiters all completely configurable
-   TPS/RAM meter that can execute commands
-   Option to reduce TNT lag or chain reactions
-   Option to limit mob spawners
-   Locate overcrowded/abused chunks
-   Many easy to use commands, including profiles
-   Full control over modules
-   Very lightweight - only enables selected features
-   Remove old logs upon enabling server (Configurable)
-   Limit AI processing attributes to save CPU
-   Full-tick sampler (Also displays spikes)
-   Everything's configurable
-   Much more.. Can't list it all ¯\_(ツ)_/¯

### Commands:
*(Permission are just lagg.command-name)*
  -   **/lagg clear**  (Clears configured entities)
-   **/lagg check [world1, world2...]** (Displays world information + more)
-   **/lagg reload**  (Reloads the configuration)
-   **/lagg killmobs** (Kills configured mobs)
-   **/lagg area <radius>**  (Removes entities in given radius)
-   **/lagg tpchunk <x> <z> [world]** (Teleports to given chunk)
-   **/lagg admin**  (Manage modules)
-   **/lagg gc**  (Force request Garbage collection [NOT RECOMMENDED])
-   **/lagg tps** (View estimated TPS [Not as accurate as Spigot's /tps])
-   **/lagg halt**  (Temporary disable configured basic server functions)
-   **/lagg sampleMemory**  <time> (Sample memory usage per-tick, and garbage collection timings)
-   **/lagg sampleTicks**  <ticks> [raw] (Sample how long ticks took to complete)
-   **/lagg unloadchunks**  (Attempts to unload chunks - [Not recommended on later Spigot's])
-   **/lagg profile <time> <type>**  (Profile certain activities such as redstone to see which chunk is the most active)
-   **/lagg memory** (View your memory heap in realtime)
-   **/lagg performance** (View your main-thread usage in real-time)
  
  ### Extra Modules:
  [SaveDeathDrops](http://dev.bukkit.org/bukkit-plugins/clearlag-savedeathdrops/): Block's Clearlag from removing items dropped by player's on death
  
  ### Supported Languages:
  *(To change your language, navigate to Clearlag's config.yml, and change settings.language from English to your desired language.)*
  -   Brazilianportuguese
-   Chinesesimplified
-   ChineseTraditional
-   Czech
-   English
-   French
-   German
-   Japanese
-   Korean
-   Polish
-   Russian
-   Spanish
