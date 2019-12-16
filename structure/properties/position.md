# position

* Method: \[get\]
* Returns: \[vector3\]

> #### Example:

```css
command getStrucurePosition(){
  permission = "getStrucurePosition";
  execute(){
    structure = player.look.getStructure();
    player.message("Structure Position: X: " + structure.position.x + " Y: " + structure.position.y + " Z: " + structure.position.z);
  }
}
```

* Method: \[set\]
* Returns: \[vector3\]

> #### Example:

```css
command setStructurePosition(){
  permission = "setStructurePosition";
  execute(){
    structure = player.look.getStructure();
    structure.position = player.position;
    player.message("Structure position set to your location!");
  }
}
```

