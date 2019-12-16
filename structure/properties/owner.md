# owner

* Method: \[get\]
* Returns: \[string\]

> #### Example:

```css
command structureOwner(){
  permission = "structureOwner";
  execute(){
    structure = player.look.getStructure();
    player.message("Structures owners steam id:  " + structure.owner);
  }
}
```

* Method: \[set\]
* Returns: \[string\]

> #### Example:

```css
command setstructureOwner(ownerId){
  permission = "setstructureOwner";
  execute(){
    structure = player.look.getStructure();
    structure.owner = ownerId;
    player.message("Structures owner set to " + structure.owner);
  }
}
```

