# hasBed

* Parameters: \[none\]

> #### Example:

```css
command hasBed(){
  permission = "hasBed";
  execute(){
    if(player.hasBed()){
      player.message("You have a bed");
    }
    else{
      player.message("You do not have a bed");
    }
  }
}
```

