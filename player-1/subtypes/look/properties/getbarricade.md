# getBarricade

* Returns: \[barricade\]

> #### Example:

```css
command barricadePosition(){
    permission = "barricadePosition";
    execute(){
      barricade = player.look.getBarricade();
      player.message("Barricades Position: X: " + barricade.x + " Y: " + barricade.y + " Z: " + barricade.z);
    }
}
```

