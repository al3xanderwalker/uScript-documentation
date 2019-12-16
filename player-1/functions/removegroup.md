# removeGroup

* Parameters: \[text\]

> Example:

```css
command removeGroup(groupName){
  permission = "removeGroup";
  execute(){
    player.removeGroup(groupName);
    player.message("You have been removed from " + groupName);
  }
}
```

