# getStructure

* Returns: \[structure\]

> #### Example:

```css
command structurePosition(){
    permission = "structurePosition";
    execute(){
      structure = player.look.getStructure();
      player.message("Structure Position: X: " + structure.x + " Y: " + structure.y + " Z: " + structure.z);
    }
}
```

