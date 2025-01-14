# CreateExplosion

### Description

Creates a deadly explosion killing players and applying force to parts at the given position.

Function of [Environment](/classes/Environment/)

#### Parameters

position `Vector3`

radius `number, default = 10`

force `number, default = 5000`

affectAnchored `Boolean, default = true`

callback `DynValue, default = nil`

#### Returns

`void`

### Example

```lua
game["Environment"]:CreateExplosion(Vector3.New(0, 0, 0), 30, 5000, false)
```

### Notes

- When true, AffectAnchored will unanchor parts within the explosion radius.
- Callback gets called for each part within explosion radius.
