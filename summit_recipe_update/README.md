# Summit State Roleplay — ND development recipe v0.2

This is a **development scaffold**, not a ready-to-play server. It downloads ND_Core, ND_Police, ND_MDT, ND_Characters, and ND_Banking source repositories. It does **not** automatically install the required built releases of oxmysql, ox_lib, ox_inventory, ox_target, nor configure their SQL, vMenu, Discord roles, economy values, vehicle systems or EUP packs. Do not deploy as a production server.

## Required next steps
1. Install compatible release builds of oxmysql, ox_lib, ox_inventory and ox_target; some repositories' source code cannot be used directly as release resources.
2. Set FiveM license key and database connection string privately in the hosting environment; never commit them.
3. Import the SQL required by the installed resource versions.
4. Check compatibility of ND addon versions and confirm ND_Characters supports your intended 3-character design; customize if needed.
5. Add and test a Discord role verification bridge for LSPD (1562452054478295070), BCSO (1561112578879520890), SAHP (1561112299589083308); staff-only vMenu must be implemented and tested separately.
6. Test resources on a fresh nonproduction server before uncommenting the `ensure` lines in `server.cfg`.

## Intended design (not yet implemented)
Starting bank $5,000, starting cash $500, balanced job progression, 3 characters, civilian and criminal combined, realistic vehicle financing/insurance, and staff-only vMenu.

## Sources
- https://github.com/ND-Framework/ND_Core
- https://github.com/ND-Framework/ND_Police
- https://github.com/ND-Framework/ND_MDT
