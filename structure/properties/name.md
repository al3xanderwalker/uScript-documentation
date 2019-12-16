# name

* Method: \[get\]
* Returns: \[string\]

> #### Example:

```css
command structureName(){
  permission = "structureName";
  execute(){
    structure = player.look.getStructure();
    player.message("Structures name:  " + structure.name);
  }
}
```

