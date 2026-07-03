# Farmatica Farms

This repository stores the public farm schematic database for the Farmatica Minecraft Fabric mod.

Farmatica lets players browse, download, and use farm schematics from inside Minecraft. This repository contains the JSON farm lists used by the mod, plus the downloadable `.litematic` schematic files for official and community farms.

## Folders

- `api/farms/official` contains the list of official Farmatica farms.
- `api/farms/community` contains the list of approved community farms.
- `schematics/official/` contains official `.litematic` files.
- `schematics/community/` contains approved community `.litematic` files.

## Submissions

Community submissions are reviewed before being added. Approved farms can be added to the community JSON list and uploaded to the `schematics/community/` folder.

## Farm JSON Format

Each farm entry should look like this:

```json
{
  "id": "starter-iron-farm",
  "name": "Starter Iron Farm",
  "author": "gui_Arther__0jo",
  "description": "Simple early-game iron farm.",
  "category": "Iron",
  "downloadUrl": "https://raw.githubusercontent.com/YOUR_GITHUB_USERNAME/farmatica-farms/main/schematics/official/starter-iron-farm.litematic",
  "official": true
}
