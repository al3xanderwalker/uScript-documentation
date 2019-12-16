# marker

* Method: \[get\]
* Returns: \[vector3\]

> Example:

```css
command marker(){
  permission = "marker";
  execute(){
    player.message("Marker Position: X: " + player.marker.x + " Y: " + player.marker.y + " Z: " + player.marker.z);
  }
}
```

