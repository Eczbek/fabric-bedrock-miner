# Fabric-Bedrock-Miner
A Fabric client mod to "mine" bedrock!

This is a fork of [bunnyi116's fork](https://github.com/bunnyi116/fabric-bedrock-miner) of [LXYan2333's mod](https://github.com/LXYan2333/Fabric-Bedrock-Miner)

I removed the hardcoded blacklist.

<br>

#### Block whitelist (break supported)
- Bedrock

#### Block to add command filters
- Air
- Replaceable blocks

### Command description
- `/bedrockMiner` on/off
- `/bedrockMiner disable` disable the mod (the mod will not continue to process after it is turned on)
- `/bedrockMiner behavior floor add <floor>` add a floor to the blacklist.
- `/bedrockMiner behavior floor remove <floor>` remove a floor from the blacklist.
- `/bedrockMiner behavior block whitelist add <block>` add whitelist block list
- `/bedrockMiner behavior block whitelist remove <block>` remove whitelist block list
- `/bedrockMiner task add <x, y, z>` add a task
- `/bedrockMiner task shortWait <bool>` short custom wait
- `/bedrockMiner task clear` clear the task
- `/bedrockMiner debug true` enables debug mode
- `/bedrockMiner debug false` turn off debug mode

# Showcase
https://www.youtube.com/watch?v=b8Y86yxjr_Y  
https://www.bilibili.com/video/BV1Fv411P7Vc

# Usage
Have the following items ready:
1. Efficiency V diamond (or netherite) pickaxe
2. Haste II beacon
3. Pistons
4. Redstone torches
5. Slime blocks

Right click bedrock **with an empty hand** to switch on/off.

While the mod is enabled, left click bedrock to "mine" it.

# Compile
1. Run `gradle build` in this directory
2. See `build/libs/`
