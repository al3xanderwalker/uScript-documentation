# groups

* Method: \[get\]
* Returns: \[array of rocketGroups\]

> Example:

```css
command groups(){
  permission = "groups";
  execute(){
    for(group in player.groups){
      player.message("You are in the group " + group.displayName);
    }
  }
}
```

