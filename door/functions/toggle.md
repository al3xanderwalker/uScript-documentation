# toggle

* Parameters: \[none\]

> #### Example:

```css
command toggleDoor(){
  permission = "openDoor";
  execute(){
    barricade = player.look.getBarricade();
    door = barricade.getDoor();
    door.toggle();
    player.message("Doors state has been toggled");
  }
}
```

