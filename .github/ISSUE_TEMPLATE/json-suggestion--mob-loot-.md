---
name: JSON suggestion (Mob/Loot)
about: Suggest a JSON compatibility file for either mob or loot addition.
title: "[JSON suggestion] Compatibility for MOD_ID"
labels: compatibility
assignees: ''

---

## JSON structure
You can learn about how to make compatibility JSON files at the [mod's description page](https://www.curseforge.com/minecraft/mc-mods/lrs-dynamic-dungeon) in the **Content addition** section.

## Mod Name / ID
(e.g. my_mod_id)

## Type of Addition
- [ ] Mob Pool
- [ ] Loot Pool

## Folder Structure
If you are only adding **one** type of addition (mob **OR** loot), then simply have all the json files for each stage in one folder, for example:
- `my_mod_id/`  
  └── `stage_1.json`  
  └── `stage_3.json`
  └── etc...

If you are adding **both** types of addition (mob **AND** loot), then ensure you mark which folder is for which, for example:
- `enemy_pool/compatibility/my_mod_id/`  
  └── `stage_1.json`  
  └── `stage_3.json`
  └── etc...
- `dungeon_loot/compatibility/my_mod_id/`  
  └── `stage_2.json`  
  └── `stage_3.json`
  └── etc...

## Submission
Attach your folder(s) as a `.zip` file or link to a GitHub Gist or repository containing the files.

## Notes
(Optional) Any additional context, special NBT setups, or mod-specific logic you'd like to highlight?
