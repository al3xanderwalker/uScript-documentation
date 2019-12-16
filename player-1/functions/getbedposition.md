# getBedPosition

* Parameters: \[none\]

> #### Example:

```css
command getBedPosition(){
  permission = "getBedPosition";
  execute(){
    bedPosition = player.getBedPosition();
    player.message("Bed Position: X: " + bedPosition.x + " Y: " + bedPosition.y + " Z: " + bedPosition.z);
  }
}
```

