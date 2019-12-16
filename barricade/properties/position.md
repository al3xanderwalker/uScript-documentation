# position

* Method: \[get\]
* Returns: \[vector3\]

> #### Example:

```css
command getBarricadePosition(){
  permission = "getBarricadePosition";
  execute(){
    barricade = player.look.getBarricade();
    player.message("Barricade Position: X: " + barricade.position.x + " Y: " + barricade.position.y + " Z: " + barricade.position.z);
  }
}
```

* Method: \[set\]
* Returns: \[vector3\]

> #### Example:

```css
command setBarricadePosition(){
  permission = "setBarricadePosition";
  execute(){
    barricade = player.look.getBarricade();
    barricade.position = player.position;
    player.message("Barricade position set to your location!");
  }
}
```

