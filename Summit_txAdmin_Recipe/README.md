# Summit State Roleplay — txAdmin recipe starter

This is a **development bootstrap**, NOT the finished Summit economy server. It downloads source repositories and writes a minimal server.cfg. It has not been deployed or tested with txAdmin.

## Current status
- Downloads ND_Core, ND_Police, ND_MDT source from their public GitHub repositories. Branch and repository structure may change; verify before deployment.
- Downloads ox_target **source**, which is not a built, ready-to-run release. Install a compatible built release separately.
- Does not install ox_lib, oxmysql, pma-voice, vMenu, or any other required dependencies.
- Does not enable ND resources until dependencies are present.
- Does not include a character selector, banking integration, vehicle financing, Discord permissions runtime, EUP or vehicle assets.

## Approved Summit settings (not implemented)
- Starting bank: $5,000; cash: $500
- Standard job progression
- Realistic vehicle ownership, loans, registration and insurance
- 3 characters per player; civilian and criminal activity on same character
- LSPD Discord role: 1562452054478295070
- BCSO Discord role: 1561112578879520890
- SAHP Discord role: 1561112299589083308
- Owner: 1561100807167025271
- Admin roles: 1561151180732899418, 1561150948561129513, 1561208047278489642
- Discord guild: 1561099712365330462
- vMenu for staff only

## Publishing
Upload `recipe.yaml` to the root of your public GitHub repository `Linguine69/Summit-State-Roleplay`. The resulting URL will be:
https://raw.githubusercontent.com/Linguine69/Summit-State-Roleplay/main/recipe.yaml

**Do not deploy this as a finished server.** Check the recipe with a disposable test server, resolve dependencies, then implement and test each missing Summit feature.

Never publish your bot token, database password, or FiveM licence key.
