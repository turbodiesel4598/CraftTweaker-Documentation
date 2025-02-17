# LootContext

Holds all information that may be obtainable from a loot table roll, allowing for identifying key information.

 Not all parameters are present at all times, for obvious reasons. For example, information related to an entity will
 not be available if the loot table being rolled is the one for a block.

## Importing the class

It might be required for you to import the package if you encounter any issues (like casting an Array), so better be safe than sorry and add the import at the very top of the file.
```zenscript
import crafttweaker.api.loot.LootContext;
```


## Properties

| Name | Type | Has Getter | Has Setter | Description |
|------|------|------------|------------|-------------|
| blockState | [MCBlockState](/vanilla/api/blocks/MCBlockState)? | true | false | Gets the block state that was broken, if present; null otherwise. |
| damageSource | [DamageSource](/vanilla/api/util/DamageSource)? | true | false | Gets the damage source that caused the death of the current entity, if present; null otherwise. |
| directKillerEntity | [MCEntity](/vanilla/api/entity/MCEntity)? | true | false | Gets the entity that effectively killed the current entity, if present; null otherwise. <br />  <br />  The difference between this and <code>killerEntity</code> resides on the direct-ness of the entity. For example, <br />  if a player kills a skeleton with an arrow, the player will be the <code>killerEntity</code>, while the arrow <br />  will be the <code>directKillerEntity</code>. |
| explosionRadius | float | true | false | Gets the explosion radius that caused the death of the entity or the destruction of the block, if present; 0.0 <br />  otherwise. |
| killerEntity | [MCEntity](/vanilla/api/entity/MCEntity)? | true | false | Gets the entity that caused the death of the current entity, if present; null otherwise. <br />  <br />  The entity may or may not be a player. To get only the player, refer to <code>lastDamagePlayer</code>. |
| lastDamagePlayer | [MCPlayerEntity](/vanilla/api/entity/MCPlayerEntity)? | true | false | Gets the last player that damaged the current entity, if present; null otherwise. |
| lootTableId | [MCResourceLocation](/vanilla/api/util/MCResourceLocation) | true | false | Gets the loot table id of the current one being rolled, if available; a place-holder otherwise. |
| lootingModifier | int | true | false | Gets the looting modifier, calculated based on the current parameters. |
| luck | float | true | false | Gets the luck factor of the player, as computed by the current parameters. |
| origin | [MCVector3d](/vanilla/api/util/MCVector3d)? | true | false | Gets the origin, or location, of the loot roll, if present; null otherwise. |
| thisEntity | [MCEntity](/vanilla/api/entity/MCEntity)? | true | false | Gets the current entity, if present; null otherwise. |
| tileEntity | [MCTileEntity](/vanilla/api/tileentity/MCTileEntity)? | true | false | Gets the block entity that was present at the location of the broken block, if present; null otherwise. |
| tool | [IItemStack](/vanilla/api/items/IItemStack) | true | false | Gets the tool that was used to break the block or perform additional behavior, if present; an empty stack <br />  otherwise. |
| world | [MCWorld](/vanilla/api/world/MCWorld)? | true | false | Gets the world where the interaction happened, if it exists or can be obtained; null otherwise. |

