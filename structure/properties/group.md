# group

* Method: \[get\]
* Returns: \[string\]

> #### Example:

```css
command structureGroup(){
  permission = "structureGroup";
  execute(){
    structure = player.look.getStructure();
    player.message("Structures group:  " + structure.group);
  }
}
```

* Method: \[set\]
* Returns: \[string\]

> #### Example:

```css
command setStructureGroup(groupId){
  permission = "setStructureGroup";
  execute(){
    structure = player.look.getStructure();
    structure.group = groupId;
    player.message("Structures group set to " + structure.group);
  }
}
```

