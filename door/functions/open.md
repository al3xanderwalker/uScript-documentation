# open

* Parameters: \[none\]

> #### Example:

```css
command openDoor(){
  permission = "openDoor";
  execute(){
    barricade = player.look.getBarricade();
    door = barricade.getDoor();
    door.open();
    player.message("Door set to open");
  }
}
```

