# setMarker

* Parameters: \[vector3\]

> #### Example:

```css
command setMarker(){
  permission = "setMarker";
  execute(){
    player.setMarker(player.position);
    player.message("You marker has been set to your location!");
  }
}
```

