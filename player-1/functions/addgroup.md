# addGroup

* Parameters: \[text\]

> #### Example:

```css
command addGroup(groupName){
  permission = "addGroup";
  execute(){
    player.addGroup(groupName);
    player.message("You have been added to " + groupName);
  }
}
```

