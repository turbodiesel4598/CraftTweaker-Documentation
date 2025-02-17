# MCEntity

## Importing the class

It might be required for you to import the package if you encounter any issues (like casting an Array), so better be safe than sorry and add the import at the very top of the file.
```zenscript
import crafttweaker.api.entity.MCEntity;
```


## Methods

:::group{name=addTag}

Return Type: boolean

```zenscript
MCEntity.addTag(tag as string) as boolean
```

| Parameter | Type | Description |
|-----------|------|-------------|
| tag | string | No Description Provided |


:::

:::group{name=addVelocity}

Return Type: void

```zenscript
MCEntity.addVelocity(x as double, y as double, z as double) as void
```

| Parameter | Type | Description |
|-----------|------|-------------|
| x | double | No Description Provided |
| y | double | No Description Provided |
| z | double | No Description Provided |


:::

:::group{name=applyEntityCollision}

Return Type: void

```zenscript
MCEntity.applyEntityCollision(entityIn as MCEntity) as void
```

| Parameter | Type | Description |
|-----------|------|-------------|
| entityIn | [MCEntity](/vanilla/api/entity/MCEntity) | No Description Provided |


:::

:::group{name=canSwim}

Return Type: boolean

```zenscript
// MCEntity.canSwim() as boolean

myMCEntity.canSwim();
```

:::

:::group{name=changeDimension}

Return Type: void

```zenscript
MCEntity.changeDimension(world as MCServerWorld) as void
```

| Parameter | Type | Description |
|-----------|------|-------------|
| world | [MCServerWorld](/vanilla/api/world/MCServerWorld) | No Description Provided |


:::

:::group{name=extinguish}

Return Type: void

```zenscript
// MCEntity.extinguish() as void

myMCEntity.extinguish();
```

:::

:::group{name=forceFireTicks}

Return Type: void

```zenscript
MCEntity.forceFireTicks(ticks as int) as void
```

| Parameter | Type | Description |
|-----------|------|-------------|
| ticks | int | No Description Provided |


:::

:::group{name=forceSetPosition}

Return Type: void

```zenscript
MCEntity.forceSetPosition(x as double, y as double, z as double) as void
```

| Parameter | Type | Description |
|-----------|------|-------------|
| x | double | No Description Provided |
| y | double | No Description Provided |
| z | double | No Description Provided |


:::

:::group{name=getAir}

Return Type: int

```zenscript
// MCEntity.getAir() as int

myMCEntity.getAir();
```

:::

:::group{name=getBrightness}

Return Type: float

```zenscript
// MCEntity.getBrightness() as float

myMCEntity.getBrightness();
```

:::

:::group{name=getData}

Return Type: [MapData](/vanilla/api/data/MapData)

```zenscript
// MCEntity.getData() as MapData

myMCEntity.getData();
```

:::

:::group{name=getDistance}

Return Type: float

```zenscript
MCEntity.getDistance(entityIn as MCEntity) as float
```

| Parameter | Type | Description |
|-----------|------|-------------|
| entityIn | [MCEntity](/vanilla/api/entity/MCEntity) | No Description Provided |


:::

:::group{name=getDistanceSq}

Return Type: double

```zenscript
MCEntity.getDistanceSq(entityIn as MCEntity) as double
```

| Parameter | Type | Description |
|-----------|------|-------------|
| entityIn | [MCEntity](/vanilla/api/entity/MCEntity) | No Description Provided |


:::

:::group{name=getDistanceSq}

Return Type: double

```zenscript
MCEntity.getDistanceSq(x as double, y as double, z as double) as double
```

| Parameter | Type | Description |
|-----------|------|-------------|
| x | double | No Description Provided |
| y | double | No Description Provided |
| z | double | No Description Provided |


:::

:::group{name=getEntityId}

Return Type: int

```zenscript
// MCEntity.getEntityId() as int

myMCEntity.getEntityId();
```

:::

:::group{name=getFireTimer}

Return Type: int

```zenscript
// MCEntity.getFireTimer() as int

myMCEntity.getFireTimer();
```

:::

:::group{name=getMaxInPortalTime}

Return Type: int

```zenscript
// MCEntity.getMaxInPortalTime() as int

myMCEntity.getMaxInPortalTime();
```

:::

:::group{name=getName}

Return Type: string

```zenscript
// MCEntity.getName() as string

myMCEntity.getName();
```

:::

:::group{name=getPosition}

Return Type: [BlockPos](/vanilla/api/util/BlockPos)

```zenscript
// MCEntity.getPosition() as BlockPos

myMCEntity.getPosition();
```

:::

:::group{name=getTags}

Return Type: Set&lt;string&gt;

```zenscript
// MCEntity.getTags() as Set<string>

myMCEntity.getTags();
```

:::

:::group{name=getType}

Return Type: [MCEntityType](/vanilla/api/entities/MCEntityType)

```zenscript
// MCEntity.getType() as MCEntityType

myMCEntity.getType();
```

:::

:::group{name=getUUID}

Return Type: string

```zenscript
// MCEntity.getUUID() as string

myMCEntity.getUUID();
```

:::

:::group{name=getWorld}

Return Type: [MCWorld](/vanilla/api/world/MCWorld)

```zenscript
// MCEntity.getWorld() as MCWorld

myMCEntity.getWorld();
```

:::

:::group{name=hasNoGravity}

Return Type: boolean

```zenscript
// MCEntity.hasNoGravity() as boolean

myMCEntity.hasNoGravity();
```

:::

:::group{name=isEntityInRange}

Return Type: boolean

```zenscript
MCEntity.isEntityInRange(entity as MCEntity, distance as double) as boolean
```

| Parameter | Type | Description |
|-----------|------|-------------|
| entity | [MCEntity](/vanilla/api/entity/MCEntity) | No Description Provided |
| distance | double | No Description Provided |


:::

:::group{name=isImmuneToFire}

Return Type: boolean

```zenscript
// MCEntity.isImmuneToFire() as boolean

myMCEntity.isImmuneToFire();
```

:::

:::group{name=isInLava}

Return Type: boolean

```zenscript
// MCEntity.isInLava() as boolean

myMCEntity.isInLava();
```

:::

:::group{name=isInWater}

Return Type: boolean

```zenscript
// MCEntity.isInWater() as boolean

myMCEntity.isInWater();
```

:::

:::group{name=isInWaterOrBubbleColumn}

Return Type: boolean

```zenscript
// MCEntity.isInWaterOrBubbleColumn() as boolean

myMCEntity.isInWaterOrBubbleColumn();
```

:::

:::group{name=isInWaterRainOrBubbleColumn}

Return Type: boolean

```zenscript
// MCEntity.isInWaterRainOrBubbleColumn() as boolean

myMCEntity.isInWaterRainOrBubbleColumn();
```

:::

:::group{name=isOffsetPositionInLiquid}

Return Type: boolean

```zenscript
MCEntity.isOffsetPositionInLiquid(x as double, y as double, z as double) as boolean
```

| Parameter | Type | Description |
|-----------|------|-------------|
| x | double | No Description Provided |
| y | double | No Description Provided |
| z | double | No Description Provided |


:::

:::group{name=isOnGround}

Return Type: boolean

```zenscript
// MCEntity.isOnGround() as boolean

myMCEntity.isOnGround();
```

:::

:::group{name=isSilent}

Return Type: boolean

```zenscript
// MCEntity.isSilent() as boolean

myMCEntity.isSilent();
```

:::

:::group{name=isSpectator}

Return Type: boolean

```zenscript
// MCEntity.isSpectator() as boolean

myMCEntity.isSpectator();
```

:::

:::group{name=isWet}

Return Type: boolean

```zenscript
// MCEntity.isWet() as boolean

myMCEntity.isWet();
```

:::

:::group{name=moveForced}

Return Type: void

```zenscript
MCEntity.moveForced(x as double, y as double, z as double) as void
```

| Parameter | Type | Description |
|-----------|------|-------------|
| x | double | No Description Provided |
| y | double | No Description Provided |
| z | double | No Description Provided |


:::

:::group{name=onCollideWithPlayer}

Return Type: void

```zenscript
MCEntity.onCollideWithPlayer(entityIn as MCPlayerEntity) as void
```

| Parameter | Type | Description |
|-----------|------|-------------|
| entityIn | [MCPlayerEntity](/vanilla/api/entity/MCPlayerEntity) | No Description Provided |


:::

:::group{name=onKillCommand}

Return Type: void

```zenscript
// MCEntity.onKillCommand() as void

myMCEntity.onKillCommand();
```

:::

:::group{name=onLivingFall}

Return Type: boolean

```zenscript
MCEntity.onLivingFall(distance as float, damageMultiplier as float) as boolean
```

| Parameter | Type | Description |
|-----------|------|-------------|
| distance | float | No Description Provided |
| damageMultiplier | float | No Description Provided |


:::

:::group{name=removeTag}

Return Type: boolean

```zenscript
MCEntity.removeTag(tag as string) as boolean
```

| Parameter | Type | Description |
|-----------|------|-------------|
| tag | string | No Description Provided |


:::

:::group{name=setAir}

Return Type: void

```zenscript
MCEntity.setAir(air as int) as void
```

| Parameter | Type | Description |
|-----------|------|-------------|
| air | int | No Description Provided |


:::

:::group{name=setEntityId}

Return Type: void

```zenscript
MCEntity.setEntityId(id as int) as void
```

| Parameter | Type | Description |
|-----------|------|-------------|
| id | int | No Description Provided |


:::

:::group{name=setFire}

Return Type: void

```zenscript
MCEntity.setFire(seconds as int) as void
```

| Parameter | Type | Description |
|-----------|------|-------------|
| seconds | int | No Description Provided |


:::

:::group{name=setNoGravity}

Return Type: void

```zenscript
MCEntity.setNoGravity(noGravity as boolean) as void
```

| Parameter | Type | Description |
|-----------|------|-------------|
| noGravity | boolean | No Description Provided |


:::

:::group{name=setOnGround}

Return Type: void

```zenscript
MCEntity.setOnGround(grounded as boolean) as void
```

| Parameter | Type | Description |
|-----------|------|-------------|
| grounded | boolean | No Description Provided |


:::

:::group{name=setPosition}

Return Type: void

```zenscript
MCEntity.setPosition(x as double, y as double, z as double) as void
```

| Parameter | Type | Description |
|-----------|------|-------------|
| x | double | No Description Provided |
| y | double | No Description Provided |
| z | double | No Description Provided |


:::

:::group{name=setSilent}

Return Type: void

```zenscript
MCEntity.setSilent(isSilent as boolean) as void
```

| Parameter | Type | Description |
|-----------|------|-------------|
| isSilent | boolean | No Description Provided |


:::

:::group{name=teleportKeepLoaded}

Teleports the entity, forcing the destination to stay loaded for a short time

Return Type: void

```zenscript
MCEntity.teleportKeepLoaded(x as double, y as double, z as double) as void
```

| Parameter | Type | Description |
|-----------|------|-------------|
| x | double | No Description Provided |
| y | double | No Description Provided |
| z | double | No Description Provided |


:::

:::group{name=updateData}

Return Type: void

```zenscript
MCEntity.updateData(data as MapData) as void
```

| Parameter | Type | Description |
|-----------|------|-------------|
| data | [MapData](/vanilla/api/data/MapData) | No Description Provided |


:::


## Properties

| Name | Type | Has Getter | Has Setter | Description |
|------|------|------------|------------|-------------|
| air | int | true | true | No Description Provided |
| data | [MapData](/vanilla/api/data/MapData) | true | false | No Description Provided |
| facingDirections | [Direction](/vanilla/api/util/Direction)[] | true | false | No Description Provided |
| name | string | true | false | No Description Provided |
| position | [BlockPos](/vanilla/api/util/BlockPos) | true | false | No Description Provided |
| uuid | string | true | false | No Description Provided |
| world | [MCWorld](/vanilla/api/world/MCWorld) | true | false | No Description Provided |

