# close

* Parameters: \[none\]

> #### Example:

```css
command closeDoor(){
  permission = "closeDoor";
  execute(){
    barricade = player.look.getBarricade();
    door = barricade.getDoor();
    door.close();
    player.message("Door set to closed");
  }
}
```

