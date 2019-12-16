# destroy

* Parameters: \[none\]

> #### Example:

```css
command destroyStructure(){
  permission = "destroyStructure";
  execute(){
    structure = player.look.getStructure();
    structure.destroy();
    player.message("Structure Destroyed!");
  }
}
```

