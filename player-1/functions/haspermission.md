# hasPermission

* Parameters: \[text\]

> #### Example:

```css
command hasPermission(permissionName){
  permission = "hasPermission";
  execute(){
    if(player.hasPermission(permissionName)){
      player.message("You have the permission" + permissionName);
    }
    else{
      player.message("You do not have the permission" + permissionName);
    }
  }
}
```

