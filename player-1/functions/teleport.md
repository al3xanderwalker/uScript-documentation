# teleport

* Parameters: \[vector3\]

> #### Example:

```css
command teleportToMarker(){
  permission = "teleportToMarker";
  execute(){
    player.teleport(player.marker);
    player.message("You have been teleporteed to your marker!");
  }
}
```

