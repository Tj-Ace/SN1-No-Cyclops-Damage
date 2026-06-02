# Cyclops No Collision Damage

This BepInEx mod makes the original Subnautica Cyclops completely immune to
## Install

1. Copy the folder `CyclopsInvincible` into `Subnautica/BepInEx/plugins/`.
2. Make sure the DLL is inside that folder.
3. Launch Subnautica with BepInEx installed.

## What It Changes

- Blocks Cyclops health-loss handlers at runtime
- Restores Cyclops health after collision-side damage paths
- Leaves fire visuals intact so the ship can still look damaged without actually losing health

## Compatibility

- Built for original Subnautica with BepInEx installed
- Designed to be always-on
- No Nautilus settings are required

## Troubleshooting

- If the Cyclops still loses health, confirm the DLL is inside a subfolder under `BepInEx/plugins/`
- If the mod does not load, check that BepInEx is installed correctly and that the DLL is not blocked by Windows

## Notes

- The mod is intentionally focused on one job: preventing Cyclops hull health loss
- It does not change normal Cyclops fire effects, lighting, or other visual feedback
- It does not require configuration files or in-game menus
