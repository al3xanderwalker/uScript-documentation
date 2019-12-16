# hasDoor

* Returns: \[boolean\]

> #### Example:

```css
command isDoor(){
  permission = "isDoor";
  execute(){
    barricade = player.look.getBarricade();
    if(barricade.hasDoor()){
       player.message("This barricade is a door");
    }
    else{
      player.message("This barricade is not a door");
    }
  }
}
```

