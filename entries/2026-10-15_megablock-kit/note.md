# Megablock environment kit, batches 1-2

Date: 2026-10-15
Images: Blender (Cycles) renders of the modules on a neutral floor. NOT in-engine. NOT gameplay.

## What was done
- 20 low-poly modules for the setting: a decaying cyberpunk megablock occupied by debtors.
  Walls (plain, door, window, lit window, shopfront with roll-up shutter), corner pillar, roof parapet,
  gallery walkway, stairs, 6 m bridge, food stall, vending machine, AC unit, vertical neon sign,
  sagging cables, dumpster, wrecked car, concrete barrier, steel crate, poster panel.
- Every module shares ONE 1024 px texture atlas and one material. 12 to 1336 triangles per module.
- Grid: 4 m wide, 3.5 m per floor. Exported as FBX for Unity.
- A validation script re-imports every file and checks normals, closed parts, UV placement and scale. All 20 pass.

## Who did what
- Claude (chat): modelled everything with Python scripts in Blender, generated the texture atlas procedurally, wrote the validator, rendered the previews.
- The boss: art direction. Killed the first look (scrap-metal shantytown, too post-apocalyptic) and pushed it to "Cyberpunk 2077 on a budget". Picked the low-poly target from test images.

## Caveats
- Neon looks blown out to white on some renders; that is the preview lighting, not the asset.
