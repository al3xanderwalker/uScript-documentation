# hasGroup

* Parameters: \[text\]

> #### Example:

```css
command hasGroup(groupName){
  permission = "hasGroup";
  execute(){
    if(player.hasGrouo(groupName)){
      player.message("You have the group" + groupName);
    }
    else{
      player.message("You do not have the group" + groupName);
    }
  }
}
```

