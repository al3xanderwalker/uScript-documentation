# isOpen

* Method: \[get\]
* Returns: \[boolean\]

> #### Example:

```css
command isDoorOpen(){
  permission = "isDoorOpen";
  execute(){
    barricade = player.look.getBarricade();
    door = barricade.getDoor();
    if(door.isOpen){
      player.message("Door is Open");
    }
    else{
      player.message("Door is Closed");
    }
  }
}
```

