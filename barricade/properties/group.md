# group

* Method: \[get\]
* Returns: \[string\]

> #### Example:

```css
command barricadeGroup(){
  permission = "barricadeGroup";
  execute(){
    barricade = player.look.getBarricade();
    player.message("Barricades group:  " + barricade.group);
  }
}
```

* Method: \[set\]
* Returns: \[string\]

> #### Example:

```css
command setBarricadeGroup(groupId){
  permission = "setBarricadeGroup";
  execute(){
    barricade = player.look.getBarricade();
    barricade.group = groupId;
    player.message("Barricades group set to " + barricade.group);
  }
}
```

