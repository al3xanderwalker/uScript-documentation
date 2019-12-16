# getPoint

* Returns: \[vector3\]

> #### Example:

```css
command locationPosition(){
    permission = "locationPosition";
    execute(){
      location = player.look.getPoint();
      player.message("Locations Position: X: " + location.x + " Y: " + location.y + " Z: " + location.z);
    }
}
```

