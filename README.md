<p align="center">
  <img src="https://i.imgur.com/xcxtzPA.png">
</p>

Take a break inside a local tavern and pull out your trusty pipe! You can additionally set the custom model data, here is an [example resource pack](https://github.com/Rausy/resource-packs/raw/master/Tobacco_Pipes.zip) that makes use of it.

<p align="center">
  <img src="https://i.imgur.com/hXTBMEf.gif">
</p>

## Features
- Smokable pipes with various plant materials
- Different materials give different potion effects!
- Night vision from cornflowers
- Water breathing from lily pads and seagrass
- Luck from oak leaves and flowering azalea
- Darkness from dark oak leaves
- And many more combinations!

## Usage
Craft a marijuana pipe with a bowl and a stick, then hold any smokable plant material in your off hand to refill your pipe. Smoke away and enjoy the effects!

## Smokable Materials
The following materials can be used to fill your pipe:
- **Grasses**: Short Grass, Fern, Large Fern, Tall Grass
- **Aquatic Plants**: Lily Pad, Seagrass, Tall Seagrass (water breathing)
- **Leaves**: All tree leaf types (oak, spruce, birch, jungle, acacia, dark oak, mangrove, cherry, azalea)
- **Flowers**: Dandelion, Poppy, Blue Orchid, Allium, Azure Bluet, Tulips, Oxeye Daisy, Cornflower, Lily of the Valley, Wither Rose, Torchflower, Sunflower, Lilac, Rose Bush, Peony, Pitcher Plant
- **Other**: Glow Lichen

Each material provides unique potion effects when smoked!

## Config
```yaml
# Smokable materials and their effects
# Format: MATERIAL: [EFFECT:DURATION:AMPLIFIER, ...]
smokables:
  SHORT_GRASS: []
  CORNFLOWER: [NIGHT_VISION:600:0]
  LILY_PAD: [WATER_BREATHING:600:0]
  OAK_LEAVES: [LUCK:400:0]
  # ... and many more!

# What custom model data should marijuana pipes have?
customModelData: 1

# How much "charge" does each smokable material add?
refillAmount: 15
```

## Commands
**/pipes info** - Plugin version

**/pipes reload** - Reload config (OP)

## Permissions
pipes.reload (OP)

## Compatibility
- Minecraft 1.21+
- Updated for modern Minecraft versions
- Uses current material names (SHORT_GRASS instead of deprecated GRASS)
