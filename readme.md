
# Glock 43X

A custom weapon for fivem!

# Installation

- Put the `LightSaber` into your `resources` folder.
- ensure LightSaber - add this line in your `server.cfg`

# If using ox_inventory

- Place in `ox_inventory/data/weapons.lua`
```lua
    ['WEAPON_GLOCK43X'] 			  = { label = 'Glock 43x',         weight = 1000,	durability = 0.0,	ammoname = 'ammo-45',},
```

# If using QBCore & qb-inventory

- Place in `qb-core/shared/items.lua`
```lua
['weapon_glock43x'] 			     = {['name'] = 'weapon_glock43x', 			 	['label'] = 'Glock 22', 				['weight'] = 7000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',			['image'] = 'weapon_glock43x.png', 						['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'pistol'},
```
- Drop the next code in `qb-core/shared/weapons.lua`
```lua
[`weapon_glock43x`] 		 = {['name'] = 'weapon_glock43x', 		['label'] = 'Glock 22', 			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
```
- Drop the next code in `qb-weapons/config.lua`
```lua
    ['weapon_glock43x'] 	             = 0.15,
```
- Add the weapon name in `qb-smallresources/client/weapdraw.lua`
```lua
    `weapon_glock43x`
```
# Credits
- [qcvntrx](https://www.gta5-mods.com/users/qcvntrx)
