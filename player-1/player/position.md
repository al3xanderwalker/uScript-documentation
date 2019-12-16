# position

* Method: \[get\]
* Returns: \[vector3\]

> Example:

```css
command position(){
  permission = "position";
  execute(){
    player.message("Your Position: X: " + player.position.x + " Y: " + player.position.y + " Z: " + player.position.z);
  }
}
```

