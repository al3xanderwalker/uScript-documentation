# broken

* Method: \[get\]
* Returns: \[boolean\]

> Example:

```css
command isBroken(){
  permission = "isBroken";
  execute(){
    if(player.broken){
      player.message("Your legs are broken!");
    }
    else{
      player.message("Your legs are not broken!");
    }
  }
}
```

* Method: \[set\]
* Returns: \[boolean\]

> Example:

```css
command toggleBroken(){
  permission = "toggleBroken";
  execute(){
    if(player.broken){
      player.broken = false;
      player.message("Fixed Legs!");
    }
    else{
      player.broken = true;
      player.message("Broke Legs!");
    }
  }
}
```

